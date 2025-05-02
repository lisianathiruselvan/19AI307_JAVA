# Ex.No:2(A)  STATIC METHOD

## AIM:
To create a java program for Reverse a Number Using static function

## ALGORITHM :
1.Start

2.Define a method reverse(int num)

3.Initialize revnum = 0

4.Repeat while num is not equal to 0:

5.Extract the last digit using digit = num % 10

6.Update revnum = revnum * 10 + digit

7.Remove the last digit from num using num = num / 10

8.Return revnum

9.In the main method:

10.Create a Scanner object to read input.

11.Read an integer from the user and store in num.

12.Call reverse(num) and store result in revnumber.

13.Print "Reversed number: " followed by revnumber.

14.End


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
import java.util.*;
public class Main{
    static int reverse(int num){
        int revnum=0;
        while(num!=0){
            int digit=num%10;
            revnum =revnum*10+digit;
            num=num/10;
        }
        return revnum;
    }
    public static void main(String[] args){
        Scanner sc=new Scanner(System.in);
        int num=sc.nextInt();
        int revnumber=reverse(num);
        System.out.println("Reversed number: "+revnumber);
    }
}
```





## OUTPUT:
![image](https://github.com/user-attachments/assets/9657e80e-c264-4b2b-abd1-c8bf1b86f284)



## RESULT:
Thus the java program for Reverse a Number Using static function has been executed successfully.

