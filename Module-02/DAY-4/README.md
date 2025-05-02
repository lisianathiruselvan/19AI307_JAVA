# Ex.No:2(D) MULTI-DIMENSIONAL ARRAY

## AIM:
To Develop a Java Program to read and print two dimensional array (Matrix).
## ALGORITHM :
1.Start

2.Create a Scanner object for input

3.Read number of rows from the user

4.Read number of cols from the user

5.Declare a 2D array matrix with size [rows][cols]

6.For i from 0 to rows - 1:

7.For j from 0 to cols - 1:

8.Read an integer from the user

9.Store it in matrix[i][j]

10.Print "The Array is:"

11.For i from 0 to rows - 1:

12.For j from 0 to cols - 1:

13.Print matrix[i][j] followed by space

14.Move to the next line after each row

15.Close the Scanner

16.End


## PROGRAM:
 ```
/*
Program to implement a Multi Dimensional Array using Java
Developed by: LISIANA T
RegisterNumber: 212222240053
*/
```

## Sourcecode.java:
```
import java.util.Scanner;

public class MatrixInputOutput {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);

        int rows = scanner.nextInt();
        int cols = scanner.nextInt();
        
        int[][] matrix = new int[rows][cols];

        for (int i = 0; i < rows; i++) {
            for (int j = 0; j < cols; j++) {
                matrix[i][j] = scanner.nextInt();
            }
        }

        System.out.println("The Array is :");
        for (int i = 0; i < rows; i++) {
            for (int j = 0; j < cols; j++) {
                System.out.print(matrix[i][j] + "  ");
            }
            System.out.println();
        }

        scanner.close();
    }
}
```

## OUTPUT:

![image](https://github.com/user-attachments/assets/d338b173-ab2c-4f99-9e4f-9fc104a4897d)


## RESULT:
Thus a Java Program to read and print two dimensional array (Matrix) was executed successfully.


