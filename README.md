# qosf_mentornship_task_2
## This is my try at doing task 2 of qosf_mentorship screening task
libraries needed :-
  1. python3.
  2. qiskit .
  3. qiskit.visualization.
  4. array from numpy.
  5. random.\
We take a random number from the list <code>list1=[0,1,2,3]</code> using <code>random.choice(list1)</code>
<br>
We create a set of 4-bit numbers based on the random number.
<br>
A coresponding *QuantumCircuit* is created.
<br>
Few simple *gates* are applied to get a result.
<br>
The result is simulated using *Aer* simulator and is viewed on a histogram using <code>plot_histogram</code>
<br>
Here is you what you can expect:-
<br>
Random number       4-bit value     Result
---
<br>
   0                  0011           0100  
<br>
   1                  1010           0011               
<br>
   2                  0101           0110
<br>
   3                  1100           0001
