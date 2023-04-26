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

