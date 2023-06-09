# Exp-18-B+ TREE 

### PROGRAM STATEMENT:-
Write the findparent module of the B+ Tree in C++ 

### PROGRAM:-
```
Node *BPTree::findParent(Node *cursor, Node *child) 
{ 
   Node * parent; 
   if(cursor ->IS_LEAF || (cursor->ptr[0])->IS_LEAF) 
      { 
       return NULL; 
      } 
   for(int i = 0;i<cursor->size+1;i++) 
   { 
      if(cursor->ptr[i] == child) 
   { 
      parent = cursor; 
      return parent; 
   } 
   else 
   { 
      parent = findParent(cursor->ptr[i],child); 
      if(parent!= NULL) 
      return parent; 
      } 
   } 
   return parent; 
}
```
### OUTPUT:-
![image](https://github.com/ManiKandan228/19CS401/assets/119160414/6abb182e-3783-41f2-9819-34138ddf29a5)

### RESULT:-
Thus, the C++ program has been executed successfully. 
