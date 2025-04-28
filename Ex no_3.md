# EX 3 C program to find number of years based on principle,rate & simple interest.
## DATE: 28-04-2025
## AIM:
To write a C program to find number of years based on principle,rate & simple interest.

## Algorithm
1. Start.
2. Declare variables: principal, rate, simple_interest, and years.
3. Prompt the user to enter the value of Principal.
4. Read the value of Principal.
5. Prompt the user to enter the value of Rate.
6. Read the value of Rate.
7. Prompt the user to enter the value of Simple Interest.
8. Read the value of Simple Interest.
9. Calculate the number of years using the formula:
          years = (Simple Interest × 100) / (Principal × Rate)
​10. Display the calculated number of years.
11. End.

## Program:
```
#include <stdio.h>
int main()
{
    float principal, rate, simple_interest, years;
    printf("Enter Principal: ");
    scanf("%f", &principal);

    printf("Enter Rate: ");
    scanf("%f", &rate);

    printf("Enter Simple Interest: ");
    scanf("%f", &simple_interest);

    years = (simple_interest * 100) / (principal * rate);
    printf("Number of years = %.2f\n", years);
    return 0;
}

```

## Output:
Enter Principal: 1000
Enter Rate: 5
Enter Simple Interest: 250
Number of years = 5.00

## Result:
Thus the program was executed and the output was verified successfully.
