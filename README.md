# NAME: Shanmuga Priya.K
# REGISTER NO: 25004352

# EXPNO: 2a) C PROGRAM TO PRINT THE STRING "PLACEMENT" N NUMBER OF TIMES.
# AIM:
To write a C program to print the string "PLACEMENT" n number of times.

# ALGORITHM:
1. Take the input from the user using scanf function.
2. Use for loop to print the string n number of times.
3. Print the string using printf function.

# PROGRAM: 
```
#include<stdio.h>
int main()
{
  int N;
  scanf("%d",&N);
  for(int i=0;i<N;i++)
    printf("PLACEMENT\n");
  return 0;
}
```
# OUTPUT:
![alt text](<Screenshot 2025-10-20 121240.png>)

# RESULT:
Thus, the program is verified successfully.

# EXPNO: 2b) C PROGRAM TO PRINT THE TRIANGULAR STAR PATTERN USINF LOOP.
*
**
***
****
*****
# AIM:
To write a C program to print the triangular star pattern using loop.

# ALGORITHM:
1. Take the input from the user using scanf function.
2. Use for loop to print the pattern the input number of times.
3. Print the pattern using printf function.

# PROGRAM: 
```
#include<math.h>
int main()
{
  int row,col,num=5;
  scanf("%d",&num);
  for(row=1;row<=num;row++)
  {
    for(col=1;col<=row;col++)
    {
      printf("*");
    }
    printf("\n");
  }
return 0;
}
```
# OUTPUT:
![alt text](<Screenshot 2025-10-20 121748.png>)

# RESULT:
Thus, the program is verified successfully.

# EXPNO: 2c) C PROGRAM TO PERFORM MULTIPLICATION AND DIVISION OF A AND B VALUES USING FUNCTIONS.

# AIM:
To write a C program to perform multiplication and division of a and b values using functions.

# ALGORITHM:
1. Declare two functions for multiplication and division with return types.
2. Take the input from the user using scanf function.
3. Inside main() function, call the functions.
4. Print the values using printf function.

# PROGRAM: 
```
#include<stdio.h>
#include<math.h>
int Multiplication(int a,int b)
{
    return a*b;
}
int Division(int a,int b)
{
    return a/b;
}
int main()
{
    int a,b;
    scanf("%d\n%d",&a,&b);
    printf("Multiplication: %d\n",Multiplication(a,b));
    printf("Division: %d",Division(a,b));
    return 0;
}
```
# OUTPUT:
![alt text](<Screenshot 2025-10-20 122421.png>)

# RESULT:
Thus, the program is verified successfully.

# EXPNO: 2d) C PROGRAM TO FIND THE SUM OF DIGITS USING FOR LOOP.

# AIM:
To write a C program to find the sum of digits using for loop.

# ALGORITHM:
1. Take the input from the user using scanf function.
2. Declare sum=0.
3. Using for loop, write the formula for sum calculation.
4. Print the value using printf function.

# PROGRAM: 
```
#include<stdio.h>
#include<math.h>
int main()
{
    int num,sum=0;
    scanf("%d",&num);
    for(;num>0;num=num/10)
    {
        sum=sum+num-(num/10)*10;
    }
    printf("%d",sum);
    return 0;
}
```
# OUTPUT:
![alt text](<Screenshot 2025-10-20 124240.png>)

# RESULT:
Thus, the program is verified successfully.


# EXPNO: 2e) C PROGRAM TO DISPLAY THE VALUE USING AUTO STORAGE CLASS WITHOUT USING LOOPING STATEMENTS.

# AIM:
To write a C program to display the value using auto storage class without using looping statements.

# ALGORITHM:
1. Delcare a void function and arguments with return types.
2. Declare the auto sorage class variable inside the function.
3. In main() function, take the inputs from the user using scanf function.
4. Call the function.

# PROGRAM: 
```
#include <stdio.h>
#include<math.h>
void display(int a,int b,int c)
{
    auto int j;
    j=c; printf("j=%d     ",j);
    j=b; printf("j=%d\n",j);
    j=a; printf("j=%d\n",j);
}
int main()
{
    int num1,num2,num3;
    scanf("%d %d %d",&num1,&num2,&num3);
    display(num1,num2,num3);
    return 0;
}
```
# OUTPUT:
![alt text](<Screenshot 2025-10-20 125125.png>)

# RESULT:
Thus, the program is verified successfully.




