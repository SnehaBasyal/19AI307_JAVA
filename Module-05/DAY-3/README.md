# Ex.No:5(C)    GETTER AND SETTER METHOD

## AIM:
To Create a java program to print the factorial of given number with the help of setter and getter method.

## ALGORITHM :
1. Start
   
3. Import `Scanner`
   
3. Define class `fact` with private integer `num`
   
4. Define `setter(int num)` to assign value to `num`
   
5. Define `getter()` to calculate factorial using a loop and print result
    
6. In `main`, create `Scanner` and `fact` objects
    
7. Read integer input and call `setter()`
    
8. Call `getter()` to display factorial
    
9. End

## PROGRAM:
Program to implement a Getter and Setter using Java

Developed by: Sneha Basyal M

RegisterNumber: 212222240101 


## Sourcecode.java:
```
import java.util.*;
class fact
{
    private int num;
    
    public void setter(int num)
    {
        this.num = num;
    }
    public void getter()
    {
        int f = 1;
        
        int i=1;
        
        while(i<=num)
        {
            f = f * i;
            i++;
        }
        
        System.out.print("Factorial of "+num+" is: "+f);
    }
}
public class Main
{
    public static void main(String[] args)
    {
        Scanner sc = new Scanner(System.in);
        fact obj = new fact();
        obj.setter(sc.nextInt());
        obj.getter();
    }
}
```

## OUTPUT:
![image](https://github.com/user-attachments/assets/6b6ce94c-f8a4-4a39-bc76-841afe622c7b)


## RESULT:
Thus the java program to print the factorial of given number with the help of setter and getter method was executed successfully.






