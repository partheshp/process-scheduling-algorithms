# Process Scheduling Algorithms

This repository contains various process scheduling algorithms implemented in C++. The purpose of these implementations is to demonstrate how different scheduling techniques work, including First-Come, First-Served (FCFS), Shortest Job First (SJF), Shortest Remaining Time First (SRTF), Round Robin (RR), Non-preemptive Priority, and Preemptive Priority scheduling.

## Table of Contents
- [Introduction](#introduction)
- [Algorithms Implemented](#algorithms-implemented)
- [Features](#features)
- [Usage](#usage)
- [Files](#files)

## Introduction
Process scheduling is a fundamental concept in operating systems, essential for multitasking and efficient CPU utilization. This repository provides graphical simulations of various process scheduling algorithms, offering user-friendly command-line interfaces for file input and visualization.

## Algorithms Implemented
1. **First-Come, First-Served (FCFS)**: Non-preemptive algorithm that processes requests in the order they arrive.
2. **Shortest Job First (SJF)**: Non-preemptive algorithm that selects the process with the smallest execution time.
3. **Shortest Remaining Time First (SRTF)**: Preemptive version of SJF, where the shortest remaining time process is always selected next.
4. **Round Robin (RR)**: Preemptive algorithm that assigns a fixed time unit per process and cycles through them.
5. **Non-preemptive Priority**: Processes are scheduled based on priority, without preemption.
6. **Preemptive Priority**: Priority-based scheduling with preemption, allowing higher priority processes to interrupt lower priority ones.

## Features
- **Graphical Simulations**: Visualize the scheduling process using NCurses.
- **Flexible Input Handling**: Process data can be input via file or default to "process-data.txt".
- **User-friendly Interface**: Command-line interface for easy interaction and parameter input.

## Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/partheshp/process_scheduling_algorithms.git
   cd process_scheduling_algorithms
   ```
2. Compile the desired algorithm:
   ```bash
   g++ -o scheduler fcfs_scheduling.cpp -lncurses
   ```
3. Run the compiled program:
   ```bash
   ./scheduler
   ```

## Files
* `fcfs_scheduling.cpp`: Implementation of FCFS scheduling.
* `sjf_scheduling.cpp`: Implementation of SJF scheduling.
* `srtf_scheduling.cpp`: Implementation of SRTF scheduling.
* `roundrobin_scheduling.cpp`: Implementation of Round Robin scheduling.
* `nonpreemptive_priority.cpp`: Implementation of Non-preemptive Priority scheduling.
* `preemptive_priority_scheduling.cpp`: Implementation of Preemptive Priority scheduling.
