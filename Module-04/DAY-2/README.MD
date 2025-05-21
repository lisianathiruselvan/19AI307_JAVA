# Ex.No:4(B) INTRODUCTION TO JAVA INHERITANCE

## AIM:
To create  a Java program to perform the inheritance concept for student details.

## ALGORITHM :
1. Start by defining a Course class with attributes for degree, branch, and year, and a method to display them.

2. Define a Student class that has a student ID and a Course object, with a method to display student details and their course.

3. In main, create a Course object with specific values.

4. Create a Student object, passing the student ID and the course object.

5. Display the student's ID and course details using the disp() method.

## PROGRAM:
 ```
/*
Program to implement a Inheritance using Java
Developed by: LISIANA T
RegisterNumber: 212222240053 
*/
```

## Sourcecode.java:
```
class Course {
    String degree;
    String branch;
    String year;

    Course(String degree, String branch, String year) {
        this.degree = degree;
        this.branch = branch;
        this.year = year;
    }

    void dispCourse() {
        System.out.println(degree + " " + branch + " " + year + " year");
    }
}

class Student {
    int stuId;
    Course course;

    Student(int stuId, Course course) {
        this.stuId = stuId;
        this.course = course;
    }

    void disp() {
        System.out.println(stuId);
        course.dispCourse();
    }
}

public class Main {
    public static void main(String[] args) {
        Course c = new Course("B.Tech", "IT", "Third");
        Student s = new Student(101, c);
        s.disp();
    }
}

```





## OUTPUT:
![image](https://github.com/lisianathiruselvan/19AI307_JAVA/blob/a67b99982aa5c437bad96c040bf637f55d35f606/Module-04/DAY-2/Screenshot%202025-05-21%20203455.png)


## RESULT:
Thus the Java program to implement the inheritance concept for student details was  executed successfully.

