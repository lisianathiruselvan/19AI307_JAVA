# Ex.No:6(D) PACKAGES
## AIM:
  To create a Java Program for accessing package from another package using packagename.
 
## ALGORITHM :
1.	Start the Program
2.	Create a directory named pack and save A.java inside it.
2.	Compile A.java from the parent directory using javac pack/A.java.
3.	Create another directory named mypack and save B.java inside it.
4.	Compile B.java from the parent directory using javac mypack/B.java.
5.	Run B from the parent directory with java mypack.B


## PROGRAM:
 ```
/*
Program to implement a Packages using Java
Developed by: LISIANA T
RegisterNumber: 212222240053
*/
```

## Sourcecode.java:
```
package package1;

public class Message {
    public void show() {
        System.out.println("Accessing class from another package!");
    }
}

package package2;

// Importing the class from another package
import package1.Message;

public class Main {
    public static void main(String[] args) {
        Message msg = new Message();
        msg.show();
    }
}
```


## OUTPUT:

Acessing class from another package!

## RESULT:
Thus, the program has accessed the package from another package has been done successfully.

