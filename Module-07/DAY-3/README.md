# Ex.No:7(C)             THREAD IN JAVA
## AIM:
 To Write a Java program to add two numbers by creating Thread using Runnable Interface.


## ALGORITHM :
1.  Start the Program
2.	Implement the Runnable interface in the class Multi and define the run() method.
3.	Read two integers using a Scanner inside the run() method.
4.	Compute their sum and print the result inside the run() method.
5.	In the main() method, create an object of Multi.
6.	Pass the object to a Thread and start it using start() to run the code in a separate thread.
6.	End


## PROGRAM:
 ```
/*
Program to implement a Thread concepts using Java
Developed by: LISIANA T
RegisterNumber: 212222240053 
*/
```

## Sourcecode.java:
```
   import java.util.*;
    public class Multi implements Runnable
    {  
        Scanner sc=new Scanner(System.in);
        
    public void run()
    {  
        int a=sc.nextInt();
        int b=sc.nextInt();
        int sum=a+b;
        System.out.println("Result: " +sum);  
    }  
    public static void main(String args[]){  
    Multi m1=new Multi(); 
    Thread t1 =new Thread(m1); 
    t1.start();  
     }  
    }
```



## OUTPUT:

![image](https://github.com/user-attachments/assets/38ec2640-e607-413f-b922-85ddf62ff405)


## RESULT:
Thus Java program to add two numbers by creating Thread using Runnable Interface. was executed successfully.







