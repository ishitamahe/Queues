# Queues
## Aim
To perform enqueue and dequeue operations ona queue.
## Theory
Queue is an abstract data structure. Unlike stacks, a queue is open at both its ends. It uses the princliple of FIFO, i.e, First in, First out. The side from where the element enters is called the rear of the queue and the side from where the element leaves is called the front of the queue. There are 2 main functions of queues, that are- Enqueue and Dequeue. Enqueue is a function used to insert or input an element in the queue. Dequeue is a function that is used to delete or remove an element from the queue. Whenever the queue is empty, the value of rear is -1. When the rear is full, the value of rear is max-1. 
## Algorithm
Step 1:Start. 
Step 2:Initialize global variables for array, front=-1 and rear=-1. 
Step 3:Initialize a function for enqueue. In this function, first check if the queue is full or not. If it isnt full insert the data from the rear end of the queue and increment the value of rear. The value of front is only incremented here if its current value is -1. 
Step 4:Initialize a function for dequeue. In this function, first check if the queue is empty or not. If it isnt empty, delete the data from the front end of the queue and decrement the value of rear. 
Step 5:For displaying the elements in the queue, we check the condition if the queue is empty or not. 
Step 6:In main(), take input from the user as to what operation is to be performed. Using switch case, perform the operation and print the queue.
Step 7:End.
## Conclusion
In this practical, we learnt about Queues and their basic fucntions such as enqueue and dequeue. We learnt how to implement a program to perform operations on queues. We learnt about its principle and the method in which queues functions. 
