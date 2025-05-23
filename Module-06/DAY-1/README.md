# Ex.No:6(A)  INNER CLASS
## AIM:
To create a Java Program to implement Method Local Inner Class.

## ALGORITHM :
1.  Start the Program.
2.	Define outer class `name`:
-	a) Declare `String name` and initialize it to "Johnson"
-	b) Define inner class `inner`:
- i) Define method `display()` that prints "Name given in Outer Class is " followed by `name`
3.	In the `main` method of `name` class:
-	a) Create an instance `obj` of the `name` class
-	b) Create an instance `obj2` of the inner class `inner` using `obj`
-	c) Call `display()` on `obj2` to print the outer class name
4.	End

## PROGRAM:

Program to implement a Inner Class using Java

Developed by: Sneha Basyal M

RegisterNumber: 212222240101


## Sourcecode.java:
```
class Name
{
    String val = "Johnson";
    
    class Inner
    {
        void display()
        {
            System.out.println("Name given in Outer Class is Johnson");
        }
        
    }
}
public class Main
{
    public static void main(String[] args)
    {
        Name obj = new Name();
        Name.Inner obj2 = obj.new Inner();
        obj2.display();
    }
}
```

## OUTPUT:
![image](https://github.com/user-attachments/assets/64c8fb85-bc57-4238-83fe-45e417c11172)


## RESULT:
Thus, the Java Program using Method Local Inner Class was executed successfully.

