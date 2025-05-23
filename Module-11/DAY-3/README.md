# Ex.No:11(C)             JAVA LINKED HASHMAP
 ## AIM :

To Create a java program to display the contains key of 104 and to retrieve the key and value using linked hash map.

## ALGORITHM :
1. Start
2. Create `LinkedHashMap<Integer, String> map`
3. Read total entries `size` from user
4. Loop `size` times:
   * Read key (Integer) and value (String)
   * Store in `map` using `put()`
5. Create iterator from `keySet()`
6. While iterator has next key:
   * Print key and its value using `get(key)`
7. Check if map contains key `104` using `containsKey(104)` and print result
8. End


## PROGRAM:

Program to implement a JAVA LINKED HASH MAP using Java

Developed by: Sneha Basyal M

RegisterNumber: 212222240101


## Sourcecode.java:
```
import java.util.*;  
public class Mapp{  
 public static void main(String args[]){ 
     
  LinkedHashMap<Integer,String> map=new LinkedHashMap<Integer,String>(); 
  Scanner sc=new Scanner(System.in);
  
  int size=sc.nextInt();
  for(int i=0;i<size;i++)
  {
  Integer a=sc.nextInt();
  String b=sc.next();
  map.put(a,b);  
  } 
 
  
 Iterator<Integer> keySetIterator = map.keySet().iterator(); while(keySetIterator.hasNext()){ Integer key = keySetIterator.next(); System.out.println("key: " + key + " value: " + map.get(key)); }

System.out.println("Does HashMap contains 104 as key: " + map.containsKey(104));



 }  
}
```


## OUTPUT:
![image](https://github.com/user-attachments/assets/585c3d24-9496-4488-9bba-346205365a7a)


## RESULT:
Thus the  java program to display the contains key of 104 and to retrieve the key and value using linked hash map was executed successfully.








