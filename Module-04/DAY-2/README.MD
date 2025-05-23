# Ex.No:4(B) INTRODUCTION TO JAVA INHERITANCE

## AIM:
Write a Java program forthe situation: Student object contains member 'Stu_Id'. It contains  object named subject, which contains its own informations such as subject1,subject2,subject3,subject4.

## ALGORITHM :
1. Start the program

2. Create class Subject

3. Declare string variables for subjects

4. Define method disp to print four subjects

5. Create class Student

6. Declare student ID variable

7. Create Subject class object

8. Define method disp to print ID and call subject's disp method

9. Create Main class

10. Create Student object

11. Call disp method with student ID

12. End the program

## PROGRAM:
 ```
Program to implement a Inheritance using Java

Developed by: Sneha Basyal M

RegisterNumber:  212222240101

## Sourcecode.java:
```
class Subject
{
    String sub1;
    String sub2;
    String sub3;
    String sub4;
    void disp(String s1,String s2,String s3,String s4)
    {
        System.out.println(s1+" "+s2+" "+s3+" "+s4);
    }
}
class Student
{
    int Stu_Id;
    Subject obj = new Subject();
    void disp(int id)
    {
       System.out.println(id);
       obj.disp("Java","DS","TOC","CG");
       
    }
}

public class Main
{
    public static void main(String[] args)
    {
        Student obj=new Student();
        obj.disp(101);
        
        
    }
}
```

## OUTPUT:



## RESULT:
Thus the Java program to implement the inheritance concept for employee details was  executed successfully.

