# Sorting algorithms & Big O

- Implementation of twelve different sorting algorithms.

## Tests :heavy_check_mark:

* [tests](./tests): Folder of test files. 

## Data Structure and Functions 

* [print_array.c](./print_array.c): C function that prints an array of integers
* [print_list.c](./print_list.c): C function that prints a `listint_t`
doubly-linked list. 

## Header Files :file_folder:

* [sort.h](./sort.h): Header file containing definitions and prototypes for
all types and functions written for the project.

Data Structure:
```
typedef struct listint_s
{
	const int n;
	struct listint_s *prev;
	struct listint_s *next;
} listint_t;
```
