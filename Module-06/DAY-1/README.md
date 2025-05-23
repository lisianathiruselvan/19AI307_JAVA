# Ex.No:6(A)  INNER CLASS
## AIM:
To create a Java Program to implement Method Local Inner Class.

## ALGORITHM :
1.Define the outer class Department with a member string variable.

2.Inside the display() method, define a local string variable.

3.Create a local inner class Inner inside the display() method.

4.Inside the Inner class, define a method print() that accesses both the outer class variable and the local method variable.

5.Instantiate the Inner class and call its print() method to display the values.

6.	End

## PROGRAM:
 ```
/*
Program to implement a Inner Class using Java
Developed by: LISIANA T
RegisterNumber: 212222240053 
*/
```

## Sourcecode.java:
```
public class Department {
    String str = "Financial and Management Department";

    void display() {
        String str1 = "ABC Industries";

        class Inner {
            void print() {
                System.out.println("Department is " + str);
                System.out.println("Company is " + str1);
            }
        }

        Inner inner = new Inner();
        inner.print();
    }

    public static void main(String[] args) {
        Department department = new Department(); 
        department.display(); 
    }
}
```


## OUTPUT:

![image](https://github.com/user-attachments/assets/c0fec8ce-dd9b-4b12-9da5-30b0baf6dbbd)


## RESULT:
Thus, the Java Program using Method Local Inner Class was executed successfully.

