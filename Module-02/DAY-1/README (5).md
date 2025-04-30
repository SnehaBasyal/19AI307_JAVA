## MOD2-DAY-1
## Ex.No:2(A) STATIC METHOD
## AIM:
To create a java program for calculate cube of a number using static method.

## ALGORITHM :
1. Start : Begin the process of calculating the cube of a number.
2. Declare a variable to store input : Declare an integer variable n to hold the number whose cube will be calculated.
3. Create a Scanner object : Create a Scanner object (sc) to read the input from the user.
4. Read input from the user : Prompt the user to input an integer value. The input value is stored in the variable n.
5. Call the cubecal function : Call the function cubecal(n) which computes the cube of the number by performing n * n * n.
6. Store the result : Store the result of the cubecal function in an integer variable result.
7. Output the result : Print the cube of the number using System.out.println("Cube is: " + result);.
. End the program.

## PROGRAM:
Program to implement a Static method using Java

Developed by: Sneha Basyal M

RegisterNumber: 212222240101

## Sourcecode.java:
```
import java.util.Scanner;
public class Main
{
    public static void main(String[] args)
    {
        Scanner sc = new Scanner(System.in);
        int num = sc.nextInt();
        cube(num);
        
    }
    static void cube(int num)
    {
        int result = num * num * num;
        System.out.print("Cube is: "+result);
    }
}
```

## OUTPUT:
![image](https://github.com/user-attachments/assets/11ca7bd5-357d-4a70-93e8-61d2a4eb23b1)


## RESULT:
Thus the java program for calculate cube of a number using static method has been executed successfully.
