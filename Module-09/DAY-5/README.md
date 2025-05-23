# Ex.No:9(E) DATA INPUT STREAM

## AIM:
To write a Java program for displaying number of bytes & read the String,Float,Character value data in the  file "OutputFile.txt" using DataInputStream

## ALGORITHM :
1. Start
2. Create `FileInputStream` for `"OutputFile.txt"`
3. Wrap it with `DataInputStream`
4. Print the number of available bytes using `available()`
5. Read and print a UTF string using `readUTF()`
6. Read and print a float using `readFloat()`
7. Read and print a character using `readChar()`
8. Close `DataInputStream` and `FileInputStream`
9. End

## PROGRAM:

Program to implement a DATA INPUT STREAM

Developed by: Sneha Basyal M

RegisterNumber: 212222240101


## Sourcecode.java:
```
FileInputStream fi = new FileInputStream("OutputFile.txt");
DataInputStream di = new DataInputStream(fi);
    
System.out.println("Available number of bytes to read: " +di.available());
System.out.println("Read UFT: " + di.readUTF());
    
System.out.println("Read Float: " + di.readFloat());
System.out.println("Read Char: " + di.readChar());
 
di.close();
fi.close();
```

## OUTPUT:
![image](https://github.com/user-attachments/assets/593ee527-5a47-4859-8c9a-dfec382325fc)



## RESULT:
Thus, implementation of  a Java program for displaying number of bytes & read the String,Float,Character value data in the  file "OutputFile.txt" using DataInputStream was executed successfully.

