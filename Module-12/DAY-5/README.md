# Ex.No:12(E)  JAVA DEQUEUE

## AIM:
To Write a java program to display the removal  element from the Dequeue using pollFirst method  in java collection.(Use string)
## ALGORITHM :

1. **Start**
2. **Create** an empty `Deque` of Strings using `ArrayDeque`
3. **Read** an integer `size` from the user
4. **Repeat** `size` times:

   * Read a string from the user
   * Add the string to the deque using `offer()`
5. **Display** the deque contents
6. **Display** the first element of the deque using `getFirst()`
7. **End**

## PROGRAM:

Program to implement a JAVA DEQUEUE

Developed by: Sneha Basyal M

RegisterNumber: 212222240101 


## Sourcecode.java:
```
import java.util.*;

public class deQueueDemo {
	

	public static void main(String args[])
	{
	
		Deque<String> dq = new ArrayDeque<String>();
        
	    Scanner sc=new Scanner(System.in);
	    int size=sc.nextInt();
	    for(int i=0;i<size;i++){
	        dq.offer(sc.next());
	    }
	    System.out.println("Display the element of Dequeue:");
		System.out.println(dq);
		System.out.println(dq.getFirst());
     	
	}
}
```


## OUTPUT:
![image](https://github.com/user-attachments/assets/767d2dde-4955-48ab-ac67-05ff420b7b78)



## RESULT:
Thus the java program to display the removal  element from the Dequeue using pollFirst method  in java collection (Use string) was executed successfully.


