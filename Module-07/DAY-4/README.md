# Ex.No:7(D) SYNCHRONIZATION
## AIM:
 To Write a Java Program to display Even number up to the range using static Synchronization block for the below Scenario

1. In a Class Table  create a function for displaying Even number up to the range with static synchronization block using void even (int n) function

Note :Assume Sleep as 400 ms  i.e Thread.Sleep(400)

## ALGORITHM :
1.	Define a method Even(int n) in class Table to print even numbers up to n.
2.	Use synchronized(this) to ensure only one thread can execute the block at a time.
3.	Initialize i = 2 and loop through even numbers (incrementing by 2) until i <= n.
4.	Print each even number, followed by a space.
5.	Use Thread.sleep(400) to pause the thread briefly, and handle any exceptions that may occur.



## PROGRAM:
 ```
/*
Program to implement a Packages using Java
Developed by: LISIANA T
RegisterNumber:  212222240053
*/
```

## Sourcecode.java:
```
class Table
  {
    void Even(int n)
    {
      synchronized(this)
     {  
     
       int i=2;
     System.out.print("List of Even numbers for " +n+ " : ");
      while(i<=n)  
        {  

        System.out.print(i +" ");   
       
        i=i+2;  
        } 
        System.out.println();
         try
     {  
      Thread.sleep(400);  
     }
     catch(Exception e){System.out.println(e);}  
      
     
     
     
     }
   }  
  }
```


## OUTPUT:

![image](https://github.com/user-attachments/assets/c79ea266-e62f-4552-ae78-5af0ab502ae2)


## RESULT:
Thus the java program for synchronization was executed successfully.

