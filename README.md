#**Experiment 8: Study of Loops in Python**

##*AIM*: ** To study and implement the use of for loops in Python for performing repetitive tasks, mathematical operations, matrix operations, and pattern generation** 

*THEORY*:

A for loop in Python is a control flow statement used to execute a block of code repeatedly for a fixed number of times. It is mainly used to iterate over sequences such as numbers, lists, strings, and matrices.

The range() function is commonly used with for loops. It generates a sequence of numbers in the following forms:

a. range(stop)

b. range(start, stop)

c. range(start, stop, step)

For loops help in:

a. Printing sequences of numbers

b. Performing repetitive mathematical calculations (like sum of N numbers)

c. Checking conditions (like prime numbers)

d. Working with nested loops for matrix operations

e. Generating patterns using strings

Nested for loops are used when working with two-dimensional data structures like matrices. In matrix multiplication, three nested loops are required to perform row-by-column multiplication.

Pattern printing programs demonstrate how loops can control repetition and formatting using string multiplication and spacing.

Thus, the for loop is an important programming construct that improves efficiency and reduces code repetition.

*ALGORITHM*:

*Program 1: Print numbers 1 to 5*

      Start
      Use range(1,6)
      Print each number inside the loop
      Display

*Program 2: Print all odd numbers between 1 to 10*

     Start
     Use range(1,11,2)
     Print each value
     Display Result
     
*Program 3: Sum of first N numbers*

     Start
     Input value of N
     Initialize sum = 0
     Iterate from 1 to N
     Add each number to sum
     Print sum
     Display
        
*Program 4: Display of 3x3 matrix*

    Start
    Define matrix A
    Use outer loop for rows
    Use inner loop for columns
    Print each element
    Display result

*Program 5: Multiplication of two 3x3 matirces*

    Start
    Define matrices A and B
    Initialize result matrix with zeros
    Use three nested loops
    Multiply and add corresponding elements
    Store result
    Print result

*Program 6: Print All prime numbers in a range*

    Start
    Iterate numbers from 2 to 50
    For each number, check divisibility
    If divisible, break
    Else print number
    Stop

           
*Program 7: Right angle triangle pattern*

    Start
    Run loop from 10 to 1
    Print "*" multiplied by loop value
    Stop

          
*Program 8: Pyramid Pattern*

    Start
    Set number of rows
    Loop from 1 to rows
    Print spaces and stars accordingly
    Stop      

*CONCLUSION:*

In this experiment, the concept of for loops in Python was successfully studied and implemented. Various programs were executed, including number printing, summation, matrix display, matrix multiplication, prime number generation, and pattern printing.
