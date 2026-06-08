# EX 20 C program to convert a string from uppercase to lowercase without using string function .
## DATE:
## AIM:
To write a C program to convert a string from uppercase to lowercase without using string function .

## Algorithm

1.Start the program and read a string from the user.

2.Initialize an index variable i = 0.

3.Traverse the string using a loop until the null character '\0' is reached.

4.For each character, check if it is uppercase ('A' to 'Z'); if true, convert it to lowercase by adding 32.

5.Display the converted string and stop the program.   

## Program:
```
#include <stdio.h>

int main() {
    char str[100];
    int i = 0;

   
    scanf(" %[^\n]", str); 

   
    while (str[i] != '\0') {
        if (str[i] >= 'A' && str[i] <= 'Z') { 
            str[i] = str[i] + 32; // Convert to lowercase
        }
        i++;
    }

    printf("%s\n", str);

    return 0;
}

```

## Output:

<img width="636" height="137" alt="Screenshot 2026-03-19 143215" src="https://github.com/user-attachments/assets/ffc9fa64-dcb7-4f56-87f5-8e161aaecff5" />


## Result:
Thus the program was executed and the output was verified successfully.
