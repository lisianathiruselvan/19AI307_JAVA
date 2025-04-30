# Ex.No:1(A) CLASS & OBJECTS

## AIM:
To Write a main() for the class named 'Test' to access class 'date' and display in-date of an employee(Time be in format Day:month:year).get the input from user

## ALGORITHM :
1.	Start the program.

2.Create a Clock class with three integer variables: hours, mins, and sec.

3. In the main method, create a Scanner object to read user input.

4. Create an object of the Clock class.

5. Read three integers from the user and assign them to hours, mins, and sec.
   
6. Display the time in the format hours/mins/sec.
   
7.	End



## PROGRAM:
 ```
/*
Program to implement a class & objects using Java
Developed by: LISIANA T
RegisterNumber:  212222240053
*/

```

## Sourcecode.java:
```
class Clock

{

int hours, mins, sec;

}
public class Test{
    public static void main(String[] args)
    {//Write your code here
     Scanner kbd=new Scanner(System.in);
     Clock obj=new Clock();
     obj.hours=kbd.nextInt();
     obj.mins=kbd.nextInt();
     obj.sec=kbd.nextInt();
     System.out.printf("%d/%d/%d",obj.hours,obj.mins,obj.sec);
    }
}

```
## OUTPUT:
![image](https://github.com/user-attachments/assets/48d05dd0-96cb-4003-8a86-e0d8ae527a23)



## RESULT:
Thus,  a main() for the class named 'Test' to access class 'date' and display in-date of an employee(Time be in format Day:month:year).get the input from user' was created successfully.
