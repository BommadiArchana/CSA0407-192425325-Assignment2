# OPERATING SYSTEMS – ASSIGNMENT 2

## Student Details

| Detail | Information |
|---|---|
| **Course Code** | CSA0407 |
| **Register Number** | 192425325 |
| **Repository Name** | CSA0407-192425325-Assignment2 |
| **Assignment** | Assignment 2 – CO2 |
| **Subject** | Operating Systems |
| **Total Marks** | 50 |
| **Bloom's Taxonomy Level** | K5 – Evaluate |
| **Duration** | 1 Week |

---

## 1. Assignment Overview

This repository contains the implementation and analysis of Operating Systems concepts related to process management, CPU scheduling, multithreading, inter-process communication, process synchronization and deadlock handling.

The assignment focuses on applying and evaluating operating system techniques through C programming, practical execution, performance measurements, diagrams and output screenshots.

The objective is to understand how operating systems manage processes, allocate CPU resources, coordinate concurrent activities and prevent unsafe resource allocation.

## 2. Objectives

- Understand process creation and process states.
- Implement and evaluate CPU scheduling algorithms.
- Explore multithreading and thread performance.
- Implement inter-process communication techniques.
- Understand synchronization using mutex locks and semaphores.
- Implement the Banker's Algorithm for deadlock avoidance.
- Analyse performance, resource utilization and system behaviour.

## 3. Technologies and Tools Used

- **Programming Language:** C
- **Compiler:** GCC / Online C Compiler
- **Development Environment:** OneCompiler
- **Version Control:** Git and GitHub
- **Operating System Concepts:** Processes, Threads, Scheduling, IPC, Synchronization and Deadlocks.

## 4. Assignment Tasks

### Q1 – Processes and Process States 

**Problem Context:** Online Examination Server

This task demonstrates process creation using the `fork()` system call.

**Concepts Covered:**
- Process creation and termination.
- Process State Diagram.
- Process Control Block (PCB).
- Parent and child processes.
- Process information using `ps` and `/proc`.
- Evaluation of resource overhead when 2,000 processes are active.

**Evidence:** C program, execution output, process-state diagram and PCB description.

### Q2 – CPU Scheduling 

**Problem Context:** Cloud Video-Encoding Service

This task evaluates CPU scheduling algorithms for jobs with different arrival times and burst times.

**Concepts Covered:**
- First Come First Serve (FCFS).
- Shortest Job First (SJF).
- Shortest Remaining Time First (SRTF).
- Priority Scheduling.
- Round Robin Scheduling.
- Gantt charts, waiting time and turnaround time.
- Time quantum comparison and starvation analysis.

**Evidence:** Scheduling calculations, Gantt charts, C program, execution outputs and performance comparison.

### Q3 – Threads 

**Problem Context:** Traffic-Camera Number-Plate Reader

This task analyses multithreading for processing traffic-camera frames.

**Concepts Covered:**
- Thread creation and execution.
- POSIX Pthreads.
- User-level and kernel-level threads.
- Shared and private thread resources.
- Comparison of 4, 8 and 16 threads.
- Thread performance and speed-up.
- Shared-counter protection.

**Evidence:** Multithreaded C program, execution output, thread diagrams and performance comparison.

### Q4 – Inter-Process Communication 

**Problem Context:** Weather Station Data Pipeline

This task demonstrates communication between processes for exchanging weather readings.

**Concepts Covered:**
- Inter-Process Communication (IPC).
- Pipe communication.
- Shared memory.
- Message passing.
- Blocking and synchronization.
- Data transfer performance for 1 MB, 10 MB and 100 MB.

**Evidence:** IPC implementation, execution outputs, communication diagrams and transfer-time comparison.

### Q5 – Synchronisation: Critical Sections, Semaphores and Monitors 

**Problem Context:** Railway Ticket Booking

This task demonstrates synchronization techniques to prevent race conditions and ensure safe access to shared resources.

**Concepts Covered:**
- Critical-section problem.
- Mutual exclusion, progress and bounded waiting.
- Peterson's solution.
- Binary and counting semaphores.
- Mutex locks.
- Producer–Consumer bounded-buffer problem.
- Synchronization using producers and consumers.

**Evidence:** Synchronization C program, semaphore implementation, execution outputs and locking decision.

### Q6 – Deadlock Handling and the Banker's Algorithm 

**Problem Context:** Shared Laboratory Equipment Scheduler

This task evaluates deadlock handling techniques and implements the Banker's Algorithm for safe resource allocation.

**Concepts Covered:**
- Four necessary conditions for deadlock.
- Deadlock prevention.
- Deadlock avoidance.
- Deadlock detection and recovery.
- Banker's Safety Algorithm.
- Resource Request Algorithm.
- Safe and unsafe states.
- Safe sequence identification.
- Performance measurement for 10, 100 and 1,000 processes.

**Evidence:** Banker's Algorithm C program, resource-allocation graph, safe-sequence calculations, execution outputs and performance analysis.

---

## 5. Repository Structure

```text
CSA0407-192425325-Assignment2/
│
├── Q1_Process_States/
│   ├── Code/
│   ├── Screenshots/
│   └── Diagrams/
│
├── Q2_CPU_Scheduling/
│   ├── Code/
│   ├──  Diagrams/
│   └── Output/
│
├── Q3_Threads/
│   ├── Code/
│   ├──  Diagrams/
│   └── Output/
│
├── Q4_Inter_Process_Communication/
│   ├── Code/
│   ├──  Diagrams/
│   └── Output/
│
├── Q5_Synchronization/
│   ├── Code/
│   ├──  Diagrams/
│   └── Output/
│
├── Q6_Deadlock_Bankers_Algorithm/
│   ├── Code/ 
│   ├── Output/
│   └── Diagrams/
│
└── README.md
```

## 6. Execution Instructions

1. Open the respective C source file.
2. Copy the program into a compatible C compiler.
3. Compile and execute the program.
4. Verify the output with the expected results.
5. Capture the execution screenshot.
6. Upload the screenshot into the respective Screenshots folder.
7. Store relevant diagrams and supporting evidence in their respective folders.

**Note:** Programs using POSIX system calls, Pthreads or Linux-specific features require a compatible Linux/POSIX environment.

## 7. Expected Learning Outcomes

After completing this assignment, the following outcomes are expected:

- Understand process management and process creation.
- Evaluate CPU scheduling algorithms.
- Analyse multithreading performance.
- Demonstrate inter-process communication.
- Apply synchronization mechanisms to concurrent programs.
- Evaluate deadlock avoidance using the Banker's Algorithm.
- Interpret experimental results and justify technical decisions.

## 8. Conclusion

This assignment provides practical exposure to fundamental Operating Systems concepts through C programming and experimental analysis.

By implementing and evaluating different algorithms and synchronization techniques, the assignment helps understand how operating systems manage processes, handle concurrency, communicate between processes and allocate resources safely.

---

**Course Code:** CSA0407  
**Register Number:** 192425325  
**Assignment:** Operating Systems – Assignment 2 (CO2)
