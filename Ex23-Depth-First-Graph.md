# Ex23 Depth First Graph
## DATE: 19-04-2025
## AIM:
To compose the code for the function createNode to traverse the graph below in the depth first fashion.

![image](https://github.com/user-attachments/assets/63552824-d0a3-49c6-a473-6db27d1f03e4)

## Algorithm
1. Start
2. Allocate memory for a new node.
3. Set the vertex field of the new node to the given value v.
4. Set the next pointer of the new node to NULL.
5. Return the newly created node.
6. End  

## Program:
```
Program to traverse the graph below in the depth first fashion
Developed by: TANESSHA KANNAN
RegisterNumber: 212223040225

#include <stdio.h>
#include <stdlib.h>

struct node {
  int vertex;
  struct node* next;
};

struct node* createNode(int v);

struct Graph {
  int numVertices;
  int* visited;
  struct node** adjLists;
};
struct node* createNode(int v) {
 
  struct node* newNode=(struct node*)malloc(sizeof(struct node));
  newNode->vertex=v;
  newNode->next=NULL;
  return newNode;
}
```

## Output:
![image](https://github.com/user-attachments/assets/b26057a7-fd6c-4388-be75-08e3231fc15c)

## Result:
Thus, the C code for the function createNode to traverse the graph below in the depth first fashion is implemented successfully
