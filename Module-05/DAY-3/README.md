# Ex.No:5(C)    GETTER AND SETTER METHOD

## AIM:
To Create a java program to print the sum of two number using getter and setter method.

## ALGORITHM :
1.  Start the Program
2.	Define class `Employee`:
-	a) Private variables `n1` and `n2`
-	b) Method `setsum(int n1, int n2)` to set values of `n1` and `n2`
-	c) Method `getsum()` to calculate and print `sum = n1 + n2`
3.	In `main` class `main` method:
-	a) Use `Scanner` to read integers `n1` and `n2`
-	b) Create ` Employee ` object, set values, and call `getsum()`
4.	End


## PROGRAM:
 ```
/*
Program to implement a Getter and Setter using Java
Developed by: LISIANA T
RegisterNumber: 212222240053 
*/
```

## Sourcecode.java:
```
import java.util.Scanner;

class SumCalculator {
    private String num1;
    private String num2;

    public void setNum1(String num1) {
        this.num1 = num1;
    }

    public String getNum1() {
        return this.num1;
    }

    public void setNum2(String num2) {
        this.num2 = num2;
    }

    public String getNum2() {
        return this.num2;
    }

    public void calculateSum() {
        int n1 = Integer.parseInt(getNum1());
        int n2 = Integer.parseInt(getNum2());
        int sum = n1 + n2;
        System.out.println("Sum is " + sum);
    }
}

public class Main {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
        SumCalculator calculator = new SumCalculator();
        
        String number1 = scanner.nextLine();
        calculator.setNum1(number1);
        
        String number2 = scanner.nextLine();
        calculator.setNum2(number2);
        
        calculator.calculateSum();
        
        scanner.close();
    }
}
```

## OUTPUT:

![image](https://github.com/user-attachments/assets/d0a24137-56ec-4f53-9057-c0ae407c15cb)


## RESULT:
Thus the java program to print the sum of two number using getter and setter method was executed successfully.






