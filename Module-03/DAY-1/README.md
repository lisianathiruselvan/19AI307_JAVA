# Ex.No:3(A)  STRING AND ITS OPERATIONS IN JAVA
## AIM:
To create a java program to read input and print length of the string in java.

## ALGORITHM :

1.Initialize Scanner: Create a Scanner object to read user input.

2.Read Input: Capture the user's input using nextLine().

3.Calculate Length: Use input.length() to find the length of the string.

4.Output Result: Print the length with a message.

5.Close Scanner: Close the Scanner to release resources.

## PROGRAM:
 ```
/*
Program to implement a String and its Operations using Java
Developed by: LISIANA T
RegisterNumber: 212222240053
*/
```

## Sourcecode.java:
```
import java.util.Scanner;

public class StringLength {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
        
        
        String input = scanner.nextLine();
        
        System.out.println("The size of the String is " + input.length());
        
        scanner.close();
    }
}
```

## OUTPUT:

![image](https://github.com/user-attachments/assets/852ea1fa-8c4b-4121-ad74-b5c6039ca897)


## RESULT:
Thus the java Program to read input and print length of the string in java was executed successfully.

