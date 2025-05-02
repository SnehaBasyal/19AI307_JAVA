# Ex.No:3(E)  STRINGBUILDER 

## AIM:
To write a Java program to Read input ,split word from sentence and use string builder.

## ALGORITHM :
1. Start the program.

2. Read a line of input from the user.

3. Convert the input string to a StringBuilder and back to a string (str1).

4. Split str1 into words using space as the delimiter (split("\\s")).

5. For each word, print it on a new line.

6. End the program.


## PROGRAM:

Program to implement a StringBuilder in Java

Developed by: Sneha Basyal M

RegisterNumber: 212222240101 


## Sourcecode.java:
```
import java.util.Scanner;
public class Main
{
    public static void main(String[] args)
    {
        Scanner sc=new Scanner(System.in);
        String str=sc.nextLine();
        StringBuilder sb=new StringBuilder(str);
        String str1=sb.toString();
        String[] words=str1.split("\\s");
        for(String w:words)
        {
            System.out.println(w);
        }
    }
}
```

## OUTPUT:
![image](https://github.com/user-attachments/assets/70f5036d-da4e-4134-970d-61152227ec53)


## RESULT:
Thus the Java program to read input , split word from sentence and use string builder was executed successfully.

