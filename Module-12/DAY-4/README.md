# Ex.No:12(D) JAVA QUEUE
## AIM:
To Write a java program to Print the top of the element from the Priority Queue.


## ALGORITHM :

1. **Start**
2. **Create** an empty `PriorityQueue` of integers
3. **Read** the number of elements (`size`) from user
4. **Repeat** for `size` times:

   * Read an integer from the user
   * Add the integer to the priority queue
5. **Display** the top (smallest) element using `peek()`
6. **End**

## PROGRAM:

Program to implement a JAVA QUEUE using Java

Developed by: Sneha Basyal M

RegisterNumber: 212222240101


## Sourcecode.java:
```
import java.util.*;

public class PriorityQueueDemo {
	

	public static void main(String args[])
	{
	
		PriorityQueue<Integer> pQueue = new PriorityQueue<Integer>();
        
	    Scanner sc=new Scanner(System.in);
	    int size=sc.nextInt();
	    for(int i=0;i<size;i++){
	        pQueue.add(sc.nextInt());
	    }
	    System.out.println("Display the top of the element of PriorityQueue:");
		System.out.println(pQueue.peek());

		
	}
}
```

## OUTPUT:
![image](https://github.com/user-attachments/assets/527075dd-54b1-4754-b8e0-4573dd385939)



## RESULT:
Thus the java program to Print the top of the element from the Priority Queue was executed successfully.


