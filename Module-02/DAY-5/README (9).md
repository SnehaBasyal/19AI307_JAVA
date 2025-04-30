## MOD2-DAY-5

## Ex.No:2(E) SORT THE ELEMENTS OF AN ARRAY
## AIM:
To write a Java program to sort the elements of an array in ascending order.

## ALGORITHM :
1. Start the program.

2. Input an integer n (size of the array).

3. Declare an integer array arr of size n.

4. Input the n elements into the array using a loop.

5. Sort the array using Bubble Sort:

6. Initialize a variable temp for swapping.

7. Outer Loop: Iterate through each element i of the array from 0 to n-1.

8. Inner Loop: Compare each element arr[i] with every subsequent element arr[j] where j starts from i+1 to n-1.

9. If arr[i] > arr[j], swap the elements using the temp variable.

10. Output the sorted array by printing each element in the array.

11. End the program.

## PROGRAM:

Developed by: Sneha Basyal M

RegisterNumber: 212222240101

## Sourcecode.java:
```
import java.util.Scanner;
public class Main
{
    public static void main(String[] args)
    {
        Scanner kbd=new Scanner(System.in);
        int n=kbd.nextInt();
        int[] arr=new int[n];
        for(int i=0;i<n;i++)
        {
            
                arr[i]=kbd.nextInt();
        }
        int temp=0;
        for(int i=0;i<arr.length;i++)
        {
            for(int j=i+1;j<arr.length;j++)
            {
                if(arr[i]>arr[j])
                {
                        temp=arr[i];
                        arr[i]=arr[j];
                        arr[j]=temp;
                }
            }
        }
        System.out.println("Result of a Sorted Array :");
        for(int i=0;i<n;i++)
        {
            System.out.printf("%d  ",arr[i]);
        }
    }
}
```

## OUTPUT:
![image](https://github.com/user-attachments/assets/a31e8398-d786-44cf-8e42-93eaa2083bc5)

## RESULT:
Thus the java program successfully sorts the elements of an array in ascending order.
