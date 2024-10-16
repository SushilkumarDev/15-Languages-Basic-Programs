# Multi-Language Programming Examples

Welcome to the **Multi-Language Programming Examples** repository! This project is designed to showcase a wide range of programming languages by solving various problems and tasks in different coding environments. Whether you're learning a new language or comparing syntax and performance across languages, this repository serves as a comprehensive reference.

## Table of Contents

- [Overview](#overview)
- [Languages](#languages)
- [Installation](#installation)
- [Usage](#usage)
- [Examples](#examples)
- [Contributing](#contributing)
- [License](#license)

## Overview

This repository aims to demonstrate how common programming tasks and algorithms are implemented in various languages, highlighting differences in syntax, paradigms, and performance. It’s a great resource for:

- Developers exploring new languages.
- Programmers comparing features across languages.
- Students learning about different programming paradigms.

By providing practical examples, this repository encourages both beginners and experienced developers to deepen their understanding of multiple programming languages.

## Languages

The repository currently includes implementations in the following languages:

1. Assembly (`main.asm`)
2. C (`main.c`)
3. C++ (`main.cpp`)
4. C# (`main.cs`)
5. Go (`main.go`)
6. Java (`main.java`)
7. JavaScript (`main.js`)
8. PHP (`main.php`)
9. Python (`main.py`)
10. R (`main.R`)
11. Ruby (`main.rb`)
12. Rust (`main.rs`)
13. Shell Script (`main.sh`)
14. Swift (`main.swift`)
15. TypeScript (`main.ts`)

Each folder contains one or more files that demonstrate various programming tasks in the specific language.

## Installation

### Prerequisites

To run the programs, you need to have the appropriate compilers or interpreters installed for each language. Below are some common installation commands for popular languages:

- **Assembly (NASM)**:

  ```bash
  sudo apt install nasm
  ```

- **GCC** (for C, C++, Assembly):

  ```bash
  sudo apt install build-essential
  ```

- **Python**:

  ```bash
  sudo apt install python3
  ```

- **Node.js** (for JavaScript and TypeScript):

  ```bash
  sudo apt install nodejs npm
  ```

- **Java**:

  ```bash
  sudo apt install default-jdk
  ```

- **Go**:
  ```bash
  sudo apt install golang
  ```

For other languages, please refer to their respective official documentation for installation instructions.

## Usage

### Running Programs

Each file is a standalone program. Depending on the language, you can compile or interpret the file using the respective command line tools. Below are examples of how to run programs in each language:

1. **Assembly**:

   ```bash
   nasm -f elf64 -o main.o main.asm
   ld -s -o main main.o
   ./main
   ```

2. **C**:

   ```bash
   gcc main.c -o main
   ./main
   ```

3. **C++**:

   ```bash
   g++ main.cpp -o main
   ./main
   ```

4. **C#**:

   ```bash
   csc main.cs
   mono main.exe
   ```

5. **Go**:

   ```bash
   go run main.go
   ```

6. **Java**:

   ```bash
   javac main.java
   java Main
   ```

7. **JavaScript (Node.js)**:

   ```bash
   node main.js
   ```

8. **PHP**:

   ```bash
   php main.php
   ```

9. **Python**:

   ```bash
   python3 main.py
   ```

10. **R**:

    ```bash
    Rscript main.R
    ```

11. **Ruby**:

    ```bash
    ruby main.rb
    ```

12. **Rust**:

    ```bash
    rustc main.rs
    ./main
    ```

13. **Shell Script**:

    ```bash
    bash main.sh
    ```

14. **Swift**:

    ```bash
    swift main.swift
    ```

15. **TypeScript**:
    ```bash
    tsc main.ts && node main.js
    ```

## Examples

Each language folder contains multiple examples that demonstrate common programming tasks and algorithms. These include:

- **Basic Syntax**: Illustrating the syntax and structure of the language.
- **Data Structures**: Implementations of arrays, linked lists, stacks, and more.
- **Algorithms**: Sorting (e.g., bubble sort, quicksort), searching (e.g., binary search).
- **Mathematical Programs**: Prime number checkers, Fibonacci sequences, factorial calculations.
- **File I/O**: Examples of reading from and writing to files.
- **Concurrency**: Illustrating threading, async operations, and parallel processing in some languages (e.g., Go, Java, Rust).

Each language directory also contains a `README.md` file explaining the specific examples and instructions for running the code.

## Contributing

We warmly welcome contributions from the community! Whether you'd like to:

- Add a new language.
- Improve an existing example.
- Optimize performance.

You’re encouraged to participate in making this repository even better. Follow these steps to contribute:

1. **Fork the Repository**: Click the "Fork" button at the top of this page to create your own copy of this repository.
2. **Create a New Branch**: Before making changes, create a new branch in your forked repository:
   ```bash
   git checkout -b your-branch-name
   ```
3. **Make Your Changes**: Ensure your code is clean, properly commented, and follows best practices for the language.
4. **Submit a Pull Request**: Once your changes are ready, submit a pull request with a description of what you’ve improved or added.

We’ll review your pull request as soon as possible and work with you to ensure it fits within the project’s scope.

## License

This project is licensed under the MIT License. For more details, see the [LICENSE](LICENSE) file.
