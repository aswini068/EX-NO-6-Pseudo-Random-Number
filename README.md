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
#include <me.h> 
 
int main() { 
    int n, i; 
 
    printf ("Enter how many random numbers to generate: "); 
    scanf("%d", &n); 
 
    srand( me(0));  
 
    printf ("Generated Random Numbers:\n"); 
    for (i = 0; i < n; i++) { 
        printf ("%d\n", rand()); 
    } 
 
    return 0; 
} 
```
# OUTPUT:
<img width="633" height="347" alt="image" src="https://github.com/user-attachments/assets/9bfb3eb7-baf3-47cd-936f-b36f60550712" />

# RESULT:
Thus the progeram for generating psuedo random number is successfully executed.
