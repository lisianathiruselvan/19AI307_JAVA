# Ex.No:5(B) TIGHTLY ENCAPSULATED CLASS

## AIM:
To Create a Create a java program for given number is armstrong number or not all must use tightly encapsulated class. 

## ALGORITHM :

1.Read a number from the user as a string input.

2.Set the input number in an ArmstrongChecker object using a setter method.

3.Convert the number to an integer and calculate the sum of its digits each raised to the power of the number of digits.

4.Compare the calculated result with the original number.

5.Print whether the number is an Armstrong number based on the comparison result.

## PROGRAM:
 ```
/*
Program to implement a tightly encapsulated class using Java
Developed by: LISIANA T
RegisterNumber:  212222240053 
*/
```

## Sourcecode.java:
```
import java.util.Scanner;

class ArmstrongChecker {
    private String number;

    public void setNumber(String number) {
        this.number = number;
    }

    public String getNumber() {
        return number;
    }

    public boolean isArmstrong() {
        int num = Integer.parseInt(number);
        int originalNum = num;
        int result = 0;
        int digits = number.length();

        while (num != 0) {
            int digit = num % 10;
            result += Math.pow(digit, digits);
            num /= 10;
        }

        return result == originalNum;
    }
}

public class Main {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
        String input = sc.nextLine();

        ArmstrongChecker checker = new ArmstrongChecker();
        checker.setNumber(input);

        if (checker.isArmstrong()) {
            System.out.println(input + " is a armstrong number");
        } else {
            System.out.println(input + " is not a armstrong number");
        }
    }
}
```

## OUTPUT:




## RESULT:
Thus a java program to find the given number is armstrong or not using tightly encapsulated class was executed successfully.



