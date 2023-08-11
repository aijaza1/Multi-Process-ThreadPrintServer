# Multi-Process-ThreadPrintServer

Created a C program that simulates a producer-consumer problem using processes and threads. The goal of this problem is to demonstrate the concept of synchronization and mutual exclusion using semaphores to coordinate the activities of multiple producers and consumers operating on a shared buffer.

This code simulates a system where multiple producers generate printer jobs and place them in a shared buffer, while multiple consumer threads retrieve and process these jobs. The code uses semaphores to control access to the shared resources and synchronize the activities of producers and consumers.

It's worth noting that the code includes proper synchronization mechanisms using semaphores to ensure that producers and consumers do not access shared resources simultaneously and that the critical sections of the code are protected. The termination handler ensures that semaphores are destroyed, threads are canceled, and shared memory is detached and removed properly upon program termination.
