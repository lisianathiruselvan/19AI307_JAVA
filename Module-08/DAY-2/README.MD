# Ex.No:8(B) IO-FILE READER/WRITER
## AIM:
To Implement a Java Program to append a String in a file "testout.txt" using Writer

## ALGORITHM :
1.	It creates a file testout.txt, writes "Welcome to Java File Concept -Reader" to it, and displays this initial content.
2.	It reopens the file in append mode and adds "1234567890" at the end of the existing content.
3.	It reads the file's content (Welcome to Java File Concept -Reader1234567890) and displays it.
4.	The file is deleted using file.delete().
5.	It tries to read the file again, but this throws an exception since the file no longer exists.




## PROGRAM:
 ```
/*
Program to implement a IO File Reader/Writer using Java
Developed by: 
RegisterNumber:  
*/
```

## Sourcecode.java:
```
 
             try
             {
                {{
                    String str="Hi Everybody";
                    Writer s=new FileWriter("testout.txt",true);
                    s.append(str);
                    s.close();
                    System.out.println("Append the character in the File Successfully");
                }}

               
  
                }
                catch(Exception e){System.out.println(e);}
```





## OUTPUT:



## RESULT:
Thus, the java program to append a String in a file "testout.txt" using Writerwas executed and verified successfully



