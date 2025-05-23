# Ex.No:11(B)   JAVA MAP & HASHMAP AND HASHTABLE
## AIM :
To Create a java program to retrieve the key and value from hashmap and display the size of the hashmap and clear the hashmap using clear method concepts.

## ALGORITHM :

1.	Start
2.	Create a HashMap to store integer keys and string values.
3. Read key-value pairs from user input and insert them into the map.
4. Iterate over the map keys and print each key-value pair.
5. Display the size of the map before and after clearing it.
6. Clear the map to remove all entries.
7.	End




## PROGRAM:
 ```
/*
Program to implement a JAVA MAP & HASHMAP AND HASHTABLE using Java
Developed by: LISIANA T
RegisterNumber: 212222240053 
*/
```

## Sourcecode.java:
```
import java.util.*;  
public class Mapp{  
 public static void main(String args[]){ 
     
  HashMap<Integer,String> map=new HashMap<Integer,String>(); 
  Scanner sc=new Scanner(System.in);
  
  int size=sc.nextInt();
  for(int i=0;i<size;i++)
  {
  Integer a=sc.nextInt();
  String b=sc.next();
  map.put(a,b);  
  } 
 
  
 Iterator<Integer> keySetIterator = map.keySet().iterator(); while(keySetIterator.hasNext()){ Integer key = keySetIterator.next(); System.out.println("key: " + key + " value: " + map.get(key)); }

System.out.println("Size of Map: " + map.size()); map.clear(); 
System.out.println("Size of Map: " + map.size()); 

 }  
}  
```

## OUTPUT:
![image](https://github.com/lisianathiruselvan/19AI307_JAVA/blob/25f233883ca5e83685560476c1ca3fcefbfff178/Module-11/DAY-2/image.png)

## RESULT:
Thus a java program to retrieve the key and value from hashmap and display the size of the hashmap and clear the hashmap using clear method concepts was executed successfully.







