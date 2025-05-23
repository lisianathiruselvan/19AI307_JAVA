# Ex.No:6(B) MULTI-LEVEL INHERITANCE

## AIM:
To Develop a Java program to perform Multilevel Inheritance 

## ALGORITHM :
1.	Start the Program.

2.	Create an object of the Alto class.

3. Call display() method from the Vehicle class using the Alto object.

4. Call print() method from the Car class using the same object.

5. Call show() method from the Alto class.

6. Display output for each method to confirm multi-level inheritance.

7.End


## PROGRAM:
 ```
/*
Program to implement a MultiLevel Inheritance using Java
Developed by: LISIANA T
RegisterNumber: 212222240053 
*/
```

## Sourcecode.java:
```
class Vehicle {
    void display() {
        System.out.println("Vehicle Class");
    }
}

class Car extends Vehicle {
    void print() {
        System.out.println("Car Class");
    }
}

class Alto extends Car {
    void show() {
        System.out.println("Alto Class");
    }
}

public class Main {
    public static void main(String[] args) {
        Alto obj = new Alto();
        obj.display();
        obj.print();
        obj.show();
    }
}
```

## OUTPUT:

![IMAGE](https://github.com/lisianathiruselvan/19AI307_JAVA/blob/99435cfce6572a0a8b491156bb35771d6d3ce4bd/Module-06/DAY-2/image.png)

## RESULT:
Thus the java program for multi-level inheritance was executed successfully.





