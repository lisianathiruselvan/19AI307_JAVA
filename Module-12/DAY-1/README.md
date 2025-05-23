# Ex.No:12(A)         JAVA TREE MAP
## AIM:
 To Write a Java program to copy a Tree Map content to another Tree Map content.

## ALGORITHM :

1.	Start the Program
2.	Create two TreeMap objects to store string key-value pairs in sorted order.
3.	Read and insert entries into map1 and map2 from user input.
4.	Display the contents of both maps before merging.
5.	Use putAll() to copy all entries from map2 into map1.
6.	Print the updated map1 after merging with map2.
7.	End



## PROGRAM:
 ```
/*
Program to implement a JAVA TREE MAP using Java
Developed by: LISIANA T
RegisterNumber: 212222240053 
*/
```

## Sourcecode.java:
```
import java.util.*;

public class TreeMapCopyExample {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);

        int n1 = sc.nextInt();
        TreeMap<String, String> map1 = new TreeMap<>();
        for (int i = 0; i < n1; i++) {
            String key = sc.next();
            String value = sc.next();
            map1.put(key, value);
        }

        int n2 = sc.nextInt();
        TreeMap<String, String> map2 = new TreeMap<>();
        for (int i = 0; i < n2; i++) {
            String key = sc.next();
            String value = sc.next();
            map2.put(key, value);
        }

        System.out.println("Tree Map 1: " + map1);
        System.out.println("Tree Map 2: " + map2);

        map1.putAll(map2);
        System.out.println("After coping map2 to map1: " + map1);
    }
}
```

## OUTPUT:

![image](https://github.com/user-attachments/assets/309ea768-e76f-4fbc-96cd-bb1d8e017e71)


## RESULT:
Thus  a Java program to copy a Tree Map content to another Tree Map content. was executed successfully.
