# enquedeque

Algorithm for the given code:

1. Declare a global array "queue" of size 10 to hold the elements of the queue.
2. Declare global variables "front" and "rear" and initialize them to -1, indicating an empty queue.
3. Declare a global variable "data" to hold the data to be enqueued.
4. Declare two functions "enqueue" and "dequeue".
5. In the main function, call "enqueue" and "dequeue" functions.
6. In the "enqueue" function:
    a. Print "Enter the value:" to prompt the user for input.
    b. Read the data to be enqueued using "scanf" and store it in the "data" variable.
    c. If the "rear" variable is equal to 9, print "overflow" to indicate that the queue is full.
    d. If the queue is not full, increment the "rear" variable by 1 and add the "data" to the "queue".
    e. If the "front" variable is equal to -1, set it to 0.
7. In the "dequeue" function:
    a. If the "front" variable is equal to -1, print "underflow" to indicate that the queue is empty.
    b. If the "front" variable is greater than "rear", set both "front" and "rear" variables to -1 to indicate an empty queue.
    c. If the queue is not empty, increment the "front" variable by 1 to dequeue the element.
8. End of the algorithm.
