<h1 align="center"> C Programming</h1>

# Introduction To C Programming.
## What is C Programing
  - C is a programming language developed at AT & T’s Bell Laboratories of USA in 1972 by Dennis Ritchie.
  - C is case sensitive
  - Variable must be declared before it is used in the program.
  - File should be have the extension .c

## History of C Language

Language |	Year	| Developed By
-------- | ------ | ------------
Algol |	1960 |	International Group
BCPL |	1967 |	Martin Richard
B	| 1970 |	Ken Thompson
Traditional C	| 1972 |	Dennis Ritchie
K & R C	| 1978	| Kernighan & Dennis Ritchie
ANSI C	| 1989 |	ANSI Committee
ANSI/ISO C	| 1990	| ISO Committee
C99 |	1999 |	Standardization Committee

## Features of C Language
  - Mid-level programming language
  - c is a reusable
  - Memory Management
  - Machine Independent or Portable
  - structured programming language
  - it is mmodular

    ***Any programming Language can be divided in to two categories.***
      - Problem oriented (High level language)
      - Machine oriented (Low level language)
      - **But C is considered as a Middle level Language.**

## C as a mid-level programming language
   - C is considered as a middle-level language because it supports the feature of both low-level and high-level languages. C language program is converted into assembly code, it supports pointer arithmetic (low-level), but it is machine independent (a feature of high-level).

## Low level language
  - Low level languages are machine level and assembly level language. 
  - In machine level language computer only understand digital numbers 
    > i.e. in the form of 0 and 1.
    - ** assembly language ** is on other hand modified version of machine level language. Where instructions are given in English like word as ADD, SUM, MOV etc. It is easy to write and understand but not understand by the machine.

##  High-Level language
  - These languages are machine independent, means it is portable.

### Memory Management
  - It supports the feature of dynamic memory allocation. In C language, we can free the allocated memory at any time by calling the free() function.

## First C Program

 ```                
                      #include <stdio.h>    
                      int main(){    
                      printf("Hello C Language");    
                      return 0;   
                      }
                      
                       ***OR***
                       
                      #include <stdio.h>    
                      void main(){    
                      printf("Hello C Language");    
                      getch();   
                      }  
```
  - `#include <stdio.h>` includes the standard input output library functions.
  - `int main()` or `void main()` The main() function is the entry point of every program in c language.
  - `printf()` The printf() function is used to print data on the console.
  - `return 0` The return 0 statement, returns execution status to the OS. The 0 value is used for successful execution and 1 for unsuccessful execution.
  - ` getch() `is a predefined non-standard function that is defined in conio.h header file. It is mostly used by the Dev C/C++, MS- DOS's compilers like Turbo C to    hold the screen until the user passes a single value to exit from the console screen.
## Editors installation
## Process of Run or Execute C program

## printf() and scanf() in C

  - The printf() and scanf() functions are used for input and output in C language. Both functions are inbuilt library functions, defined in stdio.h (header file).
  ### printf() function
  - The printf() function is used for output. It prints the given statement to the console.

    **The syntax of printf() function is given below:**
    > printf("format string",argument_list);  
  - The format string can be %d (integer), %c (character), %s (string), %f (float) etc.
  ```                     
                      #include <stdio.h>    
                      void main(){    
                      printf("Welcome to My World");    
                      getch(); 
                      }
                      
```
  #### Output
   >   Welcome to My World
 ### scanf() function
  - The scanf() function is used for input. It reads the input data from the console.
    > scanf("format string",argument_list);  
```                              
                            #include<stdio.h>    
                            void main(){    
                            int number;    
                            printf("Enter a Number:");    
                            scanf("%d",&number);    
                            printf("Your Entered Number is:%d ",number);    
                            getch();  
                            }     

```
#### Output
 >          Enter a Number:3
 >          Your Enter Number is: 3
 
 
 
 
 
