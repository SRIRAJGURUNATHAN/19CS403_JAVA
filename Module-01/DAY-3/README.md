# Ex.No:1(C) CONTROL STATEMENTS

## AIM:
To develop a Java program to check given number is zero or not.

## ALGORITHM :
1.	Start the program.
2.	Declare an integer variable 'num'
3.	Create a Scanner object 'sc' to read input from the user
4.	Read an integer input from the user and store it in 'num'
5.	Check if 'num' is equal to 0:
a.	If true, print "Given number is Zero"
b.	If false, print 'num' followed by " is Non-Zero"
6.	End





## PROGRAM:
 ```
/*
Program to implement a class & objects using Java
Developed by: Melvin S
RegisterNumber:  212222040098
*/
```

## Sourcecode.java:

```java
import java.util.*;
public class Main{
    public static void main(String[] args)
    {
        Scanner input = new Scanner(System.in);
        int zero = input.nextInt();
        if(zero==0)
        {
            System.out.print("Given number is Zero");
        }
        else
        {
            System.out.print(zero+" is Non-Zero");
        }
    }
}
```

## OUTPUT:

![image](https://github.com/user-attachments/assets/2a06047c-9f29-436a-84d0-05116803ec88)


## RESULT:
Thus, the Java program to check given number is zero or not was created successfully.

