# Ex.No:7(B) EXCEPTION HANDLING-FINALLY
## AIM:
To Write a Java program to demonstrate control flow of try-catch-finally clause when ArrayIndexOutOfBoundsException occur in try block and handled in catch block


## ALGORITHM :

1. Start
2. Declare an integer array `arr` with size 4
3. Begin `try` block
4. Attempt to access `arr[4]` (invalid index)
5. Exception is thrown
6. Catch the exception in `catch(ArrayIndexOutOfBoundsException)`
7. Print catch block message
8. Execute `finally` block
9. Print message outside try-catch-finally
10. End


## PROGRAM:

Program to implement a Exception Handling-Finally using Java

Developed by: Sneha Basyal M

RegisterNumber: 212222240101


## Sourcecode.java:
```
import java.util.*;
public class HelloWorld {
    public static void main(String[] args) 
    {
     
        int[] arr = new int[4];
         
        try
        {
            int i = arr[4];
                 
           
            System.out.println("Inside try block");
        }
         
        catch(ArrayIndexOutOfBoundsException ex)
        {
            System.out.println("Exception caught in catch block");
        }
         
        finally
        {
            System.out.println("finally block executed");
        }
         
 
        System.out.println("Outside try-catch-finally clause");
    }
}
```

## OUTPUT:



## RESULT:
Thus the Java program to demonstrate control flow of try-catch-finally clause when ArrayIndexOutOfBoundsException occur in try block and handled in catch block was executed successfully.



