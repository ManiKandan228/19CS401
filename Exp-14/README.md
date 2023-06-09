# Exp-14-STACK APPLICATIONS USING LINKED LIST 

### PROGRAM STATEMENT:-
Write A C++ program for Postfix to Prefix Conversion using Stack Stl

### PROGRAM:-
```
#include<iostream> 
#include<stack> 
#include<string> 
#include<algorithm> 
using namespace std; 
int isoperator(char a) 
{ 
   if (a=='+' || a=='-' || a=='*' || a=='/') 
   { 
      return 1; 
   } 
  else 
   { 
      return 0; 
   } 
} 
int main() 
{ 
  string postfix,prefix; 
  stack <char> s; 
  cin>>postfix; 
  int n = postfix.length()-1;
  cout<<"Postfix to Prefix expression:"<<endl;
  for(int i=n;i>=0;i--) 
 { 
 if (isoperator(postfix[i])) 
 { 
    s.push(postfix[i]); 
 } 
 else 
 { 
     prefix += postfix[i]; 
     while(!s.empty() && s.top()=='#') 
       { 
       s.pop(); 
       prefix+=s.top(); 
       s.pop(); 
       } 
       s.push('#'); 
 } 
 } 
  reverse(prefix.begin(),prefix.end()); 
  cout<<prefix; 
  return 0; 
} 
```
### OUTPUT:-
![image](https://github.com/ManiKandan228/19CS401/assets/119160414/df3539c6-c166-4c61-99e0-50b83e86b03e)

### RESULT:-
Thus, the C++ program has been executed successfully. 
