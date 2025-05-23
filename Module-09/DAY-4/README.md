# Ex.No:9(D) TRANSIENT ---SERILIZATION

## AIM:
 To implement a Java program to perform transient in Student details(name,dept,rollno).

## ALGORITHM :

1. Start
2. Define class `Studentinfo` that implements `Serializable`
3. Declare fields: `name` (normal), `dept` and `rollno` as `transient`
4. Create constructor to initialize all fields
5. When serialized, only `name` will be saved; `dept` and `rollno` will be ignored due to `transient`
6. End

## PROGRAM:
 
Program to implement a Transient using Java

Developed by: Sneha Basyal M

RegisterNumber: 212222240101 


## Sourcecode.java:
```
 class Studentinfo implements Serializable
{
    String name;
   transient String dept;
    transient int rollno;
   
    Studentinfo(String n, String r,int n1)
    {
    this.name = n;
    this.dept = r;
    this.rollno=n1;
    }
}
```
## OUTPUT:
![image](https://github.com/user-attachments/assets/dad5a7b5-8e26-4042-af8c-a0e10c36a2fc)



## RESULT:
Thus, implementation of a Java program to perform Transient in Student details was executed and verified successfully.

