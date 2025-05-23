# Ex.No:10(B) JAVA LINKED LIST
## AIM :
To Create a java program to create the linkedlist , display the elements from the linkedlist and replace the one element from the created linkedlist.

## ALGORITHM :

1. Start
2. Read number of elements `n` from user
3. Create a `LinkedList` of strings
4. Loop `n` times to read and add strings to the list
5. Print the original linked list
6. Read index and new string from user
7. Replace the element at given index using `set()` and print the replaced value
8. Print the updated linked list
9. End

## PROGRAM:

Program to implement a JAVA LINKED LIST using Java

Developed by: Sneha Basyal M

RegisterNumber: 212222240101


## Sourcecode.java:

```
import java.util.*;

public class Main {
  public static void main(String[] args) {
   Scanner sc=new Scanner(System.in);
    LinkedList<String> cars = new LinkedList<String>();
    int n=sc.nextInt();
    for(int i=0;i<n;i++)
    {
    cars.add(sc.next());
    }
    
       System.out.println("Linked List :" + cars);



      System.out.println("Object to be replaced:" + cars.set(sc.nextInt(), sc.next()));

 

      System.out.println("Linked List:" + cars);
  }
}
```


## OUTPUT:



## RESULT:
Thus the Java program of the creation of a linkedlist was executed successfully.





