# Dynamic memory allocation
## Introduction
This C program demonstrates the use of dynamic memory allocation in C using the malloc() and realloc() functions. The program allocates memory for two integer variables using malloc(), assigns values to them, and then uses realloc() to change the size of the memory block pointed to by one of the pointers.

![image](https://user-images.githubusercontent.com/125560933/234073159-3c31e20e-9969-42da-ab6a-c497cab117fd.png)


## Algorithm
1. Allocate memory for two integer variables using malloc().
2. Assign a value to the first variable using the first pointer.
3. Increment the first pointer to point to the second variable.
4. Assign a value to the second variable using the first pointer.
5. Use realloc() to change the size of the memory block pointed to by the first pointer.
6. Assign a value to the newly allocated memory location using the new pointer returned by realloc().

## Example
Suppose we want to allocate memory for two integer variables, assign them values, and then resize the memory block pointed to by one of the pointers to allocate memory for a single integer variable. The program does the following:

1. Allocates memory for two integer variables using malloc().
2. Assigns a value of 13 to the first variable using the first pointer.
3. Increments the first pointer to point to the second variable.
4. Assigns a value of 7 to the second variable using the first pointer.
5. Uses realloc() to resize the memory block pointed to by the first pointer to allocate memory for a single integer variable.
6. Assigns a value of 5 to the newly allocated memory location using the new pointer returned by realloc().


## Uses
Dynamic memory allocation is useful in situations where we don't know the size of the data that needs to be stored in memory beforehand. It allows us to allocate memory for data at runtime and release it when it's no longer needed. The malloc() and realloc() functions provide a flexible way to manage memory dynamically.

## Output of calloc.c , malloc.c and realloc.c:
![image](https://user-images.githubusercontent.com/125560933/234073375-2c40ce76-bd23-49de-8c90-5f394c9bdfe0.png)

## Applications
Dynamic memory allocation is used in a wide variety of applications, such as:

1. Implementing data structures like linked lists, stacks, and queues.
2. Allocating memory for variables and arrays in programs that need to handle varying amounts of data.
3. Implementing dynamic libraries and plugins that can be loaded and unloaded at runtime.


