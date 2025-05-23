# Ex.No:12(C)             JAVA STACK & VECTOR
 ## AIM :

To Write a java program to read and print the elements  and to fetching the specific element from the index of 3 using vector in java collection.(Use elementAt() method)
## ALGORITHM :

1.	Start the Program
2.	Create a Vector to store strings from user input.
3.	Read the number of input pairs and add two strings per iteration.
4.	Print the complete vector after input is collected.
5.	Access and display the element at the 4th position (index 3).
6.	End the program.
7.	End.



## PROGRAM:
 ```
/*
Program to implement a JAVA STACK & VECTOR  using Java
Developed by: LISIANA T
RegisterNumber: 212222240053 
*/
```

## Sourcecode.java:

```
import java.util.*;
public class VectorDemo {
	public static void main(String args[])
	{
		Vector<String> vec_tor = new Vector<String>();
        Scanner sc=new Scanner(System.in);
        int size=sc.nextInt();
	    for(int i=0;i<size;i++)
	    {
		vec_tor.add(sc.next());
	    vec_tor.add(sc.next());
	    }
	   	System.out.println("The vector is: " + vec_tor);

	    System.out.println("The element is: "
                           + vec_tor.elementAt(3));
		}
}

```

## OUTPUT:

![image](https://github.com/user-attachments/assets/6f0a05a8-89e3-4103-90de-0d91c8fbf481)



## RESULT:

Thus the java program to read and print the elements  and to fetching the specific element from the index of 3 using vector in java collection.(Use elementAt() method) was executed successfully.








