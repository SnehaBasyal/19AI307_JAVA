# Ex.No:5(B) TIGHTLY ENCAPSULATED CLASS

## AIM:
To Create a java program to print the product of two number use tightly encapsulated class. 

## ALGORITHM :

1. Start

2. Define class product with private strings a and b

3. Define set() method to assign input values to a and b

4. Define get() method to convert a and b to integers, multiply them, and print the product

5. In main, create Scanner and product objects

6. Read two inputs as strings and call set()

7. Call get() to display the product

8. End

## PROGRAM:

Program to implement a tightly encapsulated class using Java

Developed by: Sneha Basyal M 

RegisterNumber: 212222240101  


## Sourcecode.java:
```
import java.util.*;
class product
{
    private String a;
    private String b;
    
    public void set(String a, String b)
    {
        this.a = a;
        this.b = b;
    }
    public void get()
    {
        int a1 = Integer.parseInt(a);
        int b1 = Integer.parseInt(b);
        System.out.println("Product is "+a1*b1);
    }
}
public class Main
{
    public static void main(String[] args)
    {
        Scanner sc = new Scanner(System.in);
        product obj = new product();
        obj.set(sc.next(),sc.next());
        obj.get();
    }
}
```

## OUTPUT:



## RESULT:
Thus a java program to print the product of two number using tightly encapsulated class is executed successfully.



