# Producer-Consumer Application

## Aim

To develop a Producer-Consumer application using Python
threading, multiprocessing, and synchronization primitives.

## Description

The Producer-Consumer problem is a common synchronization
problem where a producer generates data and a consumer
processes the generated data.

A Queue is used to safely transfer data from the producer
to the consumer.

## Technologies Used

- Python
- Threading
- Multiprocessing
- Queue
- Synchronization

## Algorithm

1. Create a shared queue.
2. Create a producer.
3. Create a consumer.
4. Producer generates items.
5. Producer places items into the queue.
6. Consumer removes items from the queue.
7. Process all generated items.
8. Repeat the implementation using multiprocessing.
9. Display the result.

## Input

Number of items: 5

Items:

1, 2, 3, 4, 5

## Output

The producer generates items and the consumer
successfully consumes all items.

## Result

The Producer-Consumer application was successfully
implemented using threading and multiprocessing.

## Conclusion

The program demonstrates concurrent execution and
communication between producer and consumer using
Python synchronization mechanisms.
