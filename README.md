# C Process Management

This repository contains various C programs related to process management. The programs demonstrate different aspects of process creation, communication, and synchronization in a UNIX-like operating system environment.

## Programs Included

1. **calling_fork_multiple_times.c**: A program that demonstrates the use of the `fork()` system call to create multiple child processes.

2. **communicating_between_processes_using_pipes.c**: A program that showcases inter-process communication using pipes.

3. **file_copy.c**: A simple file copy program that demonstrates file I/O operations.

4. **main.c**: The main entry point for some of the included programs, showcasing basic process management techniques.

5. **process_pid.c**: A program that prints the process ID of the calling process and its parent process.

6. **process_wait.c**: A program that demonstrates the use of the `wait()` system call to synchronize parent and child processes.

## Executables

Compiled executables for the programs can be found in the `output` directory.

## Compilation

To compile any of the C programs, use the following command:
```sh
gcc -o output_file source_file.c
