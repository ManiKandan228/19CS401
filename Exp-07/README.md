

# Exp-07-PUBLIC, PRIVATE & PROTECTED INHERITANCE

### PROGRAM STATEMENT:-
Write a C++ program to get two numbers from two base classes and display the product of two 
numbers in the derived class.

### PROGRAM:-
```
#include <iostream> 
using namespace std; 
int a,b; 
class A  
{ 
    public: 
        void read() 
        { 
         cin>>a; 
        } 
}; 
class B  
{ 
    public: 
        void show() 
        { 
            cin>>b; 
        } 
}; 
class C : public A,public B 
 { 
       public:
       void draw() 
          { 
               cout<<"Product of two numbers = "<<a*b<<endl; 
          } 
 }; 
int main() 
{ 
    C c; 
    c.read(); 
    c.show(); 
    c.draw(); 
} 
```
### OUTPUT:-
![image](https://github.com/ManiKandan228/19CS401/assets/119160414/27b8cac0-c7f5-4413-a8e4-f08cf97d7b34)

### RESULT:-
Thus, the C++ program has been executed successfully. 
