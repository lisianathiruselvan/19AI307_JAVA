# Ex.No:3(B) STRING BUFFER IN JAVA

## AIM:
To Write a java program to print the text based on testcase write the program and use string buffer and append method.

## ALGORITHM :
1.	Start the program.
2.	Import `Scanner` and define class `concat`
3.	In `main`:
-	a) Create `Scanner` object `sc`
-	b) Read two strings `a` and `b` from user input
4.	Create a `StringBuffer` object `sb` initialized with string `a`
5.	Append a space and string `b` to `sb`
6.	Print the concatenated result from `sb`
7.	End


## PROGRAM:
 ```
/*
Program to implement a String Buffer using Java
Developed by: LISIANA T
RegisterNumber: 212222240053 
*/
```

## Sourcecode.java:

```
import java.util.*;
public class Main
{
    public static void main(String args[])
    {
           Scanner sc=new Scanner(System.in);
           String str=sc.nextLine();
           StringBuffer sb1=new StringBuffer(str);

           System.out.println("sb1 = "+sb1.append('s')); 
    }
}
```

## OUTPUT:

![image](https://github.com/lisianathiruselvan/19AI307_JAVA/blob/1a33fc6f1003a21f65e5180d1e2ea8264a8f3149/Screenshot%202025-05-02%20160247.png)

## RESULT:
Thus the java program use append() method concatenates the given argument with this String and use stringbuffer class was executed successfully.
