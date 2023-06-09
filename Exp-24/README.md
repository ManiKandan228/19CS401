
# Exp-24-APPLICATIONS OF GRAPH

### PROGRAM STATEMENT:-
Given A Graph Of V Vertices And E Edges And Another Edge(C - D), The task is to Find if 
the Given Edge is a Bridge. i.e., Removing the Edge Disconnects the Graph. Write a C++ Function 
to Identify Bridge(s) In A Graph.

![image](https://github.com/ManiKandan228/19CS401/assets/119160414/b37f9a66-9a1e-457a-86d9-0b24192c98f3)

### PROGRAM:-
```
/* 
// A class that represents an undirected graph class 
Graph 
{ 
   int V; // No. of vertices 
   list<int> *adj; // A dynamic array of adjacency lists 
   void bridgeUtil(int v, bool visited[], int disc[], int low[], 
   int parent[]); 
public: 
   Graph(int V); // Constructor 
   void addEdge(int v, int w); // to add an edge to graph 
   void bridge(); // prints all bridges 
 }; 
 
Graph::Graph(int V) 
{ 
 this->V = V; adj = 
 new list<int>[V]; 
} 
void Graph::addEdge(int v, int w) 
{ 
 adj[v].push_back(w); 
 adj[w].push_back(v); // Note: the graph is undirected 
} 
 
*/ 
 
void Graph::bridge() 
{ 
 // Mark all the vertices as not visited 
 bool *visited = new bool[V]; int 
*disc = new int[V]; int *low = new 
int[V]; int *parent = new int[V]; 
//Write your code here 
for(int i=0;i<V;i++) 
 { 
    parent[i] = NIL; 
    visited[i] = false; 
 } 
 for(int i = 0;i<V;i++) 
    if(visited[i] == false) 
    bridgeUtil(i,visited,disc,low,parent); 
} 
```
### OUTPUT:-

![image](https://github.com/ManiKandan228/19CS401/assets/119160414/e6f4d576-ae0a-4aca-b1ef-b161d4365c83)

### RESULT:-
Thus, the C++ program has been executed successfully. 
