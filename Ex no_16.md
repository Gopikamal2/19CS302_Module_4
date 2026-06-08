# EX 16 C program to find minimum between three integer numbers using conditional operator.
## AIM:
To write a C program to find minimum between three integer numbers using conditional operator.

## Algorithm

1.Start the program and read three integer values num1, num2, and num3.

2.Use the conditional (ternary) operator to compare num1, num2, and num3.

3.Assign the smallest value to the variable min using the condition.

4.Display the minimum value among the three numbers.

5.Stop the program.   

## Program:
```
#include <stdio.h>
int main()
{
    int num1,num2,num3,min;
    scanf("%d%d%d%d",&num1,&num2,&num3,&min);
    min = (num1 < num2 && num1 < num3) ? num1 : (num2 < num3) ? num2 : num3;
    printf("Minimum between %d, %d and %d = %d", num1, num2, num3, min);
    return 0;
}
```

## Output:

<img width="514" height="117" alt="Screenshot 2026-03-19 141034" src="https://github.com/user-attachments/assets/423ae8a0-b155-4bec-bde8-7aabb88f5224" />


## Result:
Thus the program was executed and the output was verified successfully.
