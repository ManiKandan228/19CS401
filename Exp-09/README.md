
# Exp-09-STACK ADT 

### PROGRAM STATEMENT:-
Write a CPP Program to insert five character elements in to Stack ADT (use STL for Stack) 

### PROGRAM:-
```
#include<iostream>  
#include<stck>  
using namespace std;  
int main()  
{  
  stack<char st;    
  char c;     
  int n;  
  cin>>n;  
  for(int i=0;i<n;i++)  
  {           
    cin>>c;                                
    st.push(c);  
  }  
  cout<<"Size of the stack: "<<n<<endl;    
  for(inti=0;i<n;i++)  
  {  
       cout<<st.top()<<"";         
       st.pop();  
   }  
   return 0;  
}  
```
### OUTPUT:-
![image](https://github.com/ManiKandan228/19CS401/assets/119160414/da0892c1-94a6-4359-8121-7eeb5382feaa)

### RESULT:-
Thus, the C++ program has been executed successfully. 
