# Ex.No:1(A) CLASS & OBJECTS

## AIM:
To create a class named 'Student' with String variable 'name' and integer variable 'roll_no'. 

## ALGORITHM :
1. Start
2. Define a class named Student with:
   - A String variable name
   - An int variable roll_no
3. Define the Main class
4. In the main method:
   - Create an object obj of class Student
   - Assign the value "John" to obj.name
   - Assign the value 5 to obj.roll_no
   - Print the values of obj.name and obj.roll_no with a space in between
5. End
   
## PROGRAM:

```
Program to implement a class & objects using Java

Developed by: Sneha Basyal M

RegisterNumber: 212222240101
```


## Sourcecode.java:
```
class Student
{
    String name;
    int roll_no;
}
public class Main
{
    public static void main(String[] args)
   {
        Student obj= new Student();
         obj.name="John";
         obj.roll_no=5;
         System.out.println(obj.name+" "+obj.roll_no);
    }    
}
```

## OUTPUT:

![image](https://github.com/user-attachments/assets/7e57eb94-fbb5-4b0f-a0b6-adfbc04a7931)


## RESULT:
Thus, the class named 'Student' with String variable 'name' and String variable 'address' was created successfully.
