# Ex.No:7(A)           EXCEPTION HANDLING-RUN TIME EXCEPTION
## AIM:
  To Develop a Java Program for NullPointerException.

## ALGORITHM :
1. Start
2. Declare a `String` variable `str` and assign `null`
3. Use `try` block to call `str.length()`
4. This throws a `NullPointerException`
5. Catch the exception in `catch(NullPointerException e)`
6. Print `"NullPointerException.."`
7. End

## PROGRAM:

Program to implement Java Program for NullPointerException.

Developed by: Sneha Basyal M

RegisterNumber: 212222240101 


## Sourcecode.java:
```
public class Exception2 
{
   public static void main(String args[])
   {
	try{
		String str=null;
		System.out.println (str.length());
	}
        catch(NullPointerException e){
		System.out.println("NullPointerException..");
	}
   }
}
```

## OUTPUT:
![image](https://github.com/user-attachments/assets/0e518724-24c8-4506-851f-067746a9232b)



## RESULT:
Thus the Java Program for NullPointerException was executed successfully.

