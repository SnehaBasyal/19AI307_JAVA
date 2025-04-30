# MOD2-DAY-3

## Ex.No:2(C) SINGLE ARRAY

## AIM:
To create a java program to read the length of an array, to store elements into the array and then display the array elements. 

## ALGORITHM :

1. Start the program.

2. Initialize a Scanner object to read input from the user.

3. Input the integer n from the user, which represents the number of elements in the array.

4. Declare an integer array arr of size n to store the elements.

5. Print the message "Elements in Array are :" to prompt the user.

6. Loop through the array arr from index 0 to n-1 (i.e., i = 0 to i < n):

7. Input an integer value from the user and store it at arr[i].

8. Print the element arr[i] followed by two spaces to display it.

9. End the program.

## PROGRAM:

Program to implement a Single Array using Java

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
        int n = sc.nextInt();
        int arr[] = new int[n];
        System.out.println("Elements in Array are :");
        for(int i=0;i<n;i++)
        {
            arr[i]=sc.nextInt();
            System.out.print(arr[i]+"  ");
            
        }
    }
}
```
## OUTPUT:
![image](https://github.com/user-attachments/assets/c2df2a79-c0ae-4eef-a990-792b7173bc4d)

## RESULT:
Thus, the Java program to read the length of an array, to store elements into the array and then display the array elements was executed successfully.
