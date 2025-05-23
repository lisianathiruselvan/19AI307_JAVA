# Ex.No:8(D) BUFFER INPUT/OUTPUT STREAM

## AIM:
 To Write a java Program for reading the characters from the user and print in the display screen using Buffered InputStream

## ALGORITHM :
1.	Create a BufferedInputStream object to read input from the keyboard (System.in).
2.	Display a prompt to the user for input.
3.	Read input character by character using read() method until end-of-file (-1) is detected.
4.	Convert each byte to a character and print it.
5.	Close the input stream in the finally block to release resources.



## PROGRAM:
 ```
/*
Program to implement a Buffer Input/Output Stream using Java
Developed by: LISIANA T
RegisterNumber: 212222240053 
*/
```

## Sourcecode.java:
```
import java.io.*;  
import java.io.*;
public class Main  
{
  public static void main(String[] args) throws IOException
  {
   BufferedInputStream bf = new BufferedInputStream(System.in)   ;
    try{
          int i;
        while((i=bf.read())!=-1)
        {
            char c=(char) i;
            System.out.println(c);  
    }
    }
finally{
        bf.close();
}   
}   
}
```


## OUTPUT:

![image](https://github.com/user-attachments/assets/9ccde91f-637e-4eba-9b8a-b9f945423d1b)


## RESULT:
Thus, the java program file for reading the characters from the user and print in the display screen using Buffered InputStream was executed and done successfully.


