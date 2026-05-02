Aim:-
This lab foucuses on the compilation of the program using gdb compiler and helps in understand the core concept of Computer architecture and also the address indexing in the system this experiment helps us in understanding the following points.
Basic GDB commands and Compiling C code for Stack, Queue, Linked List using gdb.

Procedure:

Step 1: Write separate C programs for implementing the following data structures:

1. Stack
    Implement the stack using either an array or a linked list.
    Perform the following operations:
    Push
    Pop
    Peek

2. Queue
    Implement the queue using an array.
    Perform the following operations:
    Enqueue
    Dequeue

3. Linked List
    Implement using dynamic memory allocation (malloc).
    Perform the following operations:
    Insertion
    Deletion
    Traversal

Debugging using GDB:-

Stack Program:
gdb ./stack
break main
run
next
step (go inside push)
print top
print stack
continue

Queue Program:
gdb ./queue
break main
run
step (enter enqueue)
print front
print rear
print queue
continue

Linked List Program:
gdb ./linkedlist
break main
run
step (go inside insert)
print head
print *head
next
continue

Result:-
->Successfully compiled and debugged C programs using GDB.
->Learned and applied basic debugging commands.
->Understood memory behavior of stack (LIFO, stack memory), queue (FIFO, indexed memory), and linked list (dynamic memory, pointers).
->Observed how address indexing works internally.
->Gained practical understanding of memory layout, pointer operations, and function call stack.