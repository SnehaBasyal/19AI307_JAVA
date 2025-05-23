# Ex.No:8(C)             FILTER READER
## AIM:
 To create a java Program using FilterReader to read the content from the file.


## ALGORITHM :

1. Start
2. Extend `FilterReader` to create `CustomFilterReader1`
3. Call superclass constructor with `Reader` input
4. Override `read()` method
5. Read a character using `super.read()`
6. If character is a space `' '`, return `'/'` instead
7. Else, return the original character
8. End


## PROGRAM:

Program to implement a Filter Reader using Java

Developed by: Sneha Basyal M

RegisterNumber: 212222240101  


## Sourcecode.java:
```
class CustomFilterReader1 extends FilterReader
{  
    CustomFilterReader1(Reader in)
    {  
        super(in);  
    }  
    public int read() throws IOException
   {  
        int x = super.read();  
        if ((char) x == ' ')  
            return ((int) '/');  
        else  
            return x;  
    }  
}  

```

## OUTPUT:
![image](https://github.com/user-attachments/assets/890afe18-0238-40e3-8556-e61a71b4c285)



## RESULT:
Thus the java Program to read the content from the file by using Filter Reader was executed and verified successfully.









