# Ex.No:5(E) IS-A RELATIONSHIP
## AIM:
To Write a java program to print the given input using is-a relationship.
Sample Input:
Beginnersbook
Teacher
Physics
Teaching
## ALGORITHM :
1.	Start the program.
2.	Create a class ArrayData:
a.	Declare an integer array and a variable for size.
b.	Create a method to read array elements from the user.
3.	Create another class ArrayOperation:
a.	Create a method findMax() that accepts an ArrayData object.
b.	Loop through the array and find the largest element.
4.	In the main() method of a class Main:
a.	Create an object of ArrayData and read the input.
b.	Create an object of ArrayOperation and call findMax() by passing the ArrayData object.
5.	Display the largest number.
6.	End the program.



## PROGRAM:
 ```
/*
Program to implement a HAS-A RelationShip
Developed by: LISIANA T
RegisterNumber: 212222240053 
*/
```

## Sourcecode.java:
```
class Beginnersbook {
    void printTitle() {
        System.out.println("Beginnersbook");
    }
}

class Teacher extends Beginnersbook {
    void printRole() {
        System.out.println("Teacher");
    }
}

class PhysicsTeacher extends Teacher {
    void printSubject() {
        System.out.println("Physics");
    }

    void printSkill() {
        System.out.println("Teaching");
    }
}

public class Main {
    public static void main(String[] args) {
        PhysicsTeacher obj = new PhysicsTeacher();
        
        obj.printTitle();
        obj.printRole();
        obj.printSubject();
        obj.printSkill();
    }
}
     
```


## OUTPUT:

![image](https://github.com/user-attachments/assets/95f3a3df-c7a8-415f-bdb5-02b2bc378d75)


## RESULT:
Thus the java program to Write a java program to print the given input using is-a relationship has been implemented successfully

