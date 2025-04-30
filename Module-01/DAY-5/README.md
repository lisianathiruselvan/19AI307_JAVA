# Ex.No:1(E)  STATIC VARIABLE

## AIM:
To Write a Java program that reads in two floating-point numbers and tests whether they are the same up to three decimal places.
## ALGORITHM :
1. Start the program.
2. Create a Scanner object to read input from the user.
3. Read the first double value and store it in variable n1.
4. Read the second double value and store it in variable n2.
5. Multiply both n1 and n2 by 1000 to shift the decimal three places.
6. Typecast the results of both multiplications to int to discard digits beyond the third decimal place.
7. Compare the integer values of both results:
8. If they are equal, print "They are the same up to three decimal places"
9.  Else, print "They are different".
10.  End the program.

## PROGRAM:
 ```
/*
Program to implement a Static Variable using Java
Developed by: LISIANA T
RegisterNumber:  212222240053
*/
```

## Sourcecode.java:
```
import java.util.Scanner;
public class Main
{
    public static void main(String[] args)
    {
        Scanner kbd=new Scanner(System.in);
        double n1=kbd.nextDouble();
        double n2=kbd.nextDouble();
        if(n1==n2)
        {
            System.out.println("They are the same up to three decimal places");
        }
        else
        {
            System.out.println("They are different");
        }
    }
}
```


## OUTPUT:

![image](https://github.com/user-attachments/assets/0f759899-1c77-44fd-9906-7ff31d441c61)



## RESULT:
Thus, the Java program that reads in two floating-point numbers and tests whether they are the same up to three decimal places was correctly implemented and verified successfully. 
 
