# C program to check whether the given input is an alphabet or not using conditional operator
## AIM:
To Write a C program to check whether the given input is an alphabet or not using conditional operator.
## ALGORITM:
1. Include the standard input-output header file.
2. Define the main function.
3. Declare a variable to store the input character.
4. Prompt the user to enter a character and read the input.
5. Use the conditional operator to Check if the character is between 'a' and 'z' or between 'A' and 'Z'.
6. If true, print that the character is an alphabet.
7. Otherwise, print that the character is not an alphabet.
## PROGRAM:
```
#include <stdio.h>
int main()
{
    char c;
    scanf("%c",&c);
    
    if (c>='a'&&c<='z')
    
    {
        printf("It is ALPHABET");
    }
    else if(c>='A'&&c<='Z')
    {
        printf("It is ALPHABET");
    }
    else
    {
        printf("It is NOT ALPHABET");
    }
    return 0;
}
```
## OUTPUT:
![image](https://github.com/VerginJenifer/c-programming-14/assets/136251012/f45f4534-93c3-4237-bc65-65c6bbe4c5bd)

## RESULT:
Thus, a C program to check whether the given input is an alphabet or not using conditional operator was executed successfully.
