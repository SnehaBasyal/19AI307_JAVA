# Ex.No:10(E)  ARRAYLIST

## AIM:
To write a Java program of swap two elements in a list. Swapping 1st(index 0) element with the 3rd(index 2) element.

## ALGORITHM :

1. Start
2. Read number of elements `n` from user
3. Create an empty `ArrayList<String>`
4. Read `n` strings and add to the list
5. Display list before swap
6. If list size ≥ 3, swap elements at index 0 and 2
7. Else, print "Swap not possible" and exit
8. Display list after swap
9. End


## PROGRAM:

Program to implement a ArrayList

Developed by: Sneha Basyal M

RegisterNumber: 212222240101


## Sourcecode.java:
```
import java.util.ArrayList;
import java.util.Scanner;

public class SwapElements {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);

        int n = scanner.nextInt();
        scanner.nextLine();  

        ArrayList<String> list = new ArrayList<>();
        for (int i = 0; i < n; i++) {
            list.add(scanner.nextLine());
        }

        System.out.println("Array list before Swap:");
        for (String item : list) {
            System.out.println(item);
        }

        if (list.size() >= 3) {
            String temp = list.get(0);
            list.set(0, list.get(2));
            list.set(2, temp);
        } else {
            System.out.println("Swap not possible: Less than 3 elements.");
            return;
        }

        System.out.println("Array list after swap:");
        for (String item : list) {
            System.out.println(item);
        }

        scanner.close();
    }
}

```

## OUTPUT:
![image](https://github.com/user-attachments/assets/90bf87eb-0f3c-4703-91e5-5f150ca4679b)


## RESULT:
Thus the java program to swap two elements in a list. Swapping 1st(index 0) element with the 3rd(index 2) element was executed successfully.
