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
2.	Create an object of the PhysicsTeacher class.
3. Call the printTitle() method inherited from the Beginnersbook class to print the title.
4. Call the printRole() method inherited from the Teacher class to print the role.
5. Call the printSubject() method of the PhysicsTeacher class to print the subject.
6. Call the printSkill() method of the PhysicsTeacher class to print the skill.
7.	End the program.

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

