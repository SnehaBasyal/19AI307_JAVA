# Ex.No:9(C)             STRING READER
## AIM:
 To Create a Java Program to display the string content after skipping 4 characters using the predefined Method Skip in StringReader

## ALGORITHM :
1. Start
2. Read a string from user input
3. Create `StringReader` using the input string
4. Print original data
5. Skip first 4 characters using `skip(4)`
6. Print message: "Data after skipping"
7. Read and print remaining characters using a loop
8. End

## PROGRAM:

Program to implement a String Reader using Java

Developed by: Sneha Basyal M

RegisterNumber: 212222240101  


## Sourcecode.java:
```
import java.io.StringReader;  
import java.util.*;
public class StringReaderExample 
{  
    public static void main(String[] args) throws Exception 
    {  
        Scanner sc = new Scanner(System.in);
        String str = sc.nextLine();
        
        StringReader sr = new StringReader(str);
        
        System.out.println("Original data: "+str);
        
        sr.skip(4);
        
        System.out.println("Data after skipping");
        
        int k;
        while((k=sr.read())!=-1)
        {
            System.out.print((char)k);
        }
    }  
}
```

## OUTPUT:
![image](https://github.com/user-attachments/assets/6f4402b1-07a0-4f81-81d4-228943ed5b61)



## RESULT:
Thus the Java Program to display and skip the specified number of characters using the predefined Method Skip in StringReader was executed and verified successfully.











