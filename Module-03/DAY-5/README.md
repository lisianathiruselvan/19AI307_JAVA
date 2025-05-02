# Ex.No:3(E)  STRINGBUILDER OBJECT REFERENCE IN JAVA

## AIM:
To Write a java program to calculates the number of tokens present in the tokenizer String.

## ALGORITHM :
1.Start the program.

2.Create a Scanner object to read user input.

3.Read a string from the user and store it in str1.

4.Create a StringBuffer object sb, initialized with str1.

5.Use replace(start, end, string) method of StringBuffer to:

6.Replace characters in the range from index 1 (inclusive) to index 3 (exclusive)

7.With the string "Java"

8.End the program.


## PROGRAM:
 ```
/*
Program to implement a StringBuilder Object Reference in Java
Developed by: LISIANA T
RegisterNumber: 212222240053 
*/
```

## Sourcecode.java:
```
import java.util.*;
public class StringTokenizer3
{
    public static void main(String[] args)
    {
        Scanner sc=new Scanner(System.in);
        String str1="Hello Everyone Have a nice day";
        StringTokenizer st=new StringTokenizer(str1," ");
        System.out.println("Total number of Tokens: "+st.countTokens());
    }
}
```
## OUTPUT:
![image](https://github.com/user-attachments/assets/92afaed0-2a35-4b87-a088-f59aeb3511e5)



## RESULT:
Thus To Write a java program to calculates the number of tokens present in the tokenizer String was successfully implemented .

