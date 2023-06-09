# Exp-11-QUEUE ADT 

### PROGRAM STATEMENT:-
Write a C++ program to insert five string elements in to Queue ADT (use STL for Queue) 

### PROGRAM:-
```
#include <iostream> 
#include <queue> 
using namespace std; 
int main() 
{ 
     queue <string> q; 
     for (int i =0;i<5;i++) 
     { 
         string a; 
         cin>>a; 
         q.push(a); 
      } 
     cout<<"Queue Elements are:"; 
     for(int i=0;i<5;i++) 
     { 
          cout<<q.front()<<" "; 
          q.pop(); 
      } 
return 0; 
}
```
### OUTPUT:-
![image](https://github.com/ManiKandan228/19CS401/assets/119160414/f20ef8a6-354c-4fce-8a97-04297e573dc2)

### RESULT:-
Thus, the C++ program has been executed successfully. 
