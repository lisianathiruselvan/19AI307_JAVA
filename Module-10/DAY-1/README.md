# Ex.No:10(A)         JAVA COLLECTION FRAMEWORK –ARRAY LIST
## AIM:
 To Create an arraylist , add elements in an arraylist and then display in descending order.

## ALGORITHM:
1.	Start the Program
2.	Create an ArrayList to store strings and a Scanner for input.
3.	Read an integer n representing the number of strings to input.
4.	Read n strings and add them to the list.
5.	Sort the list in reverse (descending) alphabetical order.
6.	Print the sorted list.
7.	End

## PROGRAM:
 ```
/*
Program to implement a ARRAY LIST using Java
Developed by: LISIANA T
RegisterNumber: 212222240053 
*/
```

## Sourcecode.java:
```
import java.util.*;
public class Main
{
    public static void main(String[] args)
    {
        ArrayList<String> obj=new ArrayList<String>();
        Scanner sc=new Scanner(System.in);
        int n=sc.nextInt();
        for(int i=0;i<n;i++)
        {
            obj.add(sc.next());
        }
        Collections.sort(obj,Collections.reverseOrder());
        System.out.println(obj);
        
    }
}
```





## OUTPUT:

![image](https://github.com/user-attachments/assets/e800ef18-171b-4891-9d67-c4fda7933d59)


## RESULT:
TThus the Java Program Create an arraylist , add elements in an arraylist and then display in descending order was executed successfully.

