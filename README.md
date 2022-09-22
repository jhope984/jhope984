# Homework Submission

|                               |Submission Information | 
|-------------------------------|-----------------------|
|**Name:**                      | Santosh Neupane       |
|**Student ID:**                |110700078              |                 
|**Class:**                     |  CSC 2312 Section 003 |
|**Homework:**                  |  #2                   |
|**Due Date:**                  |  Sep. 20, 2022        |

#  Program Description
1.First take input for initial balance and percent rate per year from the user.
2.Have to make initial balance greater than or equal to minimum withdrawl amount $420.
3.Then we have to calculate random withdrawl amount between $480 to $620 using rand function.
4.After that we have to calculate interest amount for initial balance at that time using equation  where A is interest amount, P is the principal amount and r and t are rate and time respectively.
5.Calculate new balance by subtracting withdrawl and adding interest in initial balance.
6.Printing the values then update initial balance equal to new balance.
7.End loop.
8.End Program.



# Source Files Description

## Name:  `main.cpp`
Main program.  This is the driver program that calls sub-functions
to read data from an input file, use the data to create two matrices,
and compute and display their sum and product.

## Name:  `xxx.h` 
   - if any
   Contains the definition for the class xxx.  

## Name: `xxx.cpp`
   Defines and implements the xxx class for implementing a xxx.
   This class provides routines to construct and get the xxx, ...

**... more to come**
   

#  Circumstances of programs
   - The program runs successfully.  
   - The program was developed and tested on gnu g++ 6.1.x  It was compiled, run, and tested on gcc csegrid server.

   - The program runs mostly correct except for requirement #4 that the program aborts when a negative number is introduced.


#  How to build and run the program
- Applies for CSEGrid programs

1. Decompress the homework.  The homework file is compressed.  
   - To decompress it use the following command 
      - `% unzip [1234HW1]`

   - The directory named `homework` should contain the following files:
   ```
      main.cpp
      xxx.h
      xxx.cpp
	   yyy.h
	   yyy.cpp
      makefile
      Readme.md
   ```
	[any other supporting documents]

2. Build the program.

- Change to the directory that contains the file by: 
   - `% cd [1234HW1]`
- Compile the program by: 
   - `% make`

3. Run the program by:
   - `% ./[xxx]`

4. Delete the obj files, executables, and core dump by
   - `% ./make clean`
