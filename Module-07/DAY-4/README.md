# Ex.No:7(D) SYNCHRONIZATION
## AIM:
 To Develop a Java Program to perform Fibonacci series for static synchronization method
 
## ALGORITHM :

1. Start
2. Define class `Table`
3. Create `static synchronized` method `fibonacci(n)`
4. Generate and print Fibonacci series up to `n` terms
5. Pause using `Thread.sleep(400)`
6. End


## PROGRAM:

Program to implement a synchronization using Java

Developed by: Sneha Basyal M

RegisterNumber: 212222240101


## Sourcecode.java:
```
  class Table
  {
   static synchronized void fibonacci(int n)
   {
       int  firstTerm = 0, secondTerm = 1;
    System.out.print("Fibonacci Series for " + n + " value:");

    for (int i = 1; i <= n; ++i) {
      System.out.print(firstTerm + ", ");
      int nextTerm = firstTerm + secondTerm;
      firstTerm = secondTerm;
      secondTerm = nextTerm; 
    }
    System.out.println(" ");
     try
     {  
      Thread.sleep(400);  
     }
     catch(Exception e){System.out.println(e);}  
   } 
   
  }
```

## OUTPUT:
![image](https://github.com/user-attachments/assets/f2ea6b00-6a4d-4a8d-aeb1-5d66153604d3)


## RESULT:
Thus the java program to perform Fibonacci series for static synchronization method was executed successfully.

