# CSC2002S 2023
## ASSIGNMENT 2 PCP
## MULTITHREADED CONCURRENT CLUB SIMULATION

OBJECTIVE - In this assignment, your objective is to correct and extend the existing code for a multithreaded Java simulation of patrons in a club. Utilize synchronization mechanisms to ensure that the simulation adheres to specified synchronization constraints and maintains safety and liveness.

STEPS TO RUN PROGRAM - 
* ```make```: This compiles the program and creates the class files.
* ```make run```: This will compile and run the prgram.
* ```make clean```: This will clean the bin folder by removing the class files.

## PARAMETERS FOR INPUT ( 4 PARAMETERS)
* noClubgoers: This is the total amount of patrons in the club.
* gridX: This is the number of X grid cells.
* gridY: This is the number of of Y grid cells.
* max: This is the maximum amount of people that are allowed in club

## RUNNING THE PROGRAM USING ARGUMENTS
```bash
$ make run ARGS = "<noClubgoers> <gridX> <gridY> <max>"
```

