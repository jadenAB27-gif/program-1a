# program-1a
C module 1

EX NO-1)a)-Finding whether  a given character is alphabet or not.

Date: 26/03/26
Name: JADEN SAMUEL ABRAHAM
Ref no: 25003451

AIM:
Write a C program to find whether the given character is alphabet or not.

ALGORITHM:
1)Get input from the user.
2)Find whether the input is alphabet or not using isalpha() function.
3)Use if else statement to print the result.

PROGRAM:
```
#include <stdio.h>
#include <ctype.h>
int main()
{
    char ch;
    scanf("%c",&ch);
    if(isalpha(ch))
    printf("It is ALPHABET");
    else
    printf("It is NOT ALPHABET");
}
```
OUTPUT:
<img width="529" height="317" alt="Screenshot 2025-10-19 191132" src="https://github.com/user-attachments/assets/8651e0b0-bd18-4767-a91c-9ba9579712df" />

RESULT:
Thus the program to find whether the given character is alphabet or not is executed successfully.



