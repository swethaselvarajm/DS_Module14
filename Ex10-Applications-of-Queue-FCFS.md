# Ex10 Applications of Queue – FCFS
## DATE:
## AIM:
To write a C function to calculate the turnaround time of each process given their burst time and waiting time in First Come first Serve scheduling algorithm.
## Algorithm
1. Initialize arrays for process IDs, burst times, waiting times, and turnaround times.
2. For each process, calculate the turnaround time as:
turnaround_time[i] = burst_time[i] + waiting_time[i]
3. Store the calculated turnaround time in the tat array.
4. Repeat for all processes.
5. Display the process details including burst time, waiting time, and turnaround time.

## Program:
```
/*
Program to find and display the priority of the operator in the given Postfix expression
Developed by: SWETHA S
RegisterNumber:  212222230155
*/
```
```
/*
int turnaroundtime( int proc[], int n,int burst_time[], int wait_time[], int tat[]) {
   // calculating turnaround time by adding
   // burst_time[i] + wait_time[i]
   int i;
   for ( i = 0; i < n ; i++)
   tat[i] = burst_time[i] + wait_time[i];
   return 0;
}
*/
```
## Output:

<img width="700" height="597" alt="image" src="https://github.com/user-attachments/assets/7e684a46-8f89-4bea-9e17-73c9f8e25f1b" />


## Result:
Thus, the C function to calculate the turnaround time of each process given their burst time and waiting time in First Come first Serve scheduling algorithm is implemented successfully.
