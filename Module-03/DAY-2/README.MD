## Ex.No:3(B) STRING BUFFER IN JAVA

## AIM:
To develop a java program use append() method concatenates the given argument with this String and use stringbuffer class.

## ALGORITHM :
1.	Start the program.
2.	Import `Scanner` and define class `concat`
3.	In `main`:
-	a) Create `Scanner` object `sc`
-	b) Read two strings `a` and `b` from user input
4.	Create a `StringBuffer` object `sb` initialized with string `a`
5.	Append a space and string `b` to `sb`
6.	Print the concatenated result from `sb`
7.	End



## PROGRAM:

Program to implement a String Buffer using Java

Developed by: Sneha Basyal M 

RegisterNumber: 212222240101  


## Sourcecode.java:
```
import java.util.Scanner;
public class Main
{
    public static void main(String[] args)
    {
        Scanner sc = new Scanner(System.in);
        String str = sc.nextLine();
        String str2 = sc.nextLine();
        StringBuffer sbf = new StringBuffer(str);
        sbf.append(" "+str2);
        System.out.print(sbf);
        
    }
}
```

## OUTPUT:
![image](https://github.com/SnehaBasyal/19AI307_JAVA/blob/e231c6e3a2d525bfc5073a12223f19de82f32b04/Module-03/DAY-2/Screenshot%202025-04-30%20152045.png)

## RESULT:
Thus the java program use append() method concatenates the given argument with this String and use stringbuffer class was executed successfully.
