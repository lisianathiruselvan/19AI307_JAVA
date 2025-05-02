# Ex.No:3(D) STRING TOKENIZER IN JAVA

## AIM:
To Write a java program to print output upto separator symbol(,) based on input using nextToken method of the string tokenizer java.

## ALGORITHM :
1.Start the program.

2.Create a scanner object to read input from the user.

3.Prompt the user (implicitly) to enter a string (comma-separated values).

4.Read the full input line as a string and store it in a variable (str1).

5.Create a StringTokenizer object with:

6.The input string (str1)

7.A delimiter (,), which separates tokens

8.Check if there are more tokens available using hasMoreTokens().

9.If yes, retrieve the next token using nextToken().

10.Print the retrieved token prefixed with "Next token is : ".

11.End the program.

## PROGRAM:
 ```
/*
Program to implement a String Tokenizer using Java
Developed by: LISIANA T
RegisterNumber: 212222240053 
*/
```

## Sourcecode.java:
```
import java.util.Scanner;
import java.util.StringTokenizer;

public class Main {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
        String str1 = sc.nextLine();
        StringTokenizer st = new StringTokenizer(str1, ",");
        
        if (st.hasMoreTokens()) {
            System.out.println("Next token is : " + st.nextToken());
        }
    }
}
```

## OUTPUT:
![image](https://github.com/user-attachments/assets/a588f068-e5a7-4dbc-9197-5afece7e1f40)



## RESULT:
Thus a java program to print output upto separator symbol(,) based on input using nextToken method of the string tokenizer java was executed successfully.
