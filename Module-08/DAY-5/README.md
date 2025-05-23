# Ex.No:8(E) BUFFERED READER.

## AIM:
To write a Java Program for getting integer input from the User using BufferedReader

## ALGORITHM :

1. Start
2. Create `BufferedReader` to read input from `System.in`
3. Read a line and convert it to integer using `Integer.parseInt()`
4. Print the entered integer
5. End

## PROGRAM:

Program to implement a BUFFEREDREADER

Developed by: Sneha Basyal M

RegisterNumber: 212222240101 


## Sourcecode.java:
```
import java.io.*;

public class Sample
	
{
    public static void main(String [] args) throws IOException
    {
        BufferedReader bfn = new BufferedReader(new InputStreamReader(System.in));
 
		int it = Integer.parseInt(bfn.readLine());
					
		System.out.println("Entered Integer : "+ it);
		
	}
					
}
```
## OUTPUT:
![image](https://github.com/user-attachments/assets/9c750c52-059b-4490-90f6-f0278b654cd0)



## RESULT:
Thus, the java program for getting integer input from the User using BufferedReader is successfully executed.

