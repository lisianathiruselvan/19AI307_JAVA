# Ex.No:9(D) TRANSIENT ---SERILIZATION

## AIM:
 To implement a Java program to perform Transient in Employee details in Serializable interface to make its object serialized.

## ALGORITHM :
1.	Get employee name and designation from the user.
2.	Save the Employeeinfo object to emp.txt.
3.	Read the object back from emp.txt.
4.	Print employee name and designation (designation is null due to transient).
5.	Delete File: Delete emp.txt and handle any exceptions while trying to read it.




## PROGRAM:
 ```
/*
Program to implement a Transient using Java
Developed by: LISIANA T
RegisterNumber: 212222240053 
*/
```

## Sourcecode.java:
```
 class Employeeinfo implements Serializable
{
    String name;
    transient String desi;
   
    Employeeinfo(String n, String r)
    {
    this.name = n;
    this.desi = r;
   
    }
}
```






## OUTPUT:

![image](https://github.com/user-attachments/assets/ec785570-2354-4a3d-b508-5f9aac5115b9)


## RESULT:
Thus, implementation of a Java program to perform Transient in Employee details in Serializable interface to make its object serialized was executed and verified successfully.

