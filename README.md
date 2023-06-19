# Memory Manager

## Table of Contents

1. [Introduction](#Introduction)
2. [Directory Structure](#Directory-Structure)
3. [Usage](#Usage)
4. [Contact](#Contact)

## Introduction

Welcome to the Memory Manager repository. This project is an implementation of a dynamic memory manager that provides memory allocation, deallocation, and optimization services for C programs. It employs best-fit memory allocation strategies, and features custom checks to ensure the consistency of the allocated memory.

## Directory Structure

The project directory structure:

```
.
├── README.md
├── Makefile
├── bench.c
├── clint.py
├── mem.h
├── mem_impl.h
├── mem_utils.c
└── memory.c
```

- `README.md`: This file, containing information about the project.
- `Makefile`: Used for compiling the project.
- `bench.c`: The benchmark file used to test the performance of the memory manager.
- `clint.py`: Python script for linting the C code.
- `mem.h`: Header file containing the function prototypes for the memory manager.
- `mem_impl.h`: Header file containing the function implementations for the memory manager.
- `mem_utils.c`: Contains utility functions used in the memory manager implementation.
- `memory.c`: The main implementation file of the memory manager.

## Usage

To use this project:

1. Clone the repository.
```bash
git clone https://github.com/masonJamesWheeler/Memory-Manager
```
2. Navigate to the directory.
```bash
cd <directory_name>
```
3. Compile the project using Makefile.
```bash
make
```
4. Run the memory manager.
```bash
./memory
```
5. (Optional) Test the performance of the memory manager using the benchmark file.
```bash
./bench
```

## Contact

For any questions, discussions, or clarifications about this Memory Manager or any related topics, feel free to contact me. I am always open to discussing concepts in Computer Systems and Memory Management.
