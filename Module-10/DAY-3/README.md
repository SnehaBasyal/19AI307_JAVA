# Ex.No:10(C)             JAVA LIST INTERFACE
 ## AIM :

To Create a List interface implemented by arraylist class , adding n elements to object of List interface and print all the elements inside the List interface object and apply the iterator in list using for loop for iteration.


## ALGORITHM :
1. Start
2. Read the size of the list from user
3. Create a `List` using `ArrayList`
4. Loop `size` times to read and add elements to the list
5. Loop again to print each element using `get()`
6. Print the size of the list using `size()`
7. End


## PROGRAM:

Program to implement a JAVA LIST INTERFACE using Java

Developed by: Sneha Basyal M

RegisterNumber: 212222240101  

## Sourcecode.java:
```
import java.util.*;
public class Main {

	public static void main(String args[])
	{
		Scanner sc=new Scanner(System.in);
		List<String> al = new ArrayList<>();
        int size=sc.nextInt();
        for(int i=0;i<size;i++)
        {
				al.add(sc.next());
        }

		for (int i = 0; i < size; i++) {
  
            
            System.out.println(al.get(i) + " ");
        }
	    System.out.print("Size of the List:" + al.size());
	}
}
```

## OUTPUT:



## RESULT:
Thus the java program implemented a List interface for array list was executed and verified successfully.


