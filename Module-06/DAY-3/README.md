# Ex.No:6(C)             MULTIPLE INHERITANCE 

## AIM:
To Write a java program to display mark sheet of the Student using multiple inheritance


## ALGORITHM :

1. Start
2. Define interface `Student` with method `getDetails()`
3. Define interface `Studentdet` with methods `getMarks()` and `calculateAverage()`
4. Create class `Studentdetails` that **implements both interfaces** (achieving multiple inheritance)
5. Declare `rollNo`, `name`, `marks[]`, `average`, and `Scanner`
6. Implement `getDetails()` to input roll number and name
7. Implement `getMarks()` to input 6 marks
8. Implement `calculateAverage()` to compute average of 6 marks
9. Define `display()` to print student details and average
10. In `main`, create object of `Studentdetails`
11. Call `getDetails()`, `getMarks()`, `calculateAverage()`, and `display()`
12. End

## PROGRAM:

Program to implement a Multiple Inheritance using Java

Developed by: Sneha Basyal M

RegisterNumber: 212222240101


## Sourcecode.java:
```
import java.util.Scanner;
interface Student {
    void getDetails();
}


interface Studentdet {
    void getMarks();
    void calculateAverage();
}


class Studentdetails implements Student, Studentdet {
    int rollNo;
    String name;
    int[] marks = new int[6];
    double average;

    Scanner sc = new Scanner(System.in);

  
    public void getDetails() {
        rollNo = sc.nextInt();
        name = sc.next();
    }

  
    public void getMarks() {
        for (int i = 0; i < 6; i++) {
            marks[i] = sc.nextInt();
        }
    }

 
    public void calculateAverage() {
        int sum = 0;
        for (int i = 0; i < 6; i++) {
            sum += marks[i];
        }
        average = sum / 6;
    }

  
    public void display() {
        System.out.println("Roll No : " + rollNo);
        System.out.println("Name : " + name);
        System.out.println("Average  : " + (int) average);
    }
}


public class Main {
    public static void main(String[] args) {
        Studentdetails sd = new Studentdetails();
        sd.getDetails();
        sd.getMarks();
        sd.calculateAverage();
        sd.display();
    }
}
```

## OUTPUT:
![image](https://github.com/user-attachments/assets/2cb846b6-339d-4955-a634-116578fc3e42)



## RESULT:
Thus the java program for Multiple inheritance was executed successfully.






