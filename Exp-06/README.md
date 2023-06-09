
# Exp-06-PROTECTED MEMBERS & OVERRIDING

### PROGRAM STATEMENT:-
Write a program to implement protected member with fractional values? 

### PROGRAM:-
```
#include<iostream> 
using namespace std; 
class A 
{ 
    protected: 
        float a; 
    public: 
        void show() 
        { 
            cin>>a; 
        } 
}; 
class B:public A 
{ 
    public: 
        void view() 
        { 
            cout<<"The value of num is: "<<a<<endl; 
        } 
};
int main() 
{ 
    B b; 
    b.show(); 
    b.view(); 
} 
```
### OUTPUT:-
![image](https://github.com/ManiKandan228/19CS401/assets/119160414/cc1dd118-7f30-4d14-86a3-5c1e1f304f5a)

### RESULT:-
Thus, the C++ program has been executed successfully. 
