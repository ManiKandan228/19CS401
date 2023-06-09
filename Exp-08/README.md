# Exp-08-CONSTRUCTOR & DESTRUCTOR IN DERIVED CLASS 

### PROGRAM STATEMENT:-
Write a C++ program to pass the string "Shiva" to the parameterized constructor of a base class 
through a derived class constructor

### PROGRAM:-
```
#include<iostream> 
using namespace std; 
class Parent 
{ 
    public: 
        Parent() 
        { 
            cout<<"The name passed to the base class is Shiva"<<endl; 
        } 
}; 
class child:public Parent 
{ 
    public: 
        child() 
        { 
            cout<<"The name Shiva is passed through the derived class constructor"<<endl; 
        } 
}; 
int main() 
{ 
      child c; 
} 
```
### OUTPUT:-
![image](https://github.com/ManiKandan228/19CS401/assets/119160414/86a96494-aa7f-4019-ab7c-ed26feabdfe5)

### RESULT:-
Thus, the C++ program has been executed successfully. 
