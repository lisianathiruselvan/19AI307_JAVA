# Ex.No:2(A)  STATIC METHOD

## AIM:
To Determine if the number is a multiple of 10 using staticmethod 

## ALGORITHM :
1. Start the program.
2. Read an integer input from the user.
3. Check if the number is divisible by 10 using the modulus operator.
4. If divisible, print "number is a multiple of 10."
5. Else, print "number is not a multiple of 10."
6. End the program.

## PROGRAM:
 ```
/*
Program to implement a Static method using Java
Developed by: LISIANA T
RegisterNumber: 212222240053 
*/
```

## Sourcecode.java:

```
import java.util.Scanner;

public class MultipleCheck {
    static boolean isMultipleOfTen(int num) {
        return num % 10 == 0;
    }
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
        int num = sc.nextInt();
        if (isMultipleOfTen(num)) {
            System.out.println(num + " is a multiple of 10.");
        } else {
            System.out.println(num + " is not a multiple of 10.");
        }
    }
}
```

## OUTPUT:

![image](https://github.com/user-attachments/assets/0e359754-fe37-4d95-8947-720d90ddccbe)


## RESULT:
Thus the java program To Determine if the number is a multiple of 10 using static method has been executed successfully.

