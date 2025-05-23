# Ex.No:4(D) FINAL & STATIC IN JAVA

## AIM:
   To create a Java program to perform final & static keyword for below situation Employee object contains member 'Emp_Id'. It contains object named name, which contains its own informations such as Fname, Mname, Lname.
 
## ALGORITHM :
1.	Start the Program.
2.	Define class `Name`:
-	a) Declare three `String` variables: `Fname`, `Mname`, and `Lname`
-	b) Define method `dispName(String fn, String mn, String ln)`:
-	i) Print the full name using the passed parameters `fn`, `mn`, and `ln`
3.	Define class `Employee`:
-	a) Declare an integer variable `Emp_Id`
-	b) Create an instance of `Name` called `obj`
-	c) Define method `disp(int id)`:
-	i) Print the employee ID
-	ii) Create a new `Name` object and call `dispName("B", "Leo", "John")` to display the name
4.	Define `Main` class with `main` method:
-	a) Create an `Employee` object `emp`
-	b) Call `emp.disp(101)` to display the employee details
5.	End


## PROGRAM:

Program to implement a final & Static using Java

Developed by: Sneha Basyal M 

RegisterNumber: 212222240101


## Sourcecode.java:
```
class Name
{
    String Fname;
    String Mname;
    String Lname;
    Name(String fn,String mn,String ln)
    {
        this.Fname=fn;
        this.Mname=mn;
        this.Lname=ln;
    }
    void dispName()
    {
        System.out.println(Mname+" "+Fname+" "+Lname);
    }
}
class Employee
{
    int Emp_Id;
    Name obj;
    Employee(int id,String fn,String mn,String ln)
    {
        this.Emp_Id=id;
        this.obj=new Name(fn,mn,ln);
    }
    void dispEmployee()
    {
        System.out.println(Emp_Id);
        obj.dispName();
    }
}

public class Main
{
    public static void main(String[] args)
    {
   
      Employee emp=new Employee(101,"Leo","B","John");
      emp.dispEmployee();
        
    }
}
```

## OUTPUT:

![image](https://github.com/user-attachments/assets/20e73042-b37d-4cfb-9b67-cdfca3aed30e)


## RESULT:
Thus, the java program to perform final & static keyword was executed successfully.
