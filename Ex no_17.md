# EX 17  C program to find whether a given year is a leap year or not using the else-if ladder
## DATE:
## AIM:
To write a C program to find whether a given year is a leap year or not using the else-if ladder

## Algorithm

1.Start the program and read the year value from the user.

2.Check if the year is divisible by 400; if true, it is a leap year.

3.Else, check if the year is divisible by 100; if true, it is not a leap year.

4.Else, check if the year is divisible by 4; if true, it is a leap year, otherwise not.

5.Display the result and stop the program.   

## Program:
```
#include <stdio.h>

int main() {
    int year;
    scanf("%d", &year);
    if (year % 400 == 0)
    {
        printf("%d is a leap year.\n", year);
    } 
    else if (year % 100 == 0)
    {
        printf("%d is not leap year\n", year);
    } 
    else if (year % 4 == 0) 
    {
        printf("%d is a leap year.\n", year);
    } 
    else
    {
        printf("%d is not leap year\n", year);
    }

    return 0;
}

```

## Output:

<img width="507" height="161" alt="Screenshot 2026-03-19 141507" src="https://github.com/user-attachments/assets/e672f62c-f5d1-4e1a-b018-192a0a29bd16" />



## Result:
Thus the program was executed and the output was verified successfully.
