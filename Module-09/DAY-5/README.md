# Ex.No:9(E) STRING WRITER

## AIM:
To write a Java program that reads a string from the user and prints it using the StringWriter class.
## ALGORITHM :

a.	Start the program.
b.	Import java.io.* and java.util.Scanner.
c.	Create a Scanner object to read input from the user.
d.	Read a string from the user.
e.	Create a StringWriter object.
f.	Write the string to the StringWriter object.
g.	Convert the StringWriter content to a string using .toString().
h.	Print the result on the output screen.
i.	Close the writer.
j.	End the program.


## PROGRAM:
 ```
/*
Program to implement a STRING WRITER
Developed by: LISIANA T
RegisterNumber: 212222240053 
*/
```

## Sourcecode.java:
```
import java.io.StringWriter;
import java.util.*;
public class Main
{
  public static void main(String[] args)
  {
   Scanner sc=new Scanner(System.in);
   String data=sc.nextLine();
    try {
        StringWriter sw=new StringWriter();
        sw.write(data);
        System.out.println("Data in the StringWriter: "+data);
    }

    catch(Exception e)
    {
      e.getStackTrace();
    }
  }
}

```


## OUTPUT:

![image](https://github.com/user-attachments/assets/acd10b41-9b50-434f-854f-0e39c481b1e4)


## RESULT:
Thus, implementation of  a Java program was successfully reads a string from the user and uses StringWriter to write and print the string to the output screen.

