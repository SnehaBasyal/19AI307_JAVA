# Ex.No:7(C)             THREAD IN JAVA
## AIM:
 To Develop a Java program to create Thread using Thread class.


## ALGORITHM :
1.  Start the Program
2.	Import necessary classes: `java.util.*`
3.	Define a class `Multi` that extends `Thread`:
-	a) Create a `Scanner` instance for user input.
-	b) Override the `run` method:
-	i) Read a string from user input.
-	ii) Print "Thread Name:" followed by the input string.
4.	In the `main` method:
-	a) Create an instance of `Multi`.
-	b) Create a new `Thread` instance using the `Multi` object.
-	c) Start the thread with `t1.start()`.
5.	End


## PROGRAM:

Program to implement a Thread concepts using Java

Developed by: Sneha Basyal M 

RegisterNumber: 212222240101  


## Sourcecode.java:
```
import java.util.*;
    public class Multi implements Runnable
    {  
        Scanner sc=new Scanner(System.in);
        
    public void run()
    {  
        String name=sc.nextLine();
        System.out.println("Thread Name:" +name);  
    }  
    public static void main(String args[]){  
    Multi m1=new Multi();  
    Thread t1 =new Thread(m1); 
    t1.start();  
     }  
    }  
```

## OUTPUT:
![image](https://github.com/user-attachments/assets/66a556e4-cb8e-4908-8cc7-bf8d44777eef)


## RESULT:
Thus the Java program for the creation of Thread using Thread class was executed successfully.







