# Ex.No:8(B) IO-FILE READER/WRITER
## AIM:
To Implement a Java Program to append a String in a file "testout.txt" using Writer

## ALGORITHM :
1.	FileWriter("testout.txt", true) opens the file in append mode.

2. s.append(str) adds the string at the end of the file.

3. s.close() closes the file resource.

4. try-catch block handles any possible exceptions.



## PROGRAM:
 ```
/*
Program to implement a IO File Reader/Writer using Java
Developed by: LISIANA T
RegisterNumber: 212222240053 
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
![image](https://github.com/lisianathiruselvan/19AI307_JAVA/blob/109a6544989d62a8a3e19383685ecb766368172b/Module-08/DAY-2/image.png)

## RESULT:
Thus, the java program to append a String in a file "testout.txt" using Writerwas executed and verified successfully



