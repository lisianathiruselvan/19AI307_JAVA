# Ex.No:11(C)             JAVA LINKED HASHMAP
 ## AIM :

To Create a java program to retrieve the key and value from linkedhashmap for all input value.



## ALGORITHM :

1.	Start the Program
2.	Create a LinkedHashMap to store key-value pairs with insertion order preserved.
3.	Read the number of entries and input each integer-string pair into the map.
4.	Use an iterator to traverse the map’s keys in insertion order.
5.	Print each key along with its corresponding value.
6.	End the program after displaying all entries.
7.	End


## PROGRAM:
 ```
/*
Program to implement a JAVA LINKED HASH MAP using Java
Developed by: LISIANA T
RegisterNumber: 212222240053 
*/
```

## Sourcecode.java:
```
import java.util.*;  
public class Mapp{  
 public static void main(String args[]){ 
     
  LinkedHashMap<Integer,String> map=new LinkedHashMap<>(); 
  Scanner sc=new Scanner(System.in);
  
  int size=sc.nextInt();
  for(int i=0;i<size;i++)
  {
  Integer a=sc.nextInt();
  String b=sc.next();
  map.put(a,b);  
  } 
 
  
 Iterator<Integer> keySetIterator = map.keySet().iterator(); while(keySetIterator.hasNext()){ Integer key = keySetIterator.next(); System.out.println("key: " + key + " value: " + map.get(key)); }




 }  
}
```

## OUTPUT:

![image](https://github.com/user-attachments/assets/e401038b-621f-4254-9bf6-ba9b84300527)


## RESULT:
Thus  a java program to retrieve the key and value from linkedhashmap for all input value was executed successfully.








