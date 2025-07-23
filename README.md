# 🧠 Operating Systems Project – ENCS3390

This repository contains implementations of three operating systems programming tasks focused on multithreading, scheduling simulation, and deadlock detection using CSV input.


---

## ✅ Task 1: Multithreaded Matrix Multiplication

Implements matrix multiplication using:
- Naive method (single-threaded)
- Multithreading with `pthread_create` and `pthread_join`
- Detached threads with `pthread_attr_setdetachstate`
- Parallel processing using `fork`

**Purpose**: Compare the performance of different execution models using time measurement with `gettimeofday()`.

---

## ✅ Task 2: CPU Scheduling Simulator

Simulates 6 scheduling algorithms:
- First Come First Serve (FCFS)
- Round Robin
- Shortest Remaining Time First (SRTF)
- Shortest Job First (SJF)
- Preemptive Priority
- Non-Preemptive Priority

**Note**: The simulator works for single runs per algorithm but may crash on repeated use due to memory handling limitations.

---

## ✅ Task 3: Deadlock Detection from CSV

Reads matrices from `Allocation.csv`, `Request.csv`, and `Available.csv`, then:
- Validates consistency
- Detects deadlock using Banker's Algorithm
- If safe: prints safe execution order
- If unsafe: lists deadlocked processes

**Language**: Python (NumPy, CSV parsing)


