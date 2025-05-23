# Ex.No:8(B) IO-FILE READER/WRITER
## AIM:
To create a Java Program to read the content from the file "test.txt" using Reader

## ALGORITHM :

1. Start
2. Create a `FileReader` object for `"test.txt"`
3. Read first character from file
4. Print `"File content:"`
5. Loop while character is not `-1` (end of file)
6. Print each character
7. Read next character
8. After loop, print newline
9. Close the file
10. End

## PROGRAM:

Program to implement a IO File Reader/Writer using Java

Developed by: Sneha Basyal M

RegisterNumber: 212222240101 


## Sourcecode.java:
```
Reader reader = new FileReader("test.txt");  
int data = reader.read();  
System.out.println("File content:");
while (data != -1) 
{ 
                
    System.out.print((char) data);  
    data = reader.read();  
}  
System.out.println();
reader.close();  
```

## OUTPUT:
![image](https://github.com/SnehaBasyal/19AI307_JAVA/blob/b696a0be389efbe73652b3b617cf1f43ea336517/Module-08/DAY-2/Screenshot%202025-05-23%20203352.png)


## RESULT:
Thus, the java program to read the content from the file "test.txt" using Reader was executed and verified successfully



