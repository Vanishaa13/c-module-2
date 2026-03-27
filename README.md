# c-module-2

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
<img width="1093" height="267" alt="image" src="https://github.com/user-attachments/assets/83844d38-6bb4-4ebf-b02d-949c3ec6908c" />

# RESULT:
Thus, the program is verified successfully.

# EXPNO: 2b) C PROGRAM TO PRINT THE TRIANGULAR STAR PATTERN USINF LOOP.

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
<img width="1102" height="344" alt="image" src="https://github.com/user-attachments/assets/1dc5c348-1ef1-47a9-8f22-b6f3dfbd2068" />

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
<img width="1103" height="270" alt="image" src="https://github.com/user-attachments/assets/1309bef5-4ca0-4f5c-a754-d0aa5de26263" />

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
<img width="1097" height="303" alt="image" src="https://github.com/user-attachments/assets/f8df7c76-2bd5-491b-80b9-0884fbd312ca" />

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
<img width="1077" height="270" alt="image" src="https://github.com/user-attachments/assets/faf6f00b-aaf1-4cd5-ac0b-775afa34997f" />

# RESULT:
Thus, the program is verified successfully.
