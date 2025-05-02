# Ex.No:2(C)    SINGLE ARRAY

## AIM:
To Write a Java program that creates integer array of 10 elements, accepts 10 values of arrays and print the array values in reverse order.
## ALGORITHM :
1.Start

2.Create an integer array Arr of size 10

3.For i from 0 to 9:

4.Read an integer from the user

5.Store the input in Arr[i]

6.Print "Reverse Array:"

7.For k from 9 down to 0:

8.Print Arr[k] followed by a space

9.End



## PROGRAM:
 ```
/*
Program to implement a Single Array using Java
Developed by: LISIANA T
RegisterNumber:  212222240053
*/
```

## Sourcecode.java:
```
import java.util.*; 
public class Main
{
    public static void main(String[] args) 
    { 
        Scanner sc = new Scanner(System.in); 
        //System.out.println("Enter 10 array elements:");
        int Arr[] = new int[10]; 
        for(int i = 0; i < Arr.length; i++) 
            Arr[i] = sc.nextInt(); 
        
        System.out.println("Reverse Array: "); 
        for (int k = Arr.length-1; k >= 0; k--) 
            System.out.print(Arr[k] + " "); 
    } 
}
```
## OUTPUT:
![image](https://github.com/user-attachments/assets/e4bc3402-84ba-43c1-8a6d-29835e70c1ad)



## RESULT:
Thus,  a Java program that creates integer array of 10 elements, accepts 10 values of arrays and print the array values in reverse order was executed successfully.


