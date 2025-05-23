# Ex.No:5(D) IS-A RELATIONSHIP AND HAS-A RELATIONSHIP
## AIM:
   To Create a java program to create a three class and apply is-a relationship concepts and display the output refer sample test.
 
## ALGORITHM :

1. Start

2. Define class `Animal` with variable `name` and method `eat()` to print "I can eat"

3. Define class `Dog` that extends `Animal` and has method `display()` to print the dog’s name

4. In `main`, create `Dog` object `labrador`

5. Assign `"Rohu"` to `labrador.name`

6. Call `labrador.display()` to print the name

7. Call `labrador.eat()` to print eating message

8. End

## PROGRAM:

Program to implement a IS-A RELATIONSHIP AND HAS-A RELATIONSHIP using Java

Developed by: Sneha Basyal M

RegisterNumber: 212222240101 


## Sourcecode.java:
```
class Animal {
 
  String name;
  public void eat() {
    System.out.println("I can eat");
  }
}


class Dog extends Animal {

  public void display() {
    System.out.println("My name is "+name);
  }
}

public class Main {
  public static void main(String[] args) {

    Dog labrador = new Dog();

   
    labrador.name = "Rohu";
    labrador.display();

   
    labrador.eat();

  }
}
```

## OUTPUT:
![image](https://github.com/user-attachments/assets/5550fe24-fc82-4700-893a-4de7a1f0b183)


## RESULT:
Thus the java program to create a three class and apply is-a relationship concepts was executed successfully.
