# Ex.No:4(A)  JAVA CONSTRUCTOR
## AIM:
To Write  a Java program using copy constructor to print the area of Circle

## ALGORITHM :

1.Start and define a Circle class with a radius variable and two constructors (one regular, one copy constructor).

2.Initialize the first circle object using the regular constructor with a given radius.

3.Create the second circle object using the copy constructor, passing the first circle.

4.Calculate the area of both circles using the area() method.

5.Display the area of the first and second circles on the console.





## PROGRAM:
 ```
/*
Program to implement a Constructor using Java
Developed by: LISIANA T
RegisterNumber: 212222240053 
*/
```

## Sourcecode.java:
```
class Circle 
 { 
          int r1;
         
         Circle(int radius) 
         {  
             r1 = radius;
         } 
        
         Circle(Circle obj) 
         { 
             this.r1 = obj.r1;
    
         } 
        
        double area() 
        { 
           return 3.14 * r1 * r1;
        } 
 } 
        //class to create Rectangle object and calculate area 
public class CopyConstructor 
 { 
           public static void main(String[] args) 
           { 
             Circle firstCir = new Circle(7); 
             Circle secondCir = new Circle(firstCir);
             System.out.println("Area  of First circle : "+firstCir.area());
             System.out.println("Area of Second Circle: "+secondCir.area());
             
             
           } 
 } 
 
```

## OUTPUT:

![image](https://github.com/user-attachments/assets/e04fb6db-ef4e-4bdb-b9ae-0ce0207d69db)



## RESULT:
Thus the Java program  using copy constructor to print the area of Circle was executed successfully.
