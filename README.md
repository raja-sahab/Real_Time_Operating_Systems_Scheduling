# Scheduling of Real Time Tasks

## What I have done

* Developed a real-time application with four periodic tasks with priorities assigned to each task using a priority-based scheduling algorithm. Tasks had periods of 80ms, 100ms, 200ms, and 160ms.
* Implemented inter-task communication using three global variables and semaphores with priority ceiling to protect critical sections of code. Task1 writes to T1T2 and T1T4, while Task2 writes to T2T3, and Task3 and Task4 read from these global variables.
* Successfully executed the application to demonstrate efficient task synchronization and communication using semaphores and priority ceiling protection.

## How to Run

To build and run the code in this repository, follow these steps:

* Clone the repository in a new workspace and navigate to its directory.
* In the terminal, enter the following command to become a superuser: $ sudo su
* Build the code using the following command: $ g++ Assignment1.cpp -lpthread -o Ceiling
* This will create an executable file named "Ceiling". To run the program, enter the following command: $ ./Ceiling
* The program will begin by performing a scheduling test of tasks using rate monotonic analysis. If the tasks are schedulable, the program will schedule them using priority ceiling protocol.

