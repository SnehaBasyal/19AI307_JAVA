## Ex.No:1(E) Multiplication of two number using method

## AIM:
To write a Java program for Multiplication of two number using method

## ALGORITHM :
1. Start

2. Define the class Multiplication.

3. Create a static method multiply that:
   
      a) Takes two integers num1 and num2 as input.

      b) Returns the product of num1 and num2.

5. In the main method:
   
      a) Create a Scanner object to read input.

      b) Read integer num1 from the user.

      c) Read integer num2 from the user.

      d) Call the multiply method with num1 and num2, store the result.

      e) Print the result with the message "multiplication is: ".

7. End

## PROGRAM:

Developed by: Sneha Basyal M 

RegisterNumber: 212222240101

## Sourcecode.java:
```
import java.util.Scanner;
public class Multiplication {
     
    public static int multiply(int num1, int num2)
    {
         return num1 * num2;
    }
    
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
        int num1 = scanner.nextInt(); 
        int num2 = scanner.nextInt();
        int result = multiply(num1, num2);
        System.out.println("multiplication is: " + result);
        scanner.close();
    }
}
```
## OUTPUT:

![image](https://github.com/user-attachments/assets/ae9bb423-aa4c-4918-98a6-387f310a8ffb)

## RESULT:
Thus, the Java program to read two integers from the user, multiply them using a user-defined method, and display the result is created and executed successfully.
