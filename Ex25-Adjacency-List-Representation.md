# Ex25 Adjacency List Representation
## DATE: 24-04-2025
## AIM:
To write a C program to represent the given graph using the adjacency list.

## Algorithm
1. Read the number of vertices and number of edges.
2. Read all edge pairs (source and destination) and store them.
3. Create a graph using the input edge list.
4. Print the adjacency list representation of the graph.

## Program:
```
Program to find and display the priority of the operator in the given Postfix expression
Developed by: TANESSHA KANNAN
RegisterNumber: 212223040225

int main(void)
{   
    int i,n;
    scanf("%d",&N);
    scanf("%d",&n);
    struct Edge edges[n];
    for(i=0;i<n;i++){
        scanf("%d",&edges[i].src);
        scanf("%d",&edges[i].dest);
    }
    struct Graph* graph = createGraph(edges,n);
    printGraph(graph);
    return 0;
}
```

## Output:
![image](https://github.com/user-attachments/assets/5d17318a-b176-44b2-9324-a77d1de6d0d6)

## Result:
Thus, the C program to represent the given graph using the adjacency list is implemented successfully
