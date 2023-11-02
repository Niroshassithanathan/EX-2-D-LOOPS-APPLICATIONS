# EX-2-D-LOOPS-APPLICATIONS
## AIM :
Write a c program to find the sum of odd digits using do while loop.
## ALGORITHAM :
1.Start

2.Declare variables to store the input number (num) and the sum of odd digits (sum).

3.Prompt the user to enter an integer number.

4.Read the number (num) from the user.

5.Initialize the sum to 0 (sum = 0).

6.Use a loop to extract each digit from the number until it becomes 0:

7.Print the sum of the odd digits.

8.End.
## PROGRAM :
```
#include<stdio.h>
int main(){
int a,b=0;
do {
scanf("%d",&a);
if(a%2==1)
{
b=b+a;
}
a--;
}while(a!=0);
printf("%d",b);
return 0;
}
```
## OUTPUT :
![image](https://github.com/Niroshassithanathan/EX-2-D-LOOPS-APPLICATIONS/assets/121418437/6ec5a1e8-f851-40db-bd77-4b0d70e053cf)
## RESULT :
Thus , The C program has been executed successfully.
