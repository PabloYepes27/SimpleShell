# 0x16. C - Simple Shell

## Resources:books:
Read or watch:
* [Unix shell](https://en.wikipedia.org/wiki/Unix_shell)
* [Thompson shell](https://en.wikipedia.org/wiki/Thompson_shell)
* [Ken Thompson](https://en.wikipedia.org/wiki/Ken_Thompson)
* [Everything you need to know to start coding your own shell](https://intranet.hbtn.io/concepts/64)
* [The Linux Programming Interface - Michael Kerrisk]

---
## Learning Objectives:bulb:
What you should learn from this project:

* Who designed and implemented the original Unix operating system
* Who wrote the first version of the UNIX shell
* Who invented the B programming language (the direct predecessor to the C programming language)
* Who is Ken Thompson
* How does a shell work
* What is a pid and a ppid
* How to manipulate the environment of the current process
* What is the difference between a function and a system call
* How to create processes
* What are the three prototypes of main
* How does the shell use the PATH to find the programs
* How to execute another program with the execve system call
* How to suspend the execution of a process until one of its children terminates
* What is EOF / “end-of-file”?

---

## Instalation:wrench:
Follow the following instructions to get a copy of the program and run in your local machine.

* Clone the following repository.
```
https://github.com/PabloYepes27/SimpleShell.git
```

* Compile it with GCC
```
gcc -Wall -Werror -Wextra -pedantic -g *.c -o hsh
```

* Run the program
```
./hsh
```

* Run with debugger
```
valgrind --leak-check=full --show-leak-kinds=all ./executable_name
```
---

### [0. README, man, AUTHORS ](./hsh.c)
* Write a README, Write a man for your shell. You should have an AUTHORS file at the root of your repository, listing all individuals having contributed content to the repository. 


### [1. Betty would be proud](./hsh.c)
* Write a beautiful code that passes the Betty checks


### [2. Simple shell 0.1](./hsh.c)
* Write a UNIX command line interpreter


### [3. Simple shell 0.2](./hsh.c)
* Handle command lines with arguments


### [4. Simple shell 0.3](./hsh.c)
* Handle the PATH


### [5. Simple shell 0.4](./hsh.c)
* Implement the exit built-in, that exits the shell


### [6. Simple shell 1.0](./hsh.c)
* Implement the env built-in, that prints the current environment


### [7. What happens when you type ls -l in the shell](./hsh.c)
* Write a blog post describing step by step what happens when you type ls -l


### [8. Test suite](./hsh.c)
* Contribute to a test suite for your shell.


### [9. Simple shell 0.1.1](./hsh.c)
* Write your own getline function


### [10. Simple shell 0.2.1 ](./hsh.c)
* You are not allowed to use strtok


### [11. Simple shell 0.4.1](./hsh.c)
* handle arguments for the built-in exit


### [12. Simple shell 0.4.2](./hsh.c)
* Handle Ctrl+C: your shell should not quit when the user inputs ^C


### [13. setenv, unsetenv](./hsh.c)
* Implement the setenv and unsetenv builtin commands


### [14. cd](./hsh.c)
* Implement the builtin command cd


### [15. ;](./hsh.c)
* Handle the commands separator ;


### [16. && and ||](./hsh.c)
* Handle the && and || shell logical operators


### [17. alias](./hsh.c)
* Implement the alias builtin command


### [18. variables](./hsh.c)
* Handle variables replacement - Handle the $? variable - Handle the $$ variable


### [19. comments](./hsh.c)
* Handle comments (#)


### [20. help](./hsh.c)
* Implement the help built-in


### [21. history](./hsh.c)
* Implement the history built-in, without any argument


### [22. File as input](./hsh.c)
* Your shell can take a file as a command line argument
---

## Author:black_nib:
* **Juan Pablo Yepes Tamayo**
 - [GitHub](https://github.com/PabloYepes27)
 - [Linkedin](https://www.linkedin.com/in/pablo-yepes-120495)
 - [Twitter](https://twitter.com/pabloyepes27)

 * **Tomas Gomez**
 - [GitHub](https://github.com/tomasgvgt)
 - [Linkedin](https://www.linkedin.com/)
 - [Twitter](https://twitter.com/)
