# Ex.No:6(E)  HIERARCHICAL INHERITANCE

## AIM:
To write a Java program using Hierarchical inheritance.

## ALGORITHM :

1. Start
2. Define class `Shape` with method `display()` that prints `"Shape Class"`
3. Define class `Rectangle` that extends `Shape`, with method `show()` printing `"Rectangle Class"`
4. Define class `Triangle` that extends `Shape`, with method `show()` printing `"Triangle Class"`
5. Define class `Circle` that extends `Shape`, with method `show()` printing `"Circle Class"`
6. In `main`, create objects of `Rectangle`, `Triangle`, and `Circle`
7. Call `display()` and `show()` for each object
8. End

## PROGRAM:

Program to implement a Hierarchical Inheritance

Developed by: Sneha Basyal M

RegisterNumber: 212222240101

## Sourcecode.java:

```
class Shape {
    void display() {
        System.out.println("Shape Class");
    }
}

class Rectangle extends Shape {
    void show() {
        System.out.println("Rectangle Class");
    }
}

class Triangle extends Shape {
    void show() {
        System.out.println("Triangle Class");
    }
}

class Circle extends Shape {
    void show() {
        System.out.println("Circle Class");
    }
}

public class Main {
    public static void main(String[] args) {
        Rectangle rectangle = new Rectangle();
        Triangle triangle = new Triangle();
        Circle circle = new Circle();

        rectangle.display();
        rectangle.show();

        triangle.display();
        triangle.show();

        circle.display();
        circle.show();
    }
}

```

## OUTPUT:
![image](https://github.com/user-attachments/assets/18f0c4ac-f402-4a0a-97e7-5f5e7cf7a973)


## RESULT:

Thus, the java program demonstrates heirarchical inheritance was successfully executed.
