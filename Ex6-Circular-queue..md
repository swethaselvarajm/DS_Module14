# Ex6 Dequeue Elements from Circular Queue
## DATE:
## AIM:
To write a C program to delete three elements from the filled circular queue.

## Algorithm
1. Initialize a circular queue with a fixed size and front and rear pointers.
2. Check if the queue is empty before dequeuing.
3. If not empty, remove the element at the front and update the front pointer.
4. Handle wrap-around using modulo operation. 
5. Repeat the dequeue operation three times to remove three elements.  

## Program:
```
/*
Program to delete three elements from the filled circular queue
Developed by: SWETHA S
RegisterNumber: 212222230155
*/
```
```
/*
/*#include <stdio.h>

#define SIZE 5

int items[SIZE];
int front = -1, rear = -1;
*/
int deQueue() {
  int element;
  element=items[front];
  if(isEmpty())
  {
      printf("Queue is Empty!!");
  }
  else
  {
      if(front == rear) 
      {
          front=-1;
          rear=-1;
      }
      else
      {
          front=(front+1)%SIZE;
          
      }
  }
  return element;
  //type your code here...
}
*/
```
## Output:
<img width="874" height="356" alt="image" src="https://github.com/user-attachments/assets/1bf06dc1-021f-48d8-b61f-17cc2c41fcbf" />



## Result:
Thus, the C program to delete three elements from the filled circular queue is implemented successfully.
