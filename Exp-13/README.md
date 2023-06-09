# Exp-13-STACK USING LINKED LIST 

### PROGRAM STATEMENT:-
Write a CPP Program to insert five float elements in to Stack using linked list (use STL for Stack) 

### PROGRAM:-
```
#include<iostream> 
using namespace std; 
class node 
{ 
   public: 
   float data; 
   node *next; 
}*temp,*top; 
void push() 
{ 
   if(top==NULL) 
   { 
     temp=new node; 
     cin>>temp->data; 
     temp->next=NULL; 
     top=temp; 
   } 
   else 
   { 
     temp=new node; 
     cin>>temp->data; 
     temp->next=top;
     top=temp; 
 } 
} 
void pop() 
{ 
   temp=top; 
   top=temp->next; 
   temp->next=NULL; 
   free(temp); 
} 
int main() 
{ 
   int n; 
   cin>>n; 
   for(int i=0;i<n;i++) 
   { 
      push(); 
   } 
   cout<<"Current size of the stack is "<<n<<endl; 
   cout<<"The top element of the stack is "<<top->data<<endl; 
   pop(); 
   cout<<"The top element after 1 pop operation is "<<top->data<<endl; 
   pop(); 
   cout<<"The top element after 2 pop operations is "<<top->data<<endl; 
   pop(); 
   cout<<"Size of the stack after 2 pop operations is "<<n-2<<endl; 
}
```
### OUTPUT:-
![image](https://github.com/ManiKandan228/19CS401/assets/119160414/20531151-3fdc-4ece-8693-38d8bbeb224f)

### RESULT:-
Thus, the C++ program has been executed successfully. 
