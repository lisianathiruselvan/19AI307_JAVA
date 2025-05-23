# Ex.No:8(A)           IO-FILE STREAM
## AIM:
To Write a Java Program for  displaying the data from the file "sample.txt" using FileInputStream

## ALGORITHM :
1.  available() returns the number of bytes that can be read without blocking.
2.  The file is read byte-by-byte in a loop until EOF (-1).
3.  Data is printed as characters.
4.  FileInputStream is closed after reading to release resources.
5.  IOException is caught and handled.

## PROGRAM:
 ```
/*
Program to implement a IO File Stream using Java
Developed by: LISIANA T
RegisterNumber: 212222240053 
*/
```

## Sourcecode.java:
```
   
     try
           {
           
             
           // Write a Source code for checking available byes in the file using available() and print the data in the file
           FileInputStream f=new FileInputStream("sample.txt");
           System.out.println("Data in the file:");
           int i=f.read();
           while(i!=-1)
           {
               System.out.print((char)i);
               i=f.read();
           }
      
           } 
            
           
           catch (IOException e) 
      {
      System.out.println("An error occurred.");
     
    }
```

## OUTPUT:

![image](https://github.com/user-attachments/assets/4b1a5b19-2b05-4364-a454-e72e2dc454dd)


## RESULT:
Thus the implementation of a Java Program to Write a Java Program for  displaying the data from the file "sample.txt" using FileInputStream was executed and verified successfully

