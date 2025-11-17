# Ex.No:1(C) LOOPING STATEMENT

## QUESTION:Write a Java program to reverse a number using a while loop. For example, if the input is 1234, the output should be 4321


## AIM:
To Write a Java program to reverse a number using a while loop. For example, if the input is 1234, the output should be 4321

## ALGORITHM :
1.	Start the program.
2.	Import the necessary package 'java.util'
3.	





## PROGRAM:
 ```
/*
Program to implement a Looping Statement using Java
Developed by: SANJAYKUMAR N B
RegisterNumber:  212223230189
*/
```

## SOURCE CODE:
```
import java.util.*;
class prog{
    public static void main(String args[]){
        Scanner ip=new Scanner(System.in);
        int a =ip.nextInt();
        int rev=0;
        while(a>0){
            int rem = a%10;
            rev=(rev*10)+rem;
            a/=10;
            
        }
        System.out.println("Reversed number: "+rev);
    }
}
```
## OUTPUT:


## RESULT:
Thus the java program is executed successfully.
