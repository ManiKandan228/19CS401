# Exp-15-QUEUE USING LINKED LIST

### PROGRAM STATEMENT:-
Write a CPP Program to implement Queue using Linked List, insert integer elements in to 
Queue and delete two items from Queue. 

### PROGRAM:-
```
#include<iostream> 
using namespace std; 
class node 
{ 
   public: 
   double data; 
   node *next; 
}*front,*rear,*temp; 
void push() 
{ 
     temp=new node; 
     cin>>temp->data; 
     temp->next=NULL; 
     if(rear==NULL) 
     { 
         front =temp; 
         rear=temp; 
     } 
     else 
     { 
         rear->next=temp; 
         rear=rear->next; 
     } 
} 
void pop() 
{ 
   temp=front; 
   front=front->next; 
   temp->next=NULL; 
   free(temp); 
} 
void display() 
{ 
   temp=front; 
   while(temp !=NULL) 
   { 
     cout<<temp->data<<" "; 
     temp=temp->next; 
   } 
   cout<<endl; 
} 
void ldisp() 
{ 
   temp=front; 
   cout<<"Queue Front : "<<temp->data; 
   temp=rear; 
   cout<<endl; 
   cout<<"Queue Rear : "<<temp->data; 
} 
int main() 
{ 
 int n; 
 cin>>n; 
 cout<<"Underflow."<<endl; 
 for(int i=0;i<n;i++) 
 { 
    push(); 
 } 
 cout<<"Queue :"; 
 display(); 
 cout<<"After DeQueue :"; 
 pop(); 
 pop(); 
 display(); 
 ldisp(); 
} 
```
### OUTPUT:-
![image](https://github.com/ManiKandan228/19CS401/assets/119160414/640dac6b-49df-4ff4-a9f2-7d005a9fe8e5)

### RESULT:-
Thus, the C++ program has been executed successfully. 
