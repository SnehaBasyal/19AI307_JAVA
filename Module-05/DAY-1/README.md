# Ex.No:5(A)  DATA HIDING AND ENCAPSULATION
## AIM:
To Write a java program to display name and location of the employee and use the encapsulation concepts.

## ALGORITHM :
1. Start

2. Import Scanner

3. Define class display with private variables name and location

4. Define set() to assign values

5. Define get() to print values

6. In main, create Scanner and display objects

7. Read two strings and pass to set()

8. Call get()

9. End

## PROGRAM:

Program to implement a Data Hiding & Encapsulation using Java

Developed by: Sneha Basyal M

RegisterNumber: 212222240101 


## Sourcecode.java:
```
import java.util.*;
class display
{
    private String name;
    private String location;
    
    public void set(String n, String l)
    {
        name = n;
        location = l;
        
    }
    public void get()
    {
        System.out.println(name);
        System.out.println(location);
    }
}
public class Main
{
    public static void main(String[] args)
    {
        Scanner sc=new Scanner(System.in);
        display obj = new display();
        obj.set(sc.next(),sc.next());
        obj.get();
        
    }
}
```
## OUTPUT:

![image](https://github.com/user-attachments/assets/b7872ec7-4537-484a-9ac2-b9da658894ce)


## RESULT:
Thus , the  java program to display name and location of the employee using encapsulation concepts is executed successfully.
