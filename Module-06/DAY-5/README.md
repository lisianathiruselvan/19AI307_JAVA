# Ex.No:6(E)  MULTIPLE INHERITANCE

## AIM:
To write a Java program using multiple inheritance through interfaces  for below Scenario Vehicle Class have constructor to Display "Vehicle class has 3 Child Class "Car Class constructor call its parent constructor and display "Car is the one of the Child of Vehicle Class" Truck Class constructor call its parent constructor and display "Truck is the one of the Child of Vehicle Class" Bus Class constructor call its parent constructor and display "Bus is the one of the Child of Vehicle Class" In Main class create object for Child class and access its corresponding Constructor
## ALGORITHM :

1.	Start the program.
2.	Define a base class Vehicle with a constructor that prints a message about its child classes.
3.	 Create three child classes (Car, Truck, Bus) that each extend Vehicle and define their own constructors printing specific messages.
4.	 In the main() method, create an object of Car, which triggers both Vehicle and Car constructors.
5.	 Create an object of Truck, triggering Vehicle and Truck constructors.
6.	 Create an object of Bus, triggering Vehicle and Bus constructors.
7.	End the program.


## PROGRAM:
 ```
/*
Program to implement a Multiple Inheritance
Developed by: LISIANA T
RegisterNumber:  212222240053
*/
```

## Sourcecode.java:
```
class Vehicle{
    Vehicle()
    {
        System.out.println("Vehicle class has 3 Child Class ");
    }
}

class Car extends Vehicle{
    Car()
    {
        System.out.println("Car is the one of the Child of Vehicle Class");
    }
}

class Truck extends Vehicle{
    Truck()
    {
        System.out.println("Truck is the one of the Child of Vehicle Class");
    }
}

class Bus extends Vehicle{
    Bus()
    {
        System.out.println("Bus is the one of the Child of Vehicle Class");
    }
}

public class Main{
    public static void main(String[] args){
        Car car=new Car();
        Truck truck=new Truck();
        Bus bus=new Bus();
    }
}
```


## OUTPUT:
![image](https://github.com/user-attachments/assets/b638faaa-89f7-42b6-b3e9-de5ce2a4a59f)



## RESULT:

Thus, the java program demonstrates multiple inheritance using interfaces for the given scenario has been successfully implemented.
