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
          
---
<table>
  <tr>
    <th>Random number</th>
    <th>4-bit value</th>
    <th> Result</th>
  </tr>
  <tr>
    <td>0</td>
    <td>0011</td>
    <td>0100</td>
  </tr>
  <tr>
    <td>1</td>
    <td>1010</td>
    <td>0011</td>
  </tr>
  <tr>
    <td>2</td>
    <td>0101</td>
    <td>0110</td>
  </tr>
  <tr>
    <td>3</td>
    <td>1100</td>
    <td>0001</td>
  </tr>
</table> 
