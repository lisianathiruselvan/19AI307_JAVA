# Ex.No:4(D) FINAL & STATIC IN JAVA

## AIM:
   To create a Java program to Create a final class 'Company' with Company Name,Company Id and Address as its member, make Company_Id as final variable with value "ED12G45" and write print() to display its member in the Output.
 
## ALGORITHM :
1.	Define a final class Company with three final attributes: id, name, and city.

2. Create a display() method in Company to print the company details.

3. In the main() method, create an object of the Company class.

4. Call the display() method using the object.

5. Print the company's ID, name, and city to the console.


## PROGRAM:
 ```
/*
Program to implement a final & Static using Java
Developed by: LISIANA T
RegisterNumber:  212222240053
*/
```

## Sourcecode.java:
```
final class Company{
    final String id="ED12G45";
    final String name="ABC Foods";
    final String city="Chennai";
    
    void display(){
        System.out.println("Company Details are,\nId is "+id+"\nName is "+name+"\nAddress is "+city);
    }
}
public class demo{
    public static void main(String[] args){
        Company cp=new Company();
        cp.display();
    }
}

```


## OUTPUT:

![image](https://github.com/user-attachments/assets/506e65c7-5f3a-40b8-b7f5-c7a70ca0dd1c)


## RESULT:
Thus, the java program to perform final  keyword was executed successfully.
