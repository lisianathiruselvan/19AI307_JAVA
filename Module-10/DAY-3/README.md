# Ex.No:10(C)             JAVA LIST INTERFACE
 ## AIM :

To Create a List interface implemented by arraylist class , adding n elements to object of List interface and display the list is empty or not.


## ALGORITHM :
1.	Start
2.	Import `java.util.*`
3.	Define class `Main` with `main` method:
-	a) Initialize `Scanner` and an empty `ArrayList` named `list`
-	b) Read integer `n`
4.	Check if `list` is empty, print corresponding message
5.	Use a loop to add `n` strings to `list`
6.	Check if `list` is empty again, print corresponding message
7.	End

## PROGRAM:
 ```
/*
Program to implement a JAVA LIST INTERFACE using Java
Developed by: LISIANA T
RegisterNumber: 212222240053 
*/
```

## Sourcecode.java:
```
import java.util.*;


public class GFG {

	public static void main(String args[])
	{
		Scanner sc=new Scanner(System.in);
		List<String> al = new ArrayList<>();
        int size=sc.nextInt();
        for(int i=0;i<size;i++)
        {
				al.add(sc.next());
        }

		for (int i = 0; i < size; i++) {
  
            
            System.out.println(al.get(i) + " ");
        }
	
	}
}
```

## OUTPUT:

![image](https://github.com/user-attachments/assets/f3fc8af0-23c3-46d5-b5fb-b961b6f5194d)


## RESULT:
Thus the java program implemented a List interface for array list was executed and verified successfully.










