# Ex8 Deque
## DATE:
## AIM:
To write a C function to count the number of elements present in the deque.

## Algorithm
```
1. Initialize a counter variable c to 0.
2.Loop through each index i from 0 to MAX-1 in the array.
3.Check if the element at position i is greater than 0.
4.If it is, increment the counter c.
5.After the loop, return the final count c as the number of valid elements.  
```
## Program:
```
/*
Program to count the number of elements present in the deque
Developed by: Sharmitha V
RegisterNumber: 212223110048
/*#include <stdio.h>

#define MAX 10

void addFront(int *, int, int *, int *);
void addRear(int *, int, int *, int *);
int delFront(int *, int *, int *);
int delRear(int *, int *, int *);
void display(int *);
int count(int *);
*/
int count(int *arr) {
  int c = 0;
  for(int i=0;i<MAX;i++){
      if (arr[i]>0){
          c++;
      }
  }
  return c;
}
*/
```

## Output:

![image](https://github.com/user-attachments/assets/1770afda-de1c-463a-a20f-1396ce85869e)


## Result:
Thus, the C code to count the number of elements present in the deque is implemented successfully.
