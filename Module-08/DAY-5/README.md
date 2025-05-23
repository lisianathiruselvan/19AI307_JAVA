# Ex.No:8(E)  INPUT STREAM READER.

## AIM:
To Write a Java Program for Reading data from console by InputStreamReader and BufferedReader
## ALGORITHM :
1. Start the program and prepare to take input from the user.
2. Create a BufferedReader to read input from the console.
3. Read a line of text entered by the user and store it.
4. Display a welcome message including the user's input.
5. End the program.


## PROGRAM:
 ```
/*
Program to implement a INPUT STREAM READER
Developed by: LISIANA T
RegisterNumber: 212222240053 
*/
```

## Sourcecode.java:
```
import java.io.BufferedReader;
import java.io.IOException;
import java.io.InputStreamReader;
public class Test {
	public static void main(String[] args)
		throws IOException
	{
		BufferedReader reader = new BufferedReader(
			new InputStreamReader(System.in));

		String name = reader.readLine();

		System.out.println("Welcome: "+name);
	}
}
```


## OUTPUT:

![image](https://github.com/user-attachments/assets/bff2cb61-78d4-4cc6-8de0-07d07889d47c)


## RESULT:
Thus,a Java Program for Reading data from console by InputStreamReader and BufferedReader has been executed successfully

