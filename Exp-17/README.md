# Exp-17-B TREE 

### PROGRAM STATEMENT:-
Write The Findmin module of the B Tree in C++  

### PROGRAM:-
```
void findMin(BTreeNode *myNode) 
{ 
 BTreeNode *curr = myNode; 
 while(curr->link[0]!= NULL) 
 { 
    curr = curr->link[0]; 
 } 
 cout<<endl<<"Min="<<curr->val[1]; 
 } 
```
### OUTPUT:-
![image](https://github.com/ManiKandan228/19CS401/assets/119160414/916dd22a-dfb8-4a29-930a-4aa6967fc307)

### RESULT:-
Thus, the C++ program has been executed successfully. 
