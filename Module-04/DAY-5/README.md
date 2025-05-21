# Ex.No:4(E)  PARAMETERIZED CONSTRUCTOR
## AIM:
To Create a class Box that uses a parameterized constructor to initialize the dimensions of the box. The dimensions of the Box are width, height, depth.[5,4,3]

## ALGORITHM :

1. Define a Box class with height, width, and depth as instance variables.

2. Create a constructor to initialize these variables using the this keyword.

3. Define a volume() method to compute and print the volume (h × w × d).

4. In main(), create a Box object with specific dimensions.

5. Call the volume() method to display the calculated volume.


## PROGRAM:
 ```
/*
Program to implement a Parameterized Constructor Using Java
Developed by: LISIANA T
RegisterNumber: 212222240053 
*/
```

## Sourcecode.java:

```
public class Box
{
    int h;
    int w;
    int d;

    Box(int h,int w,int d)
    {
         this.h = h;
         this.w = w;
         this.d = d;

    }
    void volume()
    {
           System.out.println("Volume is "+this.h*this.w*this.d+" units");

    }


public static void main(String[] args)
{
   Box b = new Box(5,4,3);
   b.volume();
}
}


```


## OUTPUT:


![image](https://github.com/user-attachments/assets/e8dfab8b-d1b5-4c5a-96f4-7e818c672737)



## RESULT:
Thus, the  java program was successfully demonstrates the use of a parameterized constructor to initialize class box.

 


