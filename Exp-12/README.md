# Exp-12-QUEUE APPLICATIONS

### PROGRAM STATEMENT:-
Write a C++ program to implement FCFS algorithm(no of.process p1,p2 and p3 
and its burst time are 10,5 & 8) find out waiting time & Turn Around time of the the process? 

### PROGRAM:-
```
#include<iostream> 
using namespace std; 
int main() 
{ 
 int i,wt[10], bt[10],tat[10], tot_wt=0,tot_tat=0; 
 bt[0]=10; 
 bt[1]=5; 
 bt[2]=8; 
 wt[0]=0; 
 for(i=1;i<3;i++) 
 { 
   wt[i]=wt[i-1]+bt[i-1]; 
   tot_wt+=wt[i]; 
 } 
 for(i=0;i<3;i++) 
 { 
   tat[i]=wt[i]+bt[i]; 
   tot_tat+=tat[i]; 
 } 
 cout<<"Processes BT time WT time TA time"<<endl; 
 for(i=0;i<3;i++) 
 {
    cout<<" "<<i+1<<" "<<bt[i]<<" "<<wt[i]<<" "<<tat[i]<<endl; 
 } 
}
```
### OUTPUT:-
![image](https://github.com/ManiKandan228/19CS401/assets/119160414/2fdffa08-7d67-4dee-8813-249421b4456b)

### RESULT:-
Thus, the C++ program has been executed successfully. 
