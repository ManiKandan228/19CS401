# Exp-22-KRUSKAL'S MINIMUM SPANNING TREE

### PROGRAM STATEMENT:-
Given an N × N matrix of non-negative integers, where each cell of the matrix (i, j) 
indicates the direct flight cost from the city i to city j. Find the minimum cost to reach the 
destination city N-1 from the source city 0.

![image](https://github.com/ManiKandan228/19CS401/assets/119160414/d6ca3656-b1f7-42d7-a052-0c08964ec083)

### PROGRAM:-
```
/* 
class Graph { 
 vector<vector<int> > edgelist; 
 int V; 
 
public: 
 Graph(int V) { this->V = V; } 
 */ 
void addEdge(int x, int y, int w) 
{ 
  edgelist.push_back({w,x,y}); 
} 
```
### OUTPUT:-
![image](https://github.com/ManiKandan228/19CS401/assets/119160414/9394ade6-bf2b-485d-b207-2a7070adf1ec)

### RESULT:-
Thus, the C++ program has been executed successfully. 
