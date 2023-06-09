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
![Uploading image.png…]()

### RESULT:-
Thus, the C++ program has been executed successfully. 
