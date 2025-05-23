# Ex.No:7(A)           EXCEPTION HANDLING-RUN TIME EXCEPTION
## AIM:
  To Develop a Java Program for Write a java program to demonstrate multiple catch blocks for multiple exceptions
## ALGORITHM :
1.  Start the Program
2.	Read input from the user using a Scanner.
3. Try to convert the input string to an integer.
4. Compute 10 % a to potentially trigger ArithmeticException if a is zero.
5. Catch ArithmeticException and display an appropriate message.
6. Catch NumberFormatException and display a message if input is not a valid integer.
7. End

## PROGRAM:
 ```
/*
Program to implement a Exception Handling-Run Time Exception using Java
Developed by: LISIANA T
RegisterNumber: 212222240053 
*/
```

## Sourcecode.java:
```
import java.util.Scanner;

public class HelloWorld {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
        String input = sc.nextLine();
        try {
            int a = Integer.parseInt(input);
            int result = 10 % a;
            System.out.println("Value: " + a);
        } catch (ArithmeticException e) {
            System.out.println("Arithmetic Exception : java.lang.ArithmeticException: / by zero");
        } catch (NumberFormatException e) {
            System.out.println("Number Format Exception java.lang.NumberFormatException: For input string: \"" + input + "\"");
        }
    }
}
```

## OUTPUT:

![image](https://github.com/user-attachments/assets/00aeb623-a368-4be0-8b7c-47481a8fb405)


## RESULT:
Thus the Java Program for Write a java program to demonstrate multiple catch blocks for multiple exceptionswas executed successfully.

