# Ex.No:8(D) BUFFER INPUT/OUTPUT STREAM

## AIM:
 To create a java program for writing the Specified length of data in the file Using FileOutputStream & BufferedOutputStream

## ALGORITHM :

1. Start
2. Create `FileOutputStream` for `"sample.txt"`
3. Wrap it in `BufferedOutputStream`
4. Read a line of input from user
5. Convert input string to byte array
6. Print original input
7. Write 10 bytes starting from index 5 using `bout.write(b, 5, 10)`
8. Print message for skipped output
9. Close `BufferedOutputStream` and `FileOutputStream`
10. End

## PROGRAM:

Program to implement a Buffer Input/Output Stream using Java

Developed by: Sneha Basyal M

RegisterNumber: 212222240101


## Sourcecode.java:
```
       
    FileOutputStream fout=new FileOutputStream("sample.txt");    
     BufferedOutputStream bout=new BufferedOutputStream(fout);  
     Scanner sc=new Scanner(System.in);
     String s=sc.nextLine();    
     byte b[]=s.getBytes();    
     System.out.println("Original Data:" +s);
     System.out.print("After Skipping:");
     bout.write(b,5,10);    
     bout.close();    
     fout.close();    
       
```

## OUTPUT:
![image](https://github.com/user-attachments/assets/b7839c00-c7f1-4bed-ba47-b50aa8958b33)



## RESULT:
Thus, the java program for writing the Specified length of data in the file Using FileOutputStream & BufferedOutputStream was executed and done successfully.


