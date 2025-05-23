# Ex.No:12(B)   COMPARABLE & COMPARATOR INTERFACE
## AIM :
To Write a Java program to sort a list of characters in reverse order using Comparable interface.Apply LinkedList concepts.
## ALGORITHM :
1.	Start the Program.

2.	Create a LinkedList to store strings from user input.

3. Read the number of elements and add them to the list.

4. Sort the list using a custom comparator based on natural string order.

5. Iterate through the sorted list.

6. Print each element from the list.

7.	End


## PROGRAM:
 ```
/*
Program to implement a COMPARABLE & COMPARATOR INTERFACE using Java
Developed by: LISIANA T
RegisterNumber: 212222240053 
*/
```

## Sourcecode.java:
```
import java.util.*;

public class Main {
 public static void main(String[] args) {
 
  LinkedList<String> list2 = new LinkedList<String>();
  Scanner sc=new Scanner(System.in);
  int size=sc.nextInt();
  for(int i=0;i<size;i++)
  {
  list2.add(sc.next());
  }
  list2.sort(new Comparator<String>() {
   @Override
   public int compare(String num1, String num2) {    
    return num1.compareTo(num2);
   }
   
  });
  

  for (String num : list2) {
   System.out.println(num);
  }
 }
}
```

## OUTPUT:

![Iimage](https://github.com/lisianathiruselvan/19AI307_JAVA/blob/e5e04019d3dee804b994573ea770b01753118523/Module-12/DAY-2/image.png)

## RESULT:
Thus a Java program to sort a list of characters in reverse order using Comparable interface.Apply LinkedList concepts.was executed successfully




