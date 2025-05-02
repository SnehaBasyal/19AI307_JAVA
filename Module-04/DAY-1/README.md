# Ex.No:4(A)  JAVA CONSTRUCTOR
## AIM:
To create a Java program using copy constructor to print the circumference of rectangle.[l=5,w=6]

## ALGORITHM :
1. Define a Rectangle class with length and breadth attributes.

2. Create a constructor to initialize length and breadth with given values.

3. Create a copy constructor to initialize a new object using another Rectangle object.

4. Define a method circumference() to calculate and return 2 * (length + breadth)

5. In main, create firstRect with values 5 and 6.

6. Create secondRect using the copy constructor with firstRect.

7. Print the circumference of both rectangles.

8. End the program.


## PROGRAM:

Program to implement a Constructor using Java

Developed by:  Sneha Basyal M

RegisterNumber: 212222240101 


## Sourcecode.java:
```
class Rectangle
{
    int length;
    int breadth;

    
    Rectangle(int l, int b)
    {
        this.length = l;
        this.breadth = b;
    }

 
    Rectangle(Rectangle obj)
    {
        this.length = obj.length;
        this.breadth = obj.breadth;
    }

    
    int circumference()
    {
        return 2 * (length + breadth);
    }
}

public class CopyConstructor
{
    public static void main(String[] args)
    {
        Rectangle firstRect = new Rectangle(5, 6);
        Rectangle secondRect = new Rectangle(firstRect);
        System.out.println("Area  of First Rectangle : " + firstRect.circumference());
        System.out.println("Area of First Second Rectangle : " + secondRect.circumference());
    }
}
```

## OUTPUT:
![image](https://github.com/user-attachments/assets/12a0b18b-ba6d-42ce-a614-0c56d3c99c35)



## RESULT:
Thus the Java program using copy constructor to print the circumference of rectangle was executed successfully.
