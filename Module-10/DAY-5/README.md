# Ex.No:10(E)  JAVA LINKEDHASH SET

## AIM:
To Write a java program to check wheather LinkedHashSet contains an element or not. It returns true if the set contains element, otherwise returns false.Apply clear method.
## ALGORITHM :
 1. Create a LinkedHashSet to store unique strings in insertion order.
 2. Read the number of elements and insert each string into the set.
 3. Display all elements of the set.
 4. Check and print if the set is empty before and after clearing it.
 5. Clear the set and confirm it's empty again.


## PROGRAM:
 ```
/*
Program to implement a LINKEDHASH SET
Developed by: LISIANA T
RegisterNumber: 212222240053 
*/
```

## Sourcecode.java:
```
import java.util.*;  
public class HashSetRemoveExample1 {  
    public static void main(String[] args) {  
        LinkedHashSet<String> hset=new LinkedHashSet<String>();  
        Scanner sc=new Scanner(System.in);
        int size=sc.nextInt();
        for(int i=0;i<size;i++)
        {
          hset.add(sc.next());       
        }
       
         
        
            System.out.println("HashSet Elements: "+hset);   
       
            System.out.println("Is the set empty: "+hset.isEmpty());  
            hset.clear();  
            System.out.println("Is the set empty: "+hset.isEmpty());  
    }  
}
```


## OUTPUT:
![image](https://github.com/user-attachments/assets/bd12ab32-de1b-4026-ad70-d0d77cbf281a)



## RESULT:
The Java program successfully checks whether the LinkedHashSet contains the specified element and returns true if it exists, otherwise false. The clear() method is also successfully applied to empty the set.
