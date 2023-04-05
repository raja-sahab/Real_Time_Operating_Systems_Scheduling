# Scheduling of Real Time Tasks

##What I have done

Developed a real-time application with four periodic tasks with priorities assigned to each task using a priority-based scheduling algorithm. Tasks had periods of 80ms, 100ms, 200ms, and 160ms.

Implemented inter-task communication using three global variables and semaphores with priority ceiling to protect critical sections of code. Task1 writes to T1T2 and T1T4, while Task2 writes to T2T3, and Task3 and Task4 read from these global variables.

Successfully executed the application to demonstrate efficient task synchronization and communication using semaphores and priority ceiling protection.

##How to Run

