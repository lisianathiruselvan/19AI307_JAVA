# Ex.No:11(A)         JAVA TREESET
## AIM:
 To Write a Java program to create a new tree set, add n number of  colors (string) and print out the tree set.

## ALGORITHM :
1.	Create a TreeSet to store strings in sorted (natural) order.
2.	Read the number of elements to be inserted from user input.
3.	Add each input string to the TreeSet.
4.	Automatically sort and store elements as they are added.
5.	Display the contents of the TreeSet.



## PROGRAM:
 ```
/*
Program to implement a JAVA TREESET using Java
Developed by: LISIANA T
RegisterNumber: 212222240053 
*/
```

## Sourcecode.java:
```
import java.util.*;
public class color {
  public static void main(String[] args) {
      Scanner sc=new Scanner(System.in);
  TreeSet<String> tree_set = new TreeSet<String>();
  int size=sc.nextInt();
  for(int i=0;i<size;i++)
  {
  tree_set.add(sc.next());
  }
  System.out.println("Tree set: ");
  System.out.println(tree_set);
 }
}


```


## OUTPUT:

![image](https://github.com/user-attachments/assets/5cc79157-9196-4d03-8085-48406a59bc54)


## RESULT:
Thus  a Java program to create a new tree set, add n number of  colors (string) and print out the tree set. was executed successfully.

