SIMPLE SHELL 

## Description
The aim of this project made at Alx School is to gain knowledge about the background work of a Shell when there is an user input in the prompt. 

The following is the way that our shell is compiled: 
```bash
  gcc -Wall -Werror -Wextra -pedantic -std=gnu89 *.c -g -o hsh 
```
In the other hand, our shell can run on interactive mode and non-interactive mode and also meets the Betty syntax standards.


## In few words our Shell is able to


- Display a prompt and wait for the user to type a command.
- Display the prompt again each time a command has been executed.
- Recognize if an executable cannot be found, print an error message and display the prompt again.
- Create a child process only if the command exists (avoids creating unnecessary child processes).
- Handle errors.
- Handle the “end of file” condition (Ctrl+D).
- Handle command lines with arguments.
- Handle the PATH.
- Handle the "exit" built-in.
- Handle the "env" built-in.
- Handle when the user input is a Ctrl+C.
- Execute in interactive and non-interactive modes.
## FILES
## How to use

Clone our directory to your working space:

```bash
  git clone https://github.com/MatiasMtz/simple_shell.git
```
Compile our Shell code this way:
```bash
  gcc -Wall -Werror -Wextra -pedantic -std=gnu89 *.c -g -o hsh 
```
Execute the Shell in interactive mode by:
```bash
   ./hsh
```
Or in non interactive mode (as an example):
```bash
   echo ls | ./hsh
```

## Tasks requested in this project:
|              | BRIEF DESCRIPTION                                                                |
| ----------------- | ------------------------------------------------------------------ |
| 0. README, man, AUTHORS | Write a README, a man and an AUTHORS file. |
| 1. Betty would be proud | Pass Betty checks |
| 2. Simple shell 0.1 | Display a prompt and wait for the user to type a command, if an executable cannot be found, print an error message and display the prompt again, handle errors, etc. |
| 3. Simple shell 0.2 | Handle command lines with arguments |
| 4. Simple shell 0.3 | Handle the PATH, fork must not be called if the command doesn’t exist |
| 5. Simple shell 0.4 | Implement the exit built-in, that exits the shell |
| 6. Simple shell 1.0 | mplement the env built-in, that prints the current environment |
| 7. What happens when you type `ls -l *.c` in the shell | Write a blog post describing step by step what happens when you type ls -l *.c |
| 8. Test suite | Contribute to a test suite for your shell. (https://github.com/Nachop51/shell_tests/tree/main/axel_matias_test) |
| 9. Simple shell 0.1.1 | Write your own getline function |
| 10. Simple shell 0.2.1 | You are not allowed to use strtok |
| 11. Simple shell 0.4.1 | handle arguments for the built-in exit |
| 12. Simple shell 0.4.2 | Handle Ctrl+C |
| 13. setenv, unsetenv | Implement the setenv and unsetenv builtin commands |
| 14. cd | Implement the builtin command cd |
| 15. ; | Handle the commands separator ; |
| 16. && and double pipes | Handle the && and doble pipes shell logical operators |
| 17. alias | Implement the alias builtin command |
| 18. Variables | Handle variables replacement |
| 19. Comments | Handle comments (#) |
| 20. help | Implement the help built-in |
| 21. history | Implement the history built-in, without any argument |
| 22. File as input | Your shell can take a file as a command line argument |

## Authors
- Samuel Obayemi -[Github](https://github.com/theodes1) / [Linkedin](linkedin.com/in/samuel-obayemi-631025153/)
- Ridwanullahi Badmus -[Github](https://github.com/https://github.com/Sagna112) / [Linkedin](https://www.linkedin.com/in/badmus-ridwanullahi-540012202/)
