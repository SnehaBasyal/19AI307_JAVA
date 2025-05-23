# Ex.No:7(E)  User Defined Exception using throw concept

## AIM:
To Write a java program to perform user defined exception using throw concept.

## ALGORITHM :

1. Start
2. Read age input from user
3. Call `validate(age)` method
4. Inside `validate()`, check if `age < 18`
5. If true, throw `ArithmeticException`
6. Catch and print exception
7. Else, print eligible message
8. End


## PROGRAM:

Program to perform user defined exception using throw concept.

Developed by: Sneha Basyal M

RegisterNumber: 212222240101 


## Sourcecode.java:
```
import java.util.Scanner;

public class HelloWorld 
{
             
        public static void validate(int age)  
        {
            try
            {
                if(age<18)
                {
                    throw new ArithmeticException("Person is not eligible to vote");
                }
                else
                {
                    System.out.println("Person is eligible to vote!!");
                }
                
            }
               catch(Exception e)
               {
                   System.out.println(e);
                   
               }       
           
        }  
          
        public static void main(String args[])
        {
            Scanner sc = new Scanner(System.in);
            int n = sc.nextInt();
            validate(n);
        }
}
```       

## OUTPUT:
![image](https://github.com/user-attachments/assets/db1aae00-b5e7-4932-aa75-551b3c932551)



## RESULT:

Thus the  java program to perform user defined exception using throw concept was successfully executed.


