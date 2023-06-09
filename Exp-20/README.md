# Exp-20-SPLAY TREE

### PROGRAM STATEMENT:-
Write The Preorder Traversal Module of Splay Tree in C++

### PROGRAM:-
```
void preOrder(struct node *root) 
{ 
   if(root!= NULL) 
   { 
     cout<<root->key<<" "; 
     preOrder(root->left); 
     preOrder(root->right); 
   } 
 } 

```
### OUTPUT:-
![image](https://github.com/ManiKandan228/19CS401/assets/119160414/56180485-629e-4fea-b7b5-3df69d62cef6)

### RESULT:-
Thus, the C++ program has been executed successfully. 
