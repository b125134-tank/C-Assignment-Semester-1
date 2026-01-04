# C-Assignment-Semester-1
Assignsments for the first semester for the subject Introduction to programming
TABLE OF CONTENTS:
Assignment-1
Assignment-2
Assignment-3
Assignment-4
ASSINGMENT-1 — Print name without a semicolon
A small C program that prints a heading and a name using printf() inside an if statement so that the printf call does not require a trailing semicolon.
#include<stdio.h>

//----- ASSINGMENT-1 -----------
//Printing name without Semicolon
int main()
{

    if(printf("ASSINGMENT-1 \nTanishq")){}
    return 0;
}

How it works
printf() returns the number of characters printed (an integer > 0 when it prints something).
The program uses if(printf(...)) {}. Because the return value is non-zero, the if condition is true — the printf call itself is written inside the if parentheses, so that call does not need a trailing semicolon.
The if has an empty block ({}) and the program then returns 0.
This is a common trick used in C puzzles to print output "without using a semicolon" for the printf statement itself.

Expected output
ASSINGMENT-1 
Tanishq
