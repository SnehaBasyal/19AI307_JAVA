# Ex.No:11(B)   JAVA MAP & HASHMAP AND HASHTABLE
## AIM :
To Create a java program to retrieve the key and value from hashtable for all input value.

## ALGORITHM :

1. Start
2. Create a `Hashtable<Integer, String>`
3. Read size of entries
4. Loop to read `key` (Integer) and `value` (String), insert into `map` using `put()`
5. Get `keySet()` and create an `Iterator`
6. While iterator has elements:
   * Get `key`
   * Print `key` and corresponding `value` using `get(key)`
7. End

## PROGRAM:

Program to implement a JAVA MAP & HASHMAP AND HASHTABLE using Java

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


 }  
}
```


## OUTPUT:



## RESULT:
Thus the java program to retrieve the key and value from hashtable for all input value was executed successfully.







