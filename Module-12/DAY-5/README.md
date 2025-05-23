# Ex.No:12(E)  JAVA DEQUEUE

## AIM:
To Write a java program to display the added elements from the Dequeue using java collection.
## ALGORITHM :

1.	Create a Deque using LinkedList to store integers.
2.	Read the number of elements and add them to the deque.
3.	Display the current elements of the deque.
4.	Add the element 150 to the end of the deque using addLast().
5.	Print the deque after modification.

## PROGRAM:
 ```
/*
Program to implement a JAVA DEQUEUE
Developed by: LISIANA T
RegisterNumber: 212222240053 
*/
```

## Sourcecode.java:
```
import java.util.*;

public class deQueueDemo {
	

	public static void main(String args[])
	{
	
		Deque<Integer> dq = new LinkedList<Integer>();
        
	    Scanner sc=new Scanner(System.in);
	    int size=sc.nextInt();
	    for(int i=0;i<size;i++){
	        dq.add(sc.nextInt());
	    }
	    System.out.println("Display the element of Dequeue:");
		System.out.println(dq);
        System.out.println("Display the element of Dequeue after add first element :");
        dq.addLast(150);
		System.out.println(dq);
		
	}
}
```

## OUTPUT:

![image](https://github.com/user-attachments/assets/54ec2c93-b95d-4b88-91ea-67e6f45a6b96)


## RESULT:

Thus  a java program to display the added elements from the Dequeue using java collection has been executed successfully.

