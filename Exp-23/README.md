# Exp-23-SHORTEST PATH - DIJKSTRA'S ALGORITHM 

### PROGRAM STATEMENT:-
There is an undirected weighted connected graph. You are given a positive integer n which 
denotes that the graph has n nodes labeled from 1 to n, and an array edges where each edges[i] = 
[ui, vi, weighti] denotes that there is an edge between nodes ui and vi with weight equal to weighti. 
Write a CPP addEdge() function to find the Dijkstra's shortest path from every node to all other 
nodes in the given graph. 

![image](https://github.com/ManiKandan228/19CS401/assets/119160414/ca3b2ca2-ea2f-4213-bae0-ecfad2841d44)

### PROGRAM:-
```
/* 
# define INF 0x3f3f3f3f list< 
pair<int, int> > *adj; 
 
class Graph 
{ 
 int V; // No. of vertices 
public: 
 Graph(int V); // Constructor 
 
 // function to add an edge to graph 
 void addEdge(int u, int v, int w); 
 list< pair<int, int> > *adj; 
 // prints shortest path from s 
 void shortestPath(int s); 
}; 
Graph::Graph(int V) 
{ 
 this->V = V; 
 adj = new list< pair<int, int> >[V]; 
} 
void Graph::shortestPath(int src) 
{ 
 
}*/ 
void Graph::addEdge(int u, int v, int w) 
{ 
 adj[u].push_back(make_pair(v,w)); 
 adj[v].push_back(make_pair(u,w)); 
} 
```
### OUTPUT:-

![image](https://github.com/ManiKandan228/19CS401/assets/119160414/c6323381-c6c5-4536-91f8-a162624e7b78)

### RESULT:-
Thus, the C++ program has been executed successfully. 
