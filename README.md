# Homework Submission

|                               |Submission Information | 
|-------------------------------|-----------------------|
|**Name:**                      | Santosh Neupane       |
|**Student ID:**                |110700078              |                 
|**Class:**                     |  CSC 2312 Section 003 |
|**Homework:**                  |  #1                   |
|**Due Date:**                  |  Sep. 09, 2022        |



#  Program Description
1.This program recommends the user what activity to do in a certain day of the week.
2.First it ask the user's name followed by weather condition and it ask for to enter the integer for the day starting at 0 for sunday.
3.It then takes the input from the user and then recommends the activity to do on particular day.
4. It uses while loop to get the correct input from the user. Loop continues until user enter right input. 
5. It also uses If else statement to determine what to assign on activity on the particular day as the user's input.  

# Source Files Description

## Name:  `main.cpp`
Main program.  This is the driver program. It helps to recommend the user to choose the activity to do in the certain day entered by use according to 
weather condition.

## Name: makefile.txt
   - It mainly helps to execute the file in csegrid.

#  Circumstances of programs
   - The program runs successfully.  
   - The program was developed and tested on gnu g++ 6.1.x  It was compiled, run, and tested on gcc csegrid server.
   - 
#  How to build and run the program
- Applies for CSEGrid programs

1. Decompress the homework.  The homework file is compressed.  
   - To decompress it use the following command 
      - `% unzip [1234HW1]`

   - The directory named `homework` should contain the following files:
   ```
      main.cpp
      
      makefile
      Readme.md
   

2. Build the program.
- Change to the directory that contains the file by: 
   - `% cd [hwk1]`
- Compile the program by: 
   - `% make`

3. Run the program by:
   - `% ./homework1`

4. Delete the obj files, executables, and core dump by
   - `% ./make clean`
