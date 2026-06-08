# EX 18 C program to  count the frequency of each character in a string  using for loop.
## DATE:
## AIM:
To write a C program to  count the frequency of each character in a string  using for loop.

## Algorithm

1.Start the program and read a string from the user.

2.Initialize an array freq[256] to store the frequency of each character as 0.

3.Traverse the string using a for loop and increment the count of each character in the freq array.

4.Traverse the string again and print each character along with its frequency, ensuring duplicates are not printed again.

5.Stop the program.   

## Program:
```
/*
#include <stdio.h>


void countCharacterFrequency(char str[]) {
    int freq[256] = {0};
    int i;
    
 
    for (i = 0; str[i] != '\0'; i++) {
        freq[(unsigned char)str[i]]++;
    }
    
    printf("frequency count:\n"); 
    for (i = 0; str[i] != '\0'; i++) {
        if (freq[(unsigned char)str[i]] > 0) {
            printf(" '%c' = %d\n", str[i], freq[(unsigned char)str[i]]);
            freq[(unsigned char)str[i]] = 0; 
        }
    }
}

int main() {
    char s1[100];
    int i;
    char ch;
    i = 0;
    while ((ch = getchar()) != '\n' && i < 99) {
        s1[i] = ch;
        i++;
    }
    s1[i] = '\0';
    countCharacterFrequency(s1);
    
    return 0;
}

```

## Output:

<img width="493" height="339" alt="Screenshot 2026-03-19 141951" src="https://github.com/user-attachments/assets/bbd3496b-ad97-446d-bd5a-e744cda39483" />


## Result:
Thus the program was executed and the output was verified successfully.
