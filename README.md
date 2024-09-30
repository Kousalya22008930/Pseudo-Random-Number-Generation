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
#### NAME: DHARINI PV
#### Register Number: 212222240024
```
#include <stdio.h>
#include <stdlib.h>  
#include <time.h>    
int main() {
    int n, i;
    
    srand(time(0));
    printf("Enter the number of pseudorandom numbers to generate: ");
    scanf("%d", &n);
    printf("Pseudorandom numbers:\n");
    for (i = 0; i < n; i++) {
        int random_number = rand(); // Generate a random number
        printf("%d\n", random_number);
    }
    return 0;
}
```
### OUTPUT:
![image](https://github.com/user-attachments/assets/7cdd8799-c3ff-4720-99a3-5cdf77e3a0fd)

### RESULT:
The Implementation of Pseudorandom Number Generation Using Standard library is successful.
