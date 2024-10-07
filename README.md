# Pseudo-Random-Number-Generation

### AIM:
Implementation of Pseudorandom Number Generation Using Standard library

### ALGORITHM:
Start the program and import the required libraries.
Seed the random number generator using the current time (i.e) rand(time(0));
Get the number of random numbers to generate.
Pass the value for number of iterations and print the numbers.
End the program.
### PROGRAM:
#### NAME: KOUSALYA A.
#### Register Number: 212222230068
```
#include <stdio.h>
#include <stdlib.h>
#include <time.h>

int main() 
{
    int count, min, max;
    printf("Enter the number of random numbers to generate: ");
    scanf("%d", &count);
    printf("Enter the minimum value: ");
    
    scanf("%d", &min);
    printf("Enter the maximum value: ");
    scanf("%d", &max);
    srand(time(NULL));
    printf("Pseudorandom numbers:\n");   
    for (int i = 0; i < count; i++) 
    {
        int random_number = (rand() % (max - min + 1)) + min;
        printf("%d\n", random_number);
    }
    return 0;
}
```
### OUTPUT:
![Screenshot (1)](https://github.com/user-attachments/assets/4d25a7c2-9c2d-405c-b2b1-3d78b1ec04ab)

### RESULT:
The Implementation of Pseudorandom Number Generation Using Standard library is successful.
