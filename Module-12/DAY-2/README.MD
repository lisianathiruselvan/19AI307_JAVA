# Ex.No:12(B)   COMPARABLE & COMPARATOR INTERFACE
## AIM :
To Write a Java program to sort a list of characters in reverse order using Comparable interface.Apply LinkedList concepts.
## ALGORITHM :
1.	Start the Program.
2.	Import `java.util.*` and `java.util.Map.Entry`
3.	Define `Example6` class with `main` method:
-	a) Initialize `TreeMap<String, String> tree_map1`
-	b) Read integer `size` for entries count.
4.	Use a loop to:
-	a) Read `String` values `n1` and `s1`
-	b) Insert each pair into `tree_map1`
5.	Print `tree_map1` as `"Original TreeMap content: "`
6.	Define `sort_key` class that implements `Comparator<String>`:
-	Override `compare` method to compare `String` values `str1` and `str2` using
`compareTo`
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



## RESULT:
Thus a Java program to sort a list of characters in reverse order using Comparable interface.Apply LinkedList concepts.was executed successfully




