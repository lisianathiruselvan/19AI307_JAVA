# Ex.No:4(C)    CONSTRUCTOR CHAINING(SUPER KEYWORD)

## AIM:
To Create a Java program to implement super keyword in constructor.

## ALGORITHM :
1. Define a College class with a constructor that prints the college name.

2. Create a Department class that extends College and prints the department name in its constructor using super().

3. Define a Student class that extends Department and prints a student message in its constructor using super().

4. In the main() method, create a Student object.

5. Execute constructors in the inheritance chain (College → Department → Student) and print their messages.

6.	End


## PROGRAM:
 ```
/*
Program to implement a Constructor Chaining using Java
Developed by: LISIANA T
RegisterNumber: 212222240053 
*/
```

## Sourcecode.java:
```
class College {
    College() {
        System.out.println("Saveetha Engineeirng College");
    }
}

class Department extends College {
    Department() {
        super();
        System.out.println("CSE Department");
    }
}

class Student extends Department {
    Student() {
        super();
        System.out.println("I am a Student of CSE dept");
    }
}

public class Main {
    public static void main(String[] args) {
        Student student = new Student();
    }
}

```

## OUTPUT:

![image](https://github.com/user-attachments/assets/ff23d15b-043d-4eaf-a050-7f1d000d0e8d)


## RESULT:
Thus the java program for constructor chaining was executed successfully.




