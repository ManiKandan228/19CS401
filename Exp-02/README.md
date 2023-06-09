
# EXP-02-CLASS SCOPE AND ACCESSING CLASS MEMBERS & REFERENCE VARIABLES

### PROGRAM STATEMENT:-
 Write a C++ program to find out the total & average of 5 marks without using array(define 
the class methods outside the class) 
### PROGRAM: 
```
#include<iostream>
using namespace std;
class Mark
{
    public:
        int a,b,c,d,e;
        int total;
        float avg;
};
int main()
{
    Mark m;
    cin>>m.a>>m.b>>m.c>>m.d>>m.e;
    m.total=m.a+m.b+m.c+m.d+m.e;
    m.avg=(float)m.total/5;
    cout<<"total:"<<m.total;
    cout<<" avg:"<<m.avg;
    return 0;
} 
```
### OUTPUT:-
  ![image](https://github.com/ManiKandan228/19CS401/assets/119160414/64becba5-2cd7-4d34-b6c1-0e4812b9c458)

### RESULT:-
      Thus, the C++ Program has been executed successfully. 
