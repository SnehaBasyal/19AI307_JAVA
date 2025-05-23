# Ex.No:11(E)  JAVA HASHTABLE

## AIM:
To Create a java program to retrieve the key and value from hashtable and display the size of the hashtable and clear the hashtable using clear method concepts with map interface.


## ALGORITHM :
1. **Start**
2. **Create a map** using `Hashtable` to store `<Integer, String>` key-value pairs
3. **Read size** of entries from user
4. **Loop** from `0` to `size - 1`:

   * Read an integer key
   * Read a string value
   * Insert the pair into the map
5. **Iterate** through the map:

   * For each key, print the key and its corresponding value
6. **Print** the current size of the map
7. **Clear** all entries from the map
8. **Print** the size of the map after clearing
9. **End**

## PROGRAM:

Program to implement a HASHTABLE

Developed by: Sneha Basyal M

RegisterNumber: 212222240101  


## Sourcecode.java:
```
import java.util.*;  
public class Mapp{  
 public static void main(String args[]){ 
     
  Map<Integer,String> map=new Hashtable<>(); 
  Scanner sc=new Scanner(System.in);
  
  int size=sc.nextInt();
  for(int i=0;i<size;i++)
  {
  Integer a=sc.nextInt();
  String b=sc.next();
  map.put(a,b);  
  } 
 
  
 Iterator<Integer> keySetIterator = map.keySet().iterator(); 
 while(keySetIterator.hasNext())
 { 
     Integer key = keySetIterator.next(); 
     System.out.println("key: " + key + " value: " + map.get(key)); 
     
 }

System.out.println("Size of Map: " + map.size()); map.clear(); 
System.out.println("Size of Map: " + map.size()); 

 }  
}
```


## OUTPUT:
![image](https://github.com/user-attachments/assets/c5c3e6e4-608c-4eba-ad86-6431c93bdf2e)



## RESULT:
Thus the java program to retrieve the key and value from hashtable and display the size of the hashtable and clear the hashtable using clear method concepts with map interface was executed successfully.




