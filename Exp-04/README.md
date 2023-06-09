
# Exp-04- C++ MEMBER FUNCTION

### PROGRAM STATEMENT:-
Write a C++ program to convert decimal into binary value using inline function.
  
### PROGRAM:-
```
#include <iostream> 
using namespace std; 
inline void dectobi(int a) 
 { 
      int i=1,j=a,binary=0; 
          for(j=a;j>0;j=j/2) 
         { 
              binary=binary+(a%2)*i;   
              i=i*10; 
              a=a/2; 
         } 
         cout<<"Binary Equivalent:"<<binary<<endl; 
         
 } 
int main() 
{ 
    int a; 
    cin>>a; 
    dectobi(a); 
    return 0; 
}
```
### OUTPUT:-
![image](https://github.com/ManiKandan228/19CS401/assets/119160414/994c3dc7-4ff1-41db-81ca-2a450ad057e5)

### RESULT:-
Thus, the C++ Program has been executed successfully.  

  
