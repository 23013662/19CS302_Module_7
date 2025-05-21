# EX 33 C program to read a file name from user and create that file using fopen().
## DATE:
## AIM:
To write a C program to read a file name from user and create that file using fopen().

## Algorithm
1.Start.

2.Define a variables.

3.Write a program to read a file name from user and create that file and insert student roll numbers in to that file.

4.Read the value using scanf.

5.Ask the user to make an input.

6.Print out the answer.

7.End.

## Program:
```
/*
C program to read a file name from user and create that file using fopen().
Developed by: 
RegisterNumber:  
*/
#include <stdio.h> 
int main()
{FILE *p;
char name[40]; 
scanf("%s",name);
p=fopen("name","w");
printf("%s File Created Successfully\n",name); 
printf("%s File Opened\n",name);
fclose(p);
printf("%s File Closed",name);
}
```

## Output:
![image](https://github.com/user-attachments/assets/8bb195d1-8067-4bfa-ac3a-7f0b30c6a3ae)



## Result:
Thus the program was executed and the output was verified successfully.
