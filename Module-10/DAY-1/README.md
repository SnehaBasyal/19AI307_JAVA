# Ex.No:10(A)         JAVA COLLECTION FRAMEWORK –ARRAY LIST
## AIM:
 To Create a Java Program to Create an arraylist , add elements in an arraylist and then display in descending order.

## ALGORITHM:

1. Start
2. Read the number of strings `n` from user
3. Create an `ArrayList` to store strings
4. Loop from 1 to `n`:
    Read each string and add to the list
5. Sort the list in reverse (descending) order using `Collections.sort()` with `reverseOrder()`
6. Print the sorted list
7. End

## PROGRAM:

Program to implement a ARRAY LIST using Java

Developed by: Sneha Basyal M

RegisterNumber: 212222240101


## Sourcecode.java:
```
import java.util.*;
public class Main
{
    public static void main(String[] args)
    {
        Scanner sc = new Scanner(System.in);
        int n = sc.nextInt();
        ArrayList<String> elements = new ArrayList<>();
        for(int i=1;i<=n;i++)
        {
            elements.add(sc.next());
        }
        Collections.sort(elements, Collections.reverseOrder());
        System.out.print(elements);
    }
}
```


## OUTPUT:
![image](https://github.com/user-attachments/assets/5ea7d166-321f-4137-a5bf-83bcc510f64f)



## RESULT:
TThus the Java Program to Create an arraylist , add elements in an arraylist and then display in descending order was executed successfully.

