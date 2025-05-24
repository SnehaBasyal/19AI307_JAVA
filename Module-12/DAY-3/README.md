# Ex.No:12(C)             JAVA STACK & VECTOR
 ## AIM :

To Write a java program to read and  print all the  elements and also firstelement() using vector method  in java collection.

## ALGORITHM:
1. **Start**
2. **Create a Vector** of type `String`
3. **Read input size** (number of iterations) from user
4. **Repeat for given size:**

   * Read two strings from user
   * Add both strings to the vector
5. **Print the complete vector**
6. **Display the first element of the vector**
7. **End**

## PROGRAM:

Program to implement a JAVA STACK & VECTOR  using Java

Developed by: Sneha Basyal M

RegisterNumber: 212222240101 


## Sourcecode.java:
```
import java.util.*;

public class VectorDemo {
	public static void main(String args[])
	{

		
		Vector<String> vec_tor = new Vector<String>();
        Scanner sc=new Scanner(System.in);
        int size=sc.nextInt();
	    for(int i=0;i<size;i++)
	    {
		vec_tor.add(sc.next());
	    vec_tor.add(sc.next());
	    }
	

		System.out.println("The vector is: " + vec_tor);

	    System.out.println("The first element is: "
                           + vec_tor.firstElement());
	}
}
```


## OUTPUT:
![image](https://github.com/user-attachments/assets/164aa7a6-8666-4e6f-8a29-99f1acb4da11)


## RESULT:

Thus the java program to read and  print all the  elements and also firstelement() using vector method  in java collection.was executed successfully.








