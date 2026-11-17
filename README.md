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

int main()
{
    int n, i;

    srand(time(0));

    printf("Enter the number of random numbers: ");
    scanf("%d", &n);

    for(i = 0; i < n; i++)
    {
        printf("%d\n", rand());
    }

    return 0;
}
```

# OUTPUT:
<img width="373" height="135" alt="image" src="https://github.com/user-attachments/assets/6c7c42d0-4700-4d00-bd36-5e268609fb41" />


# RESULT:
Thus the given program has been executed successfully
