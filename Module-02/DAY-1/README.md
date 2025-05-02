# Ex.No:2(A)  STATIC METHOD

## AIM:
To Determine if the number is a multiple of 10 using staticmethod 

## ALGORITHM :
1.  Start
2.  Declare a method isMultipleOfTen(int num):
3.  Return true if num % 10 == 0, else return false.
4.  In the main method:
     Create a Scanner object to read user input.
     Read an integer input from the user and store it in variable num.
 5. Call the method isMultipleOfTen(num):
      If it returns true, print "num is a multiple of 10."
      Else, print "num is not a multiple of 10.
 6. End



## PROGRAM:
 ```
/*
Program to implement a Static method using Java
Developed by: LISIANA T
RegisterNumber:  212222240053
*/
```

## Sourcecode.java:
```
import java.util.Scanner;

public class MultipleCheck {
    static boolean isMultipleOfTen(int num) {
        return num % 10 == 0;
    }
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
        int num = sc.nextInt();
        if (isMultipleOfTen(num)) {
            System.out.println(num + " is a multiple of 10.");
        } else {
            System.out.println(num + " is not a multiple of 10.");
        }
    }
}
```






## OUTPUT:

![image](https://github.com/user-attachments/assets/3baf2be1-cbf7-4756-9631-a2d8df66867e)


## RESULT:
Thus the java program for to Determine if the number is a multiple of 10 using staticmethod  has been executed successfully.

