# C - Simple Shell

## _atoi.c

The interactive() function was modified to include a descriptive comment and a clearer return statement.
The is_delim() function was modified to include a descriptive comment and a clearer return statement.
The _isalpha() function was modified to include a descriptive comment and a clearer return statement.
The _atoi() function was modified to include a descriptive comment and a clearer return statement.


## builtin.c

### Shell Project
This project contains a simple shell program that can execute basic commands. It consists of several source files including shell.c, lists.c, builtins.c, utils.c, lists.h, shell.h, and utils.h.

### How to Build
To build the shell program, simply run make in the project directory. This will generate an executable called simple_shell.

### How to Run
To run the shell program, simply execute the simple_shell executable. This will launch a prompt where you can enter commands. The shell supports basic commands like ls, pwd, and echo, as well as built-in commands like cd, exit, and help.

### File Descriptions
shell.c: contains the main function and code for launching the shell prompt and processing user input.
lists.c: contains code for creating and manipulating linked lists used by the shell.
builtins.c: contains code for implementing built-in shell commands like cd, exit, and help.
utils.c: contains utility functions used by other parts of the shell code.
lists.h: header file for the linked list code in lists.c.
shell.h: header file for the main shell program.
utils.h: header file for the ut
## main.c

### The code is written in C and consists of several source files, including:

shell.c: main program file that contains the main function and handles user input and program execution.
history.c: file that contains functions for saving and loading command history.
utils.c: file that contains utility functions used throughout the program.
lists.c: file that contains functions for working with linked lists.
shell.h: header file that contains function prototypes and definitions.

## shell.h

### This is a header file for a simple Unix shell implementation written in C.

The file contains various function prototypes, constants, and structs that are used throughout the program.

The program is divided into multiple source files, including the main loop (toem_shloop.c), parser (toem_parser.c), tokenizer (toem_tokenizer.c), and built-in commands (toem_builtin.c).

The program supports basic shell functionality, including the ability to execute commands with arguments, redirect input/output, and chain commands with && and ||. It also supports built-in commands such as cd, exit, and history.

The program utilizes various Unix system calls and functions, such as fork(), execvp(), wait(), open(), and close(), as well as linked lists and dynamic memory allocation.

The header file contains multiple constants for buffer sizes, command chaining types, and input/output redirection. It also includes structs for storing linked lists of environment variables, history, and aliases, as well as a struct for passing information between functions.

Overall, this shell implementation provides a basic example of how a Unix shell can be implemented in C, and demonstrates various programming concepts such as system calls, linked lists, and dynamic memory allocation.
