# Ex.No:12(D) JAVA QUEUE
## AIM:
To Write a java program to print the top element and removing it from the Priority Queue Container.

## ALGORITHM :
1.	Start the Program
2.	Import `PriorityQueue` and `Scanner`
3.	Define class `Main` with `main` method:
-	a) Initialize `Scanner` to read input
-	b) Create a `PriorityQueue` of integers
4.	Read integer `n` from user input for the number of elements
5.	Use a loop to:
-	a) Read integers and add them to the `PriorityQueue`
6.	Check if the `PriorityQueue` is not empty:
-	a) Remove and display the highest-priority element using `poll()`
7.	Display the remaining elements in the `PriorityQueue`
8.	End.





## PROGRAM:
 ```
/*
Program to implement a JAVA QUEUE using Java
Developed by: LISIANA T
RegisterNumber: 212222240053 
*/
```

## Sourcecode.java:

```
import java.util.*;

public class PriorityQueueDemo {
	

	public static void main(String args[])
	{
	
		PriorityQueue<Integer> pQueue = new PriorityQueue<Integer>();
        
	    Scanner sc=new Scanner(System.in);
	    int size=sc.nextInt();
	    for(int i=0;i<size;i++){
	        pQueue.add(sc.nextInt());
	    }
	    System.out.println("Display the remove element of PriorityQueue:");
		System.out.println(pQueue.poll());
		System.out.println("Display the element of PriorityQueue:");
		System.out.println(pQueue);

		
	}
}
```


## OUTPUT:
![image](https://github.com/user-attachments/assets/c08a2741-47f0-4f9e-a4c1-a36e5b7c3d54)


## RESULT:
Thus a java program to print the top element and removing it from the Priority Queue Container.
was executed successfully.


