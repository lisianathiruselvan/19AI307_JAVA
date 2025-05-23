# Ex.No:9(A)          DATA I/O STREAM
## AIM:
To Implement a Java Program to write a integer '65'  in a file "testout.txt" using DataOutputStream

## ALGORITHM :
1. Create a FileOutputStream to write to a file named testout.txt.
2. Wrap it with DataOutputStream to write primitive data types.
3. Write an integer value (65) to the file using writeInt().
4. Close both streams to release resources.
5. Print a success message to indicate completion.


## PROGRAM:
 ```
/*
Program to implement a DATA I/O STREAM using Java
Developed by: LISIANA T
RegisterNumber: 212222240053 
*/
```

## Sourcecode.java:
```
FileOutputStream fout=new FileOutputStream("testout.txt");    
DataOutputStream dout=new DataOutputStream(fout);
dout.writeInt(65);    
dout.close();    
fout.close();
System.out.println("Successfully Completed");
```

## OUTPUT:
![image](https://github.com/user-attachments/assets/2bf6d812-b5df-4e16-8c03-ccc786588fbc)


## RESULT:
Thus the Java Program  Implement a Java Program to write a integer '65'  in a file "testout.txt" using DataOutputStream was executed and verified successfully.

