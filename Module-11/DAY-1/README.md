# Ex.No:11(A)         JAVA TREESET
## AIM:
 To develop a Java program to add all the elements of a specified tree set to another tree set.


## ALGORITHM :

1. Start
2. Read sizes `size1` and `size2`
3. Create `TreeSet<Integer> tree_set1`
4. Read `size1` integers and add to `tree_set1`
5. Display `tree_set1`
6. Create `TreeSet<Integer> tree_set2`
7. Read `size2` integers and add to `tree_set2`
8. Display `tree_set2`
9. Merge `tree_set2` into `tree_set1` using `addAll()`
10. Display merged `tree_set1`
11. End


## PROGRAM:

Program to implement a JAVA TREESET using Java

Developed by: Sneha Basyal M

RegisterNumber: 212222240101 


## Sourcecode.java:
```
import java.util.*;
public class Main {
  public static void main(String[] args) {
  Scanner sc=new Scanner(System.in);
  int size1=sc.nextInt();
   int size2=sc.nextInt();
  TreeSet<Integer> tree_set1 = new TreeSet<Integer>();
    for(int i=0;i<size1;i++){
    tree_set1.add(sc.nextInt());
    }
  
  
  System.out.println("Tree set1: "+tree_set1);
  TreeSet<Integer> tree_set2 = new TreeSet<Integer>();
  for(int i=0;i<size2;i++){
    tree_set2.add(sc.nextInt());
    }
  
  System.out.println("Tree set2: "+tree_set2);
  
   tree_set1.addAll(tree_set2);
   System.out.println("Tree set1: "+tree_set1);
 }
}

```


## OUTPUT:
![image](https://github.com/user-attachments/assets/1cf72777-3bc9-4800-83f7-d6650596aeeb)



## RESULT:
Thus the java program to add all the elements of a specified tree set to another tree set was executed successfully.

