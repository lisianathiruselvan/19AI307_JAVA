# Ex.No:2(E)  SMALLEST ELEMENT IN AN ARRAY

## AIM:
To Develop a Java Program to sort the elements of an array in ascending order.
## ALGORITHM :
1.Start

2.Create a Scanner object to read input

3.Read an integer n which represents the size of the array

4.Declare an array arr of size n

5.For i from 0 to n - 1:

6. Read an integer from the user

7.Store it in arr[i]

8.For i from 0 to n - 1:

9.For j from i + 1 to n - 1:

10.If arr[i] > arr[j]:

11.Swap arr[i] and arr[j]

12.Print "Result of a Sorted Array :"

13.For i from 0 to n - 1:

14.Print arr[i] followed by a space

15.End
	

## PROGRAM:
 ```
/*
Program to implement a Smallest Element in an Array
Developed by: LISIANA T
RegisterNumber: 212222240053 
*/
```

## Sourcecode.java:
```
import java.util.Scanner;
public class Main
{
    public static void main(String[] args)
    {
        Scanner kbd=new Scanner(System.in);
        int n=kbd.nextInt();
        int[] arr=new int[n];
        for(int i=0;i<n;i++)
        {
            arr[i]=kbd.nextInt();
        }
        int temp=0;
        for(int i=0;i<arr.length;i++)
        {
            for(int j=i+1;j<arr.length;j++)
            {
                if(arr[i]>arr[j])
                {
                    temp=arr[i];
                    arr[i]=arr[j];
                    arr[j]=temp;
                }
            }
        }
        System.out.println("Result of a Sorted Array :");
        for(int i=0;i<n;i++)
        {
            System.out.printf("%d  ",arr[i]);
        }
    }
}
```
## OUTPUT:

![image](https://github.com/user-attachments/assets/7bf1dad6-ef03-4761-9e54-ca7c7abcc9a9)


## RESULT:
Thus Develop a Java Program to sort the elements of an array in ascending order has been successfully implemented.




