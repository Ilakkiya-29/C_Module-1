# 1. Topic A: DATATYPES - OPERATORS

# Aim:
To understand different data types and operators in C.

# Procedure:
Declare variables of different data types (int, float, char).
Use arithmetic, relational, and logical operators on the variables.
Display the results using printf().

# Program:
```
#include <stdio.h>
int main() {
    int a = 5, b = 2;
    float x = 3.5, y = 2.0;
    char c = 'A';

    printf("Sum: %d\n", a+b);
    printf("Division: %.2f\n", x/y);
    printf("Character: %c\n", c);
    return 0;
}
```

# Output:

Sum: 7
Division: 1.75
Character: A

# Result:
The program demonstrates the use of different data types and operators.

# 2. Topic B: CONDITIONAL - STATEMENTS

# Aim:
To learn how to use conditional statements like if, if-else, and switch in C.

# Procedure:

Take input from the user.
Apply conditional checks using if-else or switch.
Display messages based on conditions.

# Program:
```
#include <stdio.h>
int main() {
    int num;
    scanf("%d", &num);

    if(num % 2 == 0)
        printf("Even\n");
    else
        printf("Odd\n");

    return 0;
}
```

# Output:

Input: 7
Odd

# Result:
The program correctly identifies even and odd numbers using conditional statements.

# 3. Topic C: OPERATORS - EXPRESSIONS

# Aim:
To evaluate expressions using different operators in C.

# Procedure:

Declare variables.
Write arithmetic and relational expressions.
Display the results.

# Program:
```
#include <stdio.h>
int main() {
    int a = 10, b = 5;
    printf("a + b = %d\n", a+b);
    printf("a > b = %d\n", a>b);
    return 0;
}
```

# Output:

a + b = 15
a > b = 1

# Result:
The program demonstrates the evaluation of expressions with different operators.

# 4. Topic D: USING CONDITIONAL STATEMENTS

# Aim:
To use conditional statements to solve problems based on input conditions.

# Procedure:

Take user input.
Use if-else or switch for decision making.
Display the corresponding output.

# Program:
```
#include <stdio.h>
int main() {
    int marks;
    scanf("%d", &marks);

    if(marks >= 50)
        printf("Pass\n");
    else
        printf("Fail\n");
    return 0;
}
```

# Output:

Input: 45
Fail

# Result:
The program correctly uses conditional statements to determine pass/fail.

# 5. Topic E: CALCULATING TOTAL, PERCENTAGE, AND DIVISION USING CONDITIONAL STATEMENTS

# Aim:
To calculate total marks, percentage, and assign grades using conditional statements.

# Procedure:

Take marks of subjects from the user.
Calculate total and percentage.
Use if-else to assign grades.
Display total, percentage, and grade.

# Program:
```
#include <stdio.h>
int main() {
    int m1, m2, m3;
    scanf("%d %d %d", &m1, &m2, &m3);

    int total = m1 + m2 + m3;
    float percentage = total / 3.0;

    printf("Total: %d\n", total);
    printf("Percentage: %.2f\n", percentage);

    if(percentage >= 75)
        printf("Grade: A\n");
    else if(percentage >= 50)
        printf("Grade: B\n");
    else
        printf("Grade: C\n");

    return 0;
}
```

# Output:

Input: 80 70 90
Total: 240
Percentage: 80.00
Grade: A

# Result:
The program calculates total, percentage, and assigns grades using conditional statements.
