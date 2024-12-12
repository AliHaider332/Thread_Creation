# Multithreading Task Simulator

## Overview

This program demonstrates the usage of **multithreading** in C++ to run two tasks concurrently. The tasks are **Task A** and **Task B**, each printing a message with a loop that runs 10 iterations. Both tasks are executed simultaneously using the C++ `<thread>` library, showcasing the power of multithreading in managing multiple tasks in parallel.

## Features

- **Multithreading**: Uses C++ threads to run `taskA()` and `taskB()` concurrently.
- **Task Execution**: Each task prints a message along with its iteration number (from 0 to 9).
- **Sleep Functionality**: A `sleep(1)` function call is used in each task to simulate a delay of 1 second between task iterations.
- **Thread Synchronization**: The `join()` method is used to ensure the main thread waits for the completion of both threads before finishing execution.

## How to Use

### 1. Compile the Program:
To compile the program, run the following command in the terminal:

```bash
g++ -std=c++11 -o multithreaded_program multithreaded_program.cpp
