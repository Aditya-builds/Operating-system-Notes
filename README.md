what about this Operating Systems Syllabus
1. Basics
Introduction of Operating System
Types of Operating Systems
Functions of Operating System
Real-Time Systems
Tasks in Real-Time Systems
Difference Between Multitasking, Multithreading, and Multiprocessing
Types of Computer Memory (RAM and ROM)
Difference Between 32-bit and 64-bit Operating Systems
What Happens When We Turn On a Computer?
Boot Block
UEFI (Unified Extensible Firmware Interface) and its Difference from BIOS
2. System Structure
Microkernel
Kernel I/O Subsystem (I/O System)
Monolithic Kernel and Key Differences from Microkernel
Introduction to System Call
Get/Set Process Resource Limits in C
Dual-Mode Operations in OS
Privileged and Non-Privileged Instructions
3. CPU Scheduling
Process (Introduction and Different States)
Process Table and Process Control Block (PCB)
Process Scheduler
CPU Scheduling (Preemptive and Non-Preemptive Scheduling)
Measure Time Spent in Context Switch
Difference Between Dispatcher and Scheduler
FCFS Scheduling:
Set 1, Set 2, and Convoy Effect
Shortest Job First (SJF) Scheduling:
Non-Preemptive (Set 1)
Preemptive (Set 2)
With Predicted Burst Time
Longest Remaining Time First (LRTF) Algorithm & Program
Round Robin Scheduling:
Selfish Round Robin Scheduling
With Different Arrival Times
Priority Scheduling:
Preemptive Priority Scheduling
With Different Arrival Times (Set 2)
Starvation and Aging
Highest Response Ratio Next (HRRN) Scheduling
Multilevel Queue and Multilevel Feedback Queue Scheduling
Lottery Process Scheduling
Multiple-Processor Scheduling
4. Process Synchronization
Process Synchronization (Introduction and Critical Section)
Interprocess Communication (IPC):
Methods, Shared Memory, Message Queues
Message-Based Communication in IPC
Signals in C
Semaphores:
Mutex vs. Semaphore, Monitors
Peterson’s Algorithm (Basic C Implementation, CPU Cycles & Memory Fence)
Dekker’s and Bakery Algorithms
Classic Problems:
Producer-Consumer Problem Using Semaphores
Dining Philosophers (Semaphores and Monitors)
Readers-Writers Problem (Introduction and Readers Preference Solution)
Sleeping Barber Problem
Priority Inversion and Inheritance
5. Deadlock
Deadlock (Introduction, Detection, and Recovery)
Deadlock, Starvation, and Livelock
Deadlock Prevention and Avoidance
Banker’s Algorithm & Resource Allocation Graph (RAG)
Deadlock Detection in Distributed Systems
6. Processes & Threads
Threads (Types, User Level vs. Kernel Level)
Process-Based and Thread-Based Multitasking
Multithreading Models and Benefits
Zombie Processes (Prevention & System Limits)
Remote Procedure Call (RPC)
7. Memory Management
Memory Hierarchy Design
Types of RAM (Random Access Memory)
Memory Allocation:
Buddy System
Partition Allocation (Fixed and Dynamic)
Non-Contiguous Allocation
Logical vs. Physical Address
Paging and Segmentation
Page Replacement Algorithms:
LRU, Optimal, LFU, Second Chance (Clock Policy)
Techniques to Handle Thrashing
Memory Virtualization (Virtual Address to Physical Mapping)
Program Implementations:
Buddy Memory Allocation (Set 1 and 2)
Next Fit Algorithm
Shared Libraries (Static and Dynamic)
8. Disk Management
File Systems and Unix File System
Directory Management Using Shell Script
File Directory Structures:
Path Name, Allocation Methods, and Access Methods
Disk Scheduling Algorithms (SSTF, Spooling, Buffering)
Free Space Management
9. Miscellaneous
Introduction to UNIX System
Important Linux Commands (leave, diff, cal, ncal, locate, ln)
Process States and Transitions in UNIX
Introduction to Linux Shell and Shell Scripting
crontab in Linux with Examples
Depth and Maxdepth in Linux find() Command
