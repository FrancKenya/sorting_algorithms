ALX - C - Sorting algorithms & Big O

Background Context
This project is meant to be done by groups of two students. Each group of two should pair program for at least the mandatory part.

Resources
Read or watch:

Sorting algorithm
Big O notation
Sorting algorithms animations
15 sorting algorithms in 6 minutes (WARNING: The following video can trigger seizure/epilepsy. It is not required for the project, as it is only a funny visualization of different sorting algorithms)
CS50 Algorithms explanation in detail by David Malan
All about sorting algorithms
Learning Objectives
At the end of this project, you are expected to be able to explain to anyone, without the help of Google:

## Mandatory Tasks

### :white_check_mark: 0. Bubble sort
Write a function that sorts an array of integers in ascending order using the Bubble sort algorithm

* Prototype: `void bubble_sort(int *array, size_t size);`
* You’re expected to print the `array` after each time you swap two elements

Write in the file `0-O`, the big O notations of the time complexity of the Bubble sort algorithm, with 1 notation per line:

* in the best case
* in the average case
* in the worst case

File(s): [`0-bubble_sort.c`](./0-bubble_sort.c) [`0-O`](./0-O)\
Compiled: `gcc -Wall -Wextra -Werror -pedantic 0-bubble_sort.c 0-main.c print_array.c -o bubble`

### :white_check_mark: 1. Insertion sort
Write a function that sorts a doubly linked list of integers in ascending order using the Insertion sort algorithm

* Prototype: `void insertion_sort_list(listint_t **list);`
* You are not allowed to modify the integer `n` of a node. You have to swap the nodes themselves.
* You’re expected to print the `list` after each time you swap two elements

Write in the file `1-O`, the big O notations of the time complexity of the Insertion sort algorithm, with 1 notation per line:

* in the best case
* in the average case
* in the worst case

File(s): [`1-insertion_sort_list.c`](./1-insertion_sort_list.c) [`1-O`](./1-O)\
Compiled: `gcc -Wall -Wextra -Werror -pedantic 1-main.c 1-insertion_sort_list.c print_list.c -o insertion`

### :white_check_mark: 2. Selection sort
Write a function that sorts an array of integers in ascending order using the Selection sort algorithm

* Prototype: `void selection_sort(int *array, size_t size);`
* You’re expected to print the `array` after each time you swap two elements

Write in the file `2-O`, the big O notations of the time complexity of the Selection sort algorithm, with 1 notation per line:

* in the best case
* in the average case
* in the worst case

File(s): [`2-selection_sort.c`](./2-selection_sort.c) [`2-O`](./2-O)\
Compiled: `gcc -Wall -Wextra -Werror -pedantic 2-main.c 2-selection_sort.c print_array.c -o select`

### :white_check_mark: 3. Quick sort
Write a function that sorts an array of integers in ascending order using the Quick sort algorithm

* Prototype: `void quick_sort(int *array, size_t size);`
* You must implement the Lomuto partition scheme.
* The pivot should always be the last element of the partition being sorted.
* You’re expected to print the `array` after each time you swap two elements

Write in the file `3-O`, the big O notations of the time complexity of the Quick sort algorithm, with 1 notation per line:

* in the best case
* in the average case
* in the worst case

File(s): [`3-quick_sort.c`](./3-quick_sort.c) [`3-O`](./3-O)\
Compiled: `gcc -Wall -Wextra -Werror -pedantic 3-main.c 3-quick_sort.c print_array.c -o quick`
