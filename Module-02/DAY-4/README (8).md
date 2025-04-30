# MOD2-DAY-4

## Ex.No:2(D) MULTI-DIMENSIONAL ARRAY

## AIM:
To create a java Program to find the sum of all the elements present in a 2-D array.

## ALGORITHM :
1. Start the program.

2. Define a method sum that takes a 2D array arr as a parameter.

3. Initialize a variable sum to store the total sum, set its initial value to 0.

4. Loop through each row of the 2D array (arr):

5. For each row, loop through each element in the row.

6. Add the current element arr[i][j] to sum.

7. After completing the loops, print the sum of all elements in the array.

8. In the main method:
   Declare and initialize a 2D array arr with predefined values.

   Call the sum method and pass the array arr as an argument.

9. End the program.

## PROGRAM:

Program to implement a Multi Dimensional Array using Java

Developed by: Sneha Basyal M

RegisterNumber: 212222240101

## Sourcecode.java:
```
public class Main
{
    static void sum(int[][] arr)
    {
        int sum=0;
        for(int i=0;i<arr.length;i++)
        {
            for(int j=0;j<arr[0].length;j++)
            {
                sum = sum + arr[i][j];
            }
            
        }
        System.out.println("Sum of all elements is: "+sum);
    }
    public static void main(String[] args)
    {
        int[][] arr = {
            {1, 2, 3, 4, 5},
            {2, 4, 6, 8, 10},
            {1, 3, 5, 7, 9}
        };
        sum(arr);
    }
}
```
## OUTPUT:
![image](https://github.com/user-attachments/assets/26da3b39-7e5e-4872-aabf-63d9e54fb32d)

## RESULT:
Thus the java program that returns the sum of all the elements present in a 2-D array was executed successfully.
