# Ex.No:6(C)             HIERARCHICAL INHERITANCE 

## AIM:
  To Develop a Java program to perform Hierarchical Inheritance for below scenario Animal Class have constructor to display "Animal is the Base Class"2. Dog Class constructor call its parent constructor and display "Dog is the Derived Class of Animal"3. Cat Class constructor call its parent constructor and display "Cat is the Derived Class of Animal"4. In Main class create object for Child class and access its corresponding Constructor

## ALGORITHM :
1.  Start the Program
   
2.  Define a base class Animal with a constructor that prints a message.

3. Define two derived classes Dog and Cat, each calling super() to invoke the Animal constructor and then printing their own messages.

4. In the main() method, create an object of the Dog class → invokes Animal and Dog constructors.

5. Create an object of the Cat class → invokes Animal and Cat constructors.

6. Output confirms the order of constructor calls in the inheritance hierarchy.

7.	End




## PROGRAM:
 ```
/*
Program to implement a Hierarchical Inheritance using Java
Developed by: LISIANA T 
RegisterNumber: 212222240053 
*/
```

## Sourcecode.java:
```
class Animal {
    Animal() {
        System.out.println("Animal is the Base Class");
    }
}

class Dog extends Animal {
    Dog() {
        super();
        System.out.println("Dog is the Derived Class of Animal");
    }
}

class Cat extends Animal {
    Cat() {
        super();
        System.out.println("Cat is the Derived Class of Animal");
    }
}

public class Main {
    public static void main(String[] args) {
        Dog obj1 = new Dog();
        Cat obj2 = new Cat();
    }
}
```

## OUTPUT:

![image](https://github.com/user-attachments/assets/0e1e73f8-303f-491c-af59-9ac53d98e2b1)


## RESULT:
Thus the java program for Hierarchical inheritance was executed successfully.






