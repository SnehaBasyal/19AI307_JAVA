## Ex.No:1(B) VARIABLES AND OPERATOR

## AIM:
To write a Java program to get values of variables 'a' and 'b'  and then check if both the conditions 'a < 50' and 'a < b' and b>60 are true. [Class name is ‘Demo’]

## ALGORITHM :
1. Start
2. Import the Scanner class for input.
3. Define the class Demo.
4. Inside the main method:
   - Create a Scanner object sc to read input.
   - Read an integer a from the user.
   - Read an integer b from the user.
   - Check if:
     - a < 50
     - a < b
     - b > 60
   - If all conditions are true:
     - Print "true"
   - Else:
     - Print "false"
5. End
   
## PROGRAM:

Program to implement a variable and operators using Java

Developed by: Sneha Basyal M

RegisterNumber: 212222240101


## Sourcecode.java:

```
import java.util.Scanner;
public class Demo
{
    public static void main(String[] args)
    {
        Scanner sc = new Scanner(System.in);
        int a = sc.nextInt();
        int b = sc.nextInt();
        if (a<50 && a<b && b>60)
        {
            System.out.println("true");
        }
        else
        {
            System.out.println("false");
        }
    }
}
```

## OUTPUT:
![image](https://github.com/user-attachments/assets/1106946e-a611-46d0-8fb6-426833dd0035)


## RESULT: 
Thus, the Java program to get the values of variables 'a' and 'b' from the user and then check if the conditions a < 50, a < b, and b > 60 are true is created and executed successfully. The appropriate message (true or false) is displayed based on the condition evaluation.
