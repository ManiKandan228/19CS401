
# Exp-05 -INHERITANCE(BASE CLASS & DERIVED CLASSES)

### PROGRAM STATEMENT:-
Write a C++ program to read regno ,name & gender in one class and display the above details in 
another class using inheritance? 

### PROGRAM:-
```
#include <iostream> 
using namespace std; 
class A 
 { 
    public: 
        int regno; 
        string name,gender; 
        void data1() 
        { 
            cin>>regno>>name>>gender; 
        } 
}; 
class B:public A 
{ 
    public: 
    void data2() 
    { 
        cout<<"Register Number: "<<regno<<endl; 
        cout<<"Name: "<<name<<endl; 
        cout<<"Gender: "<<gender<<endl; 
    } 
 }; 
 int main() 
{
  B b; 
  b.data1(); 
  b.data2();
}   
```
### OUTPUT:-
![image](https://github.com/ManiKandan228/19CS401/assets/119160414/0805f852-a170-4ad1-96b2-8bc281f5bd05)

### RESULT:-
Thus, the C++ program has been executed successfully.  
