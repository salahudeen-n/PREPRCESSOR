# C Preprocessor Implementation in C

## Project Description

This project is a basic implementation of a **C Preprocessor using C programming**. It demonstrates how a preprocessor processes a C source file before the actual compilation process.

The program takes a C source file as a command-line argument and generates an intermediate `.i` file by performing preprocessing operations.

## Features

- **File Inclusion:** Identifies `#include` directives and incorporates the contents of the corresponding header files into the output file.
- **Comment Removal:** Detects and removes single-line (`//`) and multi-line (`/* ... */`) comments from the source code.
- **Macro Handling:** Includes a separate module for handling `#define` macro directives.
- **Intermediate File Generation:** Generates an `.i` file containing the preprocessed source code.
- **Command-Line Arguments:** Accepts the input C filename through command-line arguments.

## Project Modules

| File | Description |
|---|---|
| `preprocessor_main.c` | Main function and preprocessing workflow |
| `file_inclusion.c` | Handles header file inclusion |
| `comment_removal_file.c` | Removes single-line and multi-line comments |
| `macro_handler.c` | Macro handling module |
| `header.h` | Function declarations and header file |
| `makefile` | Automates compilation |

## Technologies Used

- C Programming
- File Handling
- Dynamic Memory Allocation
- Pointers and Strings
- Structures and Linked Lists
- Command-Line Arguments
- Makefile

## Compilation and Execution

**1. Compile the project**

```bash
make
```

**2. Run the executable**

```bash
./mypreprocessor input.c
```

Replace `input.c` with your C source filename.

## Output

After successful execution, the program generates an intermediate file with the `.i` extension.

For example:

```text
input.c  →  input.i
```

The generated `.i` file contains the preprocessed output.

## Learning Outcomes

- Understanding the working principle of a C preprocessor.
- Learning file operations in C.
- Working with dynamic memory allocation and pointers.
- Understanding header file inclusion.
- Implementing comment removal techniques.
- Practicing modular programming using multiple C source files.

## Author

**Salahudeen N**

