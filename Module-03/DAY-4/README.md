# Ex.No:3(D) STRING TOKENIZER IN JAVA

## AIM:
To create a java program to calculate the number of tokens present in the tokenizer string.

## ALGORITHM :
1. Start the program.

2. Read a line of input from the user.

3. Create a StringTokenizer object to split the input string using space (" ") as the delimiter.

4. Count the number of tokens (words) using countTokens().

5. Display the total number of tokens.

6. End the program.

## PROGRAM:
Program to implement a String Tokenizer using Java

Developed by: Sneha Basyal M

RegisterNumber: 212222240101 


## Sourcecode.java:
```
import java.util.*;    
public class Main 
{    
 
  public static void main(String args[])  
  {    
     Scanner sc=new Scanner(System.in);
     String str1=sc.nextLine();
     StringTokenizer st = new StringTokenizer(str1," ");    
     System.out.println("Total number of Tokens: "+st.countTokens());
   }    
}
```

## OUTPUT:
![image](https://github.com/user-attachments/assets/40ff7fbd-94fd-4b3b-8252-e37a7a618b19)



## RESULT:
Thus the java program to calculate the number of tokens present in the tokenizer string was executed successfully.
