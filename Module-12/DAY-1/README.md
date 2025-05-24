# Ex.No:12(A)         JAVA TREE MAP
## AIM:
 To implement a Java program to get all keys from the given a Tree Map.

## ALGORITHM :
1. **Start**
2. **Create** an empty `TreeMap<String, String>`
3. **Read** the number of key-value pairs (size) from the user
4. **Repeat** for each pair (from 0 to size - 1):

   * Read a key (String)
   * Read a value (String)
   * **Insert** the key-value pair into the TreeMap
5. **Get** the set of keys from the TreeMap
6. **For each** key in the set:

   * **Print** the key
7. **End**

## PROGRAM:

Program to implement a JAVA TREE MAP using Java

Developed by: Sneha Basyal M

RegisterNumber: 212222240101 


## Sourcecode.java:
```
import java.util.*;  
public class Exa {  
   public static void main(String args[]){  

   TreeMap<String,String> tree_map1=new TreeMap<String,String>();      
  Scanner sc=new Scanner(System.in);
   int size=sc.nextInt();
   for(int i=0;i<size;i++)
   {
      String n1 = sc.next();
      String s1= sc.next();
       
   	  tree_map1.put(n1,s1);  
   }
    
 Set<String> keys = tree_map1.keySet();
        for(String key: keys){
            System.out.println(key);
        }
    }
}
```


## OUTPUT:
![image](https://github.com/user-attachments/assets/9ca6692d-9be2-4ff7-a99a-e3d45e27def8)


## RESULT:
Thus the Java program to get all keys from the given a Tree Map was executed successfully.
