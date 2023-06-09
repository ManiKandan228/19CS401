# Exp-16-QUEUE APPICATIONS USING LINKED LIST 

### PROGRAM STATEMENT:-
Write a C++ Program to implement FCFS Algorithm(to Read No of Process P1, P2 , P3 and 
P4 and its Burst Time from the user) & Find out Waiting Time of the Process?  

### PROGRAM:-
```
#include<iostream> 
using namespace std; int 
main() 
{ 
 int burst_time[4]; 
 for(int i =0;i<4;i++) 
 { 
    cin>>burst_time[i]; 
 } 
 int wt_time[4]; 
 wt_time[0]=0; 
 for(int i =1;i<4;i++) 
 { 
    wt_time[i]=burst_time[i-1]+wt_time[i-1]; 
 } 
 cout<<"Processes BT time WT time "<<endl; 
 for(int i=0;i<4;i++) 
 { 
    cout<<" "<<i+1<<" "<<burst_time[i]<<" "<<wt_time[i]<<endl; 
 } 
return 0; 
} 
```
### OUTPUT:-
![image](https://github.com/ManiKandan228/19CS401/assets/119160414/dfe0fceb-0807-4f03-8d20-a8aed07130f7)

### RESULT:-
Thus, the C++ program has been executed successfully. 
