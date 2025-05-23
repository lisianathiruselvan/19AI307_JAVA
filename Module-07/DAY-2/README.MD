# Ex.No:7(B) EXCEPTION HANDLING-FINALLY
## AIM:
To Write a Java program to demonstrate control flow of try-catch-finally clause when ArithmeticException occur in try block and handled in catch block

## ALGORITHM :
1.	Start the Program

2.	Read an integer input from the user.

3. Try dividing a fixed number a = 100 by the input b.

4. Catch ArithmeticException if division by zero occurs and print the exception.

5. Execute the finally block to print a message, whether or not an exception occurred.

6. Continue with the rest of the program after the try-catch-finally block.

7.	End



## PROGRAM:
 ```
/*
Program to implement a Exception Handling-Finally using Java
Developed by: LISIANA T
RegisterNumber: 212222240053 
*/
```

## Sourcecode.java:
```
import java.util.*;
public class HelloWorld {
    public static void main(String[] args) 
    {
      
       Scanner sc=new Scanner(System.in);
      try {
         int b=sc.nextInt();
         int a=100;
          int c = a/b;
          System.out.println("Valid Statement :" +c);
      }
         
        catch(ArithmeticException ex)
        {
            System.out.println("Exception: " +ex);
        }
         
        finally
        {
            System.out.println("Finally block executed");
        }
         
        // rest program will be executed
        System.out.println("Outside try-catch-finally clause");
    }
}

```

## OUTPUT:
![image](https://github.com/lisianathiruselvan/19AI307_JAVA/blob/f6b21c1849c1ce23b97ec26d26a68fd9b460a8e2/Module-07/DAY-2/image.png)

## RESULT:
Thus the Java program to demonstrate control flow of try-catch-finally clause when NumberFormatException occur in try block and handled in catch block was executed successfully.



