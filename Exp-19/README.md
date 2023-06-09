# Exp-19-RED-BLACK TREE 

### PROGRAM STATEMENT:-
Write the Traversal module of the red black tree in CPP. 

### PROGRAM:-
```
void inorder(node* root) 
 { 
   if(root!=NULL) 
   { 
     inorder(root->l); 
     cout<<"Data="<<root->d<<" "<<"Color="<<root->c<<endl; 
     inorder(root->r); 
   } 
 } 

```
### OUTPUT:-
![image](https://github.com/ManiKandan228/19CS401/assets/119160414/5997ea22-98d0-47d7-890c-36b108a40a77)

### RESULT:-
Thus, the C++ program has been executed successfully. 
