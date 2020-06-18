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

### [0. Bubble sort](./0-bubble_sort.c)
* Write a function that sorts an array of integers in ascending order using the Bubble sort algorithm


### [1. Insertion sort](./1-insertion_sort_list.c)
* Write a function that sorts a doubly linked list of integers in ascending order using the Insertion sort algorithm


### [2. Selection sort](./2-selection_sort.c)
* Write a function that sorts an array of integers in ascending order using the Selection sort algorithm


### [3. Quick sort](./3-quick_sort.c)
* Write a function that sorts an array of integers in ascending order using the Quick sort algorithm


### [4. Shell sort - Knuth Sequence](./100-shell_sort.c)
* Write a function that sorts an array of integers in ascending order using the Shell sort algorithm, using the Knuth sequence


### [5. Cocktail shaker sort](./101-cocktail_sort_list.c)
* Write a function that sorts a doubly linked list of integers in ascending order using the Cocktail shaker sort algorithm


### [6. Counting sort](./102-counting_sort.c)
* Write a function that sorts an array of integers in ascending order using the Counting sort algorithm


### [7. Merge sort](./103-merge_sort.c)
* Write a function that sorts an array of integers in ascending order using the Merge sort algorithm


### [8. Heap sort ](./104-heap_sort.c)
* Write a function that sorts an array of integers in ascending order using the Heap sort algorithm


### [9. Radix sort](./105-radix_sort.c)
* Write a function that sorts an array of integers in ascending order using the Radix sort algorithm


### [10. Bitonic sort](./106-bitonic_sort.c)
* Write a function that sorts an array of integers in ascending order using the Bitonic sort algorithm


### [11. Quick Sort - Hoare Partition scheme](./107-quick_sort_hoare.c)
* Write a function that sorts an array of integers in ascending order using the Quick sort algorithm


### [12. Dealer](./1000-sort_deck.c)
* Write a function that sorts a deck of cards.

---

## Author
* **Juan Pablo Yepes Tamayo**
 - [GitHub](https://github.com/PabloYepes27)
 - [Linkedin](https://www.linkedin.com/in/pablo-yepes-120495)
 - [Twitter](https://twitter.com/pabloyepes27)

 * **Tomas Gomez**
 - [GitHub](https://github.com/tomasgvgt)
 - [Linkedin](https://www.linkedin.com/)
 - [Twitter](https://twitter.com/)
