# Round Robin Scheduling
Round Robin Scheduling is a CPU scheduling algorithm where each process is assigned a fixed time slot in a cyclic way. As the term is generally used, time slices (also known as time quanta) are assigned to each process in equal portions and in circular order, handling all processes without priority.  
My project here deals with computing the average turn around time and the average waiting time for a given number of processes, that are executed using Round Robin Scheduling.  
## Example
We consider three processes P1, P2 and P3, in that priority order, with run times 3, 4 and 3 units respectively, and all arriving at the same time. Supposing that the time quatum is 0, the processes will be executed as:  
P1 (at time 0) → P2 → P3 → P1 → P2 → P3 → P1 → P2 → P3 → P2 (finishing at time 10)  
Then,  
- P1 waiting time: 4
- P2 waiting time: 6
- P3 waiting time: 6  
Therefore average waiting time will be: (4+6+6)/3=5.33
