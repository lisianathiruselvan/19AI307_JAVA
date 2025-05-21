# Ex.No:5(A)  DATA HIDING AND ENCAPSULATION
## AIM:
To Create a java program to display name and location of the employee and use the encapsulation concepts

## ALGORITHM :
1.  Start the program
2.	Define class `Employee`:
-	a) Declare two private `String` variables: `name1` and `name2`
-	b) Define `setname(String n1)` method to set `name1` to `n1`
-	c) Define `setname2(String n2)` method to set `name2` to `n2`
-	d) Define `get1()` method to return `name1`
-	e) Define `get2()` method to return `name2`
3.	Define `Main` class with `main` method:
-	a) Create `Scanner` object `sc` for input
-	b) Read `name1` and `name2` from user input
-	c) Create ` Employee ` object `hl`
-	d) Use `hl.setname(name1)` and `hl.setname2(name2)` to set the names
-	e) Print the values of `hl.get1()` and `hl.get2()`
4.	End


## PROGRAM:
 ```
/*
Program to implement a Data Hiding & Encapsulation using Java
Developed by: LISIANA T
RegisterNumber: 212222240053
*/
```

## Sourcecode.java:

```
import java.util.*;
class display
{
    private String name;
    private String location;
    
    public void set(String n, String l)
    {
        name = n;
        location = l;
        
    }
    public void get()
    {
        System.out.println(name);
        System.out.println(location);
    }
}
public class Main
{
    public static void main(String[] args)
    {
        Scanner sc=new Scanner(System.in);
        display obj = new display();
        obj.set(sc.next(),sc.next());
        obj.get();
        
    }
}
```
## OUTPUT:


![image](https://github.com/user-attachments/assets/0315ae88-af40-49b8-bf3e-83c31f9ff1e8)


## RESULT:
Thus , the  java program to display name and location of the employee and use the encapsulation concepts executed successfully.
