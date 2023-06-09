# Exp-21-PRIM'S MINIMUM SPANNING TREE

### PROGRAM STATEMENT:-
Given A Weighted, Undirected and Connected Graph of V Vertices and E Edges. The Task 
is to Find the Sum of Weights of the Edges Of The Minimum Spanning Tree.

![image](https://github.com/ManiKandan228/19CS401/assets/119160414/ba045246-1186-43e8-b462-834f87ac3f01)


### PROGRAM:-
```
/* 
#include<bits/stdc++.h>
using namespace std; 
# define INF 0x3f3f3f3f 
 
// iPair ==> Integer Pair typedef 
pair<int, int> iPair; 
 
// This class represents a directed graph using 
// adjacency list representation class 
Graph 
{ 
 int V; // No. of vertices 
 
 // In a weighted graph, we need to store vertex 
 // and weight pair for every edge 
 list< pair<int, int> > *adj; public: 
 Graph(int V); // Constructor 
 
 // function to add an edge to graph 
 void addEdge(int u, int v, int w); 
 
 // Print MST using Prim's algorithm 
 void primMST(); 
}; 
 
// Allocates memory for adjacency list 
Graph::Graph(int V) 
{ 
 this->V = V; 
 adj = new list<iPair> [V]; 
} */ 
 
void Graph::addEdge(int u, int v, int w) 
{ 
  adj[u].push_back(make_pair(v,w)); 
  adj[v].push_back(make_pair(u,w)); 
} 
```
### OUTPUT:-
![image](https://github.com/ManiKandan228/19CS401/assets/119160414/f7eaba93-c146-4b6a-b532-a56032d19f24)

### RESULT:-
Thus, the C++ program has been executed successfully. 
