# Ex.No:12(B)   COMPARABLE & COMPARATOR INTERFACE
## AIM :
To Write a java program to sort the list based on null value for name using comparator method(nullsfirst).

## ALGORITHM :

1. **Start**
2. **Create a class `Student`** with attributes: `rollno`, `name`, and `age`
3. **Define** getter and setter methods for each attribute
4. **In the main method:**

   * Create an `ArrayList` of `Student` objects
   * Add `Student` objects to the list (some with `null` names)
5. **Create a comparator** to compare students by name using `Comparator.comparing()` with `Comparator.nullsFirst()` to treat `null` as less than non-null
6. **Sort** the list using `Collections.sort()` with the comparator
7. **Display** the sorted list: roll number, name, and age for each student
8. **End**

## PROGRAM:

Program to implement a COMPARABLE & COMPARATOR INTERFACE using Java

Developed by: Sneha Basyal M

RegisterNumber: 212222240101 



## Sourcecode.java:
```
import java.util.*;    
 class Student {    
   int rollno;    
   String name;    
  int age;    
    Student(int rollno,String name,int age){    
    this.rollno=rollno;    
    this.name=name;    
    this.age=age;    
    }  
    public int getRollno() {  
        return rollno;  
    }  
    public void setRollno(int rollno) {  
        this.rollno = rollno;  
    }  
    public String getName() {  
        return name;  
    }  
  
    public void setName(String name) {  
        this.name = name;  
    }  
  
    public int getAge() {  
        return age;  
    }  
    public void setAge(int age) {  
        this.age = age;  
    }  
    }    public class TestSort2{    
 public static void main(String args[]){    
 ArrayList<Student> al=new ArrayList<Student>();    
 al.add(new Student(101,"Vijay",23));    
 al.add(new Student(106,"Ajay",27));    
 al.add(new Student(105,null,21));    
 Comparator<Student> cm1=Comparator.comparing(Student::getName,Comparator.nullsFirst(String::compareTo));  
  Collections.sort(al,cm1);  
  System.out.println("Considers null to be less than non-null");  
  for(Student st: al){  
     System.out.println(st.rollno+" "+st.name+" "+st.age);  
     }  
  
 }    
 }     
```



## OUTPUT:
![image](https://github.com/SnehaBasyal/19AI307_JAVA/blob/319c3e19d0e6311a2bcd9fc7a4c64a2dad7013db/Module-12/DAY-2/Screenshot%202025-05-24%20095707.png)


## RESULT:
Thus the java program to sort the list based on null value for name using comparator method(nullsfirst) was executed successfully




