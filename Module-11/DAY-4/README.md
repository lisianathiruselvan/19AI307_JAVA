# Ex.No:11(D) RELATED TO MAP CONCEPTS

## AIM:
To Create a java program to display the name with key  using map interface like key , value pair.

## ALGORITHM :

1.	Start
2.	Create a HashMap to store integer keys and string values.
3.	Read the number of entries and input each integer-string pair into the map.
4.	Use a for-each loop to iterate over the map's entries.
5.	For each entry, retrieve and print the key and corresponding value.
6.	End the program after printing all the map entries.
7.	End




## PROGRAM:
 ```
/*
Program to implement a RELATED TO MAP CONCEPTS using Java
Developed by: LISIANA T
RegisterNumber: 212222240053 
*/
```

## Sourcecode.java:
```
import java.util.*;  
public class Mapp{  
 public static void main(String args[]){ 
     
  Map<Integer,String> map=new HashMap<Integer,String>(); 
  Scanner sc=new Scanner(System.in);
  
  int size=sc.nextInt();
  for(int i=0;i<size;i++)
  {
  Integer a=sc.nextInt();
  String b=sc.next();
  map.put(a,b);  
  } 
 
  for(Map.Entry m:map.entrySet()){  
   System.out.println(m.getKey()+" "+m.getValue());  
  }  
 }  
}
```


## OUTPUT:

![image](https://github.com/user-attachments/assets/ccfe1d8b-a399-464f-b80b-de35cb187fce)


## RESULT:
Thus  a java program to display the name with key  using map interface like key , value pair. executed and verified successfully.


