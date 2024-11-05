# C-Programming Past Papers solution

## WAP in C language to find simple interest where user need to input principle, rate and time. 

```c
#include <stdio.h>
#include <conio.h>

int main() {
    int principle, rate, time;
    float simple_interest;

    printf("Enter principle: ");
    scanf("%d", &principle);
    printf("Enter rate: ");
    scanf("%d", &rate);
    printf("Enter time: ");
    scanf("%d", &time);

    simple_interest = (principle * rate * time) / 100.0;
    printf("Simple Interest: %f\n", simple_interest); // You can use %.2f for 2 decimal places.

    getch();
    return 0;
}
```
<hr>

## WAP in C language to display the series with sum:<br>
`1 2 3 4 ...` upto 10<sup>th</sup> term.
```c
#include <stdio.h>
#include <conio.h>

int main() {
    int i, sum = 0;

    for (i = 1; i <= 10; i++) {
        printf("%d ", i);
        sum += i;
    }
    printf("\nSum: %d\n", sum);

    getch();
    return 0;
}
```
<hr>

## WAP in C-language that asks any two numbers and displays the greatest among them.
```c
#include <stdio.h>
#include <conio.h>

int main() {
    int num1, num2;

    printf("Enter first number: ");
    scanf("%d", &num1);
    printf("Enter second number: ");
    scanf("%d", &num2);

    if (num1 > num2) {
        printf("Greatest: %d\n", num1);
    } else if (num1 < num2) {
        printf("Greatest: %d\n", num2);
    } else {
        printf("Both numbers are equal.\n");
    }

    getch();
    return 0;
}
```
<hr>

## WAP that asks a number and checks whether it is negative, positive or zero.
```c
#include <stdio.h>
#include <conio.h>

int main() {
    int number;

    printf("Enter a number: ");
    scanf("%d", &number);

    if (number > 0) {
        printf("Positive\n");
    } else if (number < 0) {
        printf("Negative\n");
    } else {
        printf("Zero\n");
    }

    getch();
    return 0;
}
```
<hr>

## WAP in C-language to display first 10 odd numbers.
```c
#include <stdio.h>
#include <conio.h>

int main() {
    int i, num = 1;

    for (i = 0; i < 10; i++) {
        printf("%d ", num);
        num += 2;
    }
    printf("\n");

    getch();
    return 0;
}
```
<hr>

## WAP in C-language to calculate the sum of the following series:<br>
`1 3 5 ... ` to 10<sup>th</sup> term.
```c
#include <stdio.h>
#include <conio.h>

int main() {
    int i, num = 1, sum = 0;

    for (i = 0; i < 10; i++) {
        printf("%d ", num); //optional
        sum += num;
        num += 2;
    }
    printf("\nSum: %d\n", sum);

    getch();
    return 0;
}
```

<hr>

## WAP in C-language to display first 10 natural numbers.
```c
#include <stdio.h>
#include <conio.h>

int main() {
    int i;

    for (i = 1; i <= 10; i++) {
        printf("%d ", i);
    }
    printf("\n");

    getch();
    return 0;
}
```
<hr>

## WAP in C-language to calculate sum of odd numbers from 80 to 90.
```c
#include <stdio.h>
#include <conio.h>

int main() {
    int i, sum = 0;

    for (i = 81; i <= 89; i += 2) {
        printf("%d ", i);
        sum += i;
    }
    printf("\nSum: %d\n", sum);

    getch();
    return 0;
}
```
<hr>

## WAP in C-language that asks any three numbers and displays the greatest among them.
```c
#include <stdio.h>
#include <conio.h>

int main() {
    int num1, num2, num3;

    printf("Enter first number: ");
    scanf("%d", &num1);
    printf("Enter second number: ");
    scanf("%d", &num2);
    printf("Enter third number: ");
    scanf("%d", &num3);

    if (num1 > num2 && num1 > num3) {
        printf("Greatest: %d\n", num1);
    } else if (num2 > num1 && num2 > num3) {
        printf("Greatest: %d\n", num2);
    } else {
        printf("Greatest: %d\n", num3);
    }

    getch();
    return 0;
}
```
> Assuming no two numbers are equal

<hr>

## WAP in C-language that asks user to enter any number and and check whether the number is odd or even.
```c
#include <stdio.h>
#include <conio.h>

int main() {
    int number;

    printf("Enter an integer: ");
    scanf("%d", &number);

    if (number % 2 == 0) {
        printf("%d is even.\n", number);
    } else {
        printf("%d is odd.\n", number);
    }

    getch();
    return 0;
}
```
<hr>

## WAP in C-language that asks user to enter total number of days and convert it to year, month and week.
```c
#include <stdio.h>
#include <conio.h>

int main() {
    int days, years, months, weeks;

    printf("Enter total number of days: ");
    scanf("%d", &days);

    years = days / 365;
    days %= 365;
    months = days / 30;
    days %= 30;
    weeks = days / 7;
    days %= 7;

    printf("Years: %d, Months: %d, Weeks: %d\n", years, months, weeks);

    getch();
    return 0;
}
```
<hr>

## WAP in C-language that asks user to enter a number and check whether it is divisible by 5 or not.
```c
#include <stdio.h>
#include <conio.h>

int main() {
    int number;

    printf("Enter a number: ");
    scanf("%d", &number);

    if (number % 5 == 0) {
        printf("%d is divisible by 5.\n", number);
    } else {
        printf("%d is not divisible by 5.\n", number);
    }

    getch();
    return 0;
}
```
<hr>