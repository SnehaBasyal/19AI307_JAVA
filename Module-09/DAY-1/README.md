# Ex.No:9(A)          DATA I/O STREAM
## AIM:
To create a Java Program to store a String Value in a file "testout.txt" using DataOutputStream

## ALGORITHM :
1. Start
2. Create `FileOutputStream` for `"testout.txt"`
3. Wrap it with `DataOutputStream`
4. Write a UTF string to the file using `writeUTF()`
5. Close `DataOutputStream` and `FileOutputStream`
6. Print success message
7. End

## PROGRAM:

Program to implement a DATA I/O STREAM using Java

Developed by: Sneha Basyal M

RegisterNumber: 212222240101 


## Sourcecode.java:
```
FileOutputStream fout=new FileOutputStream("testout.txt");    
DataOutputStream dout=new DataOutputStream(fout);
dout.writeUTF("This is a file created by using Data Stream"); 
dout.close();    
fout.close();
System.out.println("Successfully Completed");  
                       
```

## OUTPUT:
![image](https://github.com/user-attachments/assets/864df834-75ff-40bf-be03-b847b8b97e0f)



## RESULT:
Thus the Java Program to store a String Value in a file "testout.txt" using DataOutputStream was executed and verified successfully.

