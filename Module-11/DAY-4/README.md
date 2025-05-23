# Ex.No:11(D) RELATED TO MAP CONCEPTS

## AIM:
To Create a java program to display the name with key  using map interface like key , value pair.

## ALGORITHM :
1. Start
2. Create an empty map to store key-value pairs
3. Read how many pairs to input (size)
4. Repeat for given size:

   * Read a key (integer)
   * Read a value (name)
   * Put key and value into the map
5. Print all key-value pairs from the map
6. End

## PROGRAM:
 
Program to implement a RELATED TO MAP CONCEPTS using Java

Developed by: Sneha Basyal M

RegisterNumber: 212222240101 


## Sourcecode.java:
```
import java.util.*;  
public class Mapp{  
 public static void main(String args[]){ 
     
  Map<Integer,String> map=new HashMap<Integer,String>(); 
  Scanner sc=new Scanner(System.in);
  
  int size=sc.nextInt();
  for(int i=0;i<size;i++)
  {
  Integer a=sc.nextInt();
  String b=sc.next();
  map.put(a,b);  
  } 
 
  for(Map.Entry m:map.entrySet()){  
   System.out.println(m.getKey()+" "+m.getValue());  
  }  
 }  
}
```

## OUTPUT:
![image](https://github.com/user-attachments/assets/030b8cc2-9c95-4a6b-a311-72e1e316b792)



## RESULT:
Thus the java program to display the name with key  using map interface like key , value pair was executed and verified successfully.


