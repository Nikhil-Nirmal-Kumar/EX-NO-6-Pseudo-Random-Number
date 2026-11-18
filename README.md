# EX-NO-6-Pseudo-Random-Number

# AIM: 
Implementation of Pseudorandom Number Generation Using Standard library

# ALGORITHM:
Start the program and import the required libraries.
Seed the random number generator using the current time(i.e) rand(time(0));
Get the number of randon number to generate.
Pass the value for number of iterations and print the numbers.
End the program.

# PROGRAM:
```
#include <stdio.h>
#include <stdlib.h>
#include <time.h>

int main() {
    int n, i;

    srand(time(0));

    printf("Enter the number of random numbers to generate: ");
    scanf("%d", &n);

    printf("\nGenerated pseudo-random numbers:\n");
    for (i = 0; i < n; i++) {
        printf("%d\n", rand());
    }

    return 0;
}
```
# OUTPUT:
<img width="766" height="292" alt="image" src="https://github.com/user-attachments/assets/a2026259-67a4-434b-83fb-f90e960fb1e2" />

# RESULT:
The program is executed successfully.
