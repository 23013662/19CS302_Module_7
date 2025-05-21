# EX 31 C program to find the smallest among three numbers using Structure.
## DATE:
## AIM:
To write a C program to find the smallest among three numbers using Structure.

## Algorithm
1.Start.

2.Define a variables a,b,c.

3.Write program to find the smallest among the three numbers.

4.Read the value using scanf.

5.Ask the user to make an input.

6.Print out the answer.

7.End   

## Program:
```
/*
C program to find the smallest among three numbers using Structure.
Developed by:santhiya c 
RegisterNumber:212223060247  
*/
#include<stdio.h> 
int main()
{
int a,b,c; 
scanf("%d%d%d",&a,&b,&c); 
if(a<b && a<c)
{
printf("%d is the smallest number.",a);
}
else if(b<a && b<c)
{
printf("%d is the smallest number.",b);
}
else
{
printf("%d is the smallest number.",c);
}
}

```

## Output:
![image](https://github.com/user-attachments/assets/00045fb2-fbc7-4770-96bc-4e2d0b1d86d6)



## Result:
Thus the program was executed and the output was verified successfully.
