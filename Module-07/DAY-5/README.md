# Ex.No:7(E)  POLYMORPHISM

## AIM:
To Write a Java Program for run time polymorphism by creating a class named Shape that contains a empty method named print Area().Provide two classes named Rectangle and triangle such that each one of the classes extends the class Shape. Each one of the classes contains only the method print Area () that prints the area of the given shape 
## ALGORITHM :
1.	Start the program.
2.	Define a base class Shape with an empty method printArea(int a, int b).
3.	Create Rectangle and Triangle classes that override printArea to compute and print their respective areas.
4.	Read two integers (a and b) from user input in the main() method.
5.	Instantiate Rectangle and Triangle objects but refer to them as Shape type (polymorphism).
6.	Call printArea(a, b) on both objects to display the calculated areas.
7.	End the program.



## PROGRAM:
 ```
/*
Program to implement a Method Overloading in Java
Developed by: LISIANA T
RegisterNumber: 212222240053 
*/
```

## Sourcecode.java:
```
import java.util.Scanner;

class Shape {
    void printArea(int a, int b) {}
}

class Rectangle extends Shape {
    void printArea(int a, int b) {
        System.out.println("Area of Rectangle:" + (a * b));
    }
}

class Triangle extends Shape {
    void printArea(int a, int b) {
        System.out.println("Area of Triangle:" + ((a * b) / 2));
    }
}

public class Main {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
        int a = sc.nextInt();
        int b = sc.nextInt();
        Shape rect = new Rectangle();
        Shape tri = new Triangle();
        rect.printArea(a, b);
        tri.printArea(a, b);
    }
}
```


## OUTPUT:
![image](https://github.com/user-attachments/assets/13a6e070-28ab-4d99-a265-026dc5dfadfb)



## RESULT:

Thus the  java program successfully  for run time polymorphism by creating a class named Shape that contains a empty method named print Area().Provide two classes named Rectangle and triangle such that each one of the classes extends the class Shape. Each one of the classes contains only the method print Area () that prints the area of the given shape 


