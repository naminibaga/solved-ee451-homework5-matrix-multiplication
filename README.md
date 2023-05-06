Download Link: https://assignmentchef.com/product/solved-ee451-homework5-matrix-multiplication
<br>
<h1>1             Matrix Multiplication</h1>

In the lecture and discussion, we discussed two approaches to compute matrix multiplication (<em>C </em>= <em>A</em>×<em>B</em>) using CUDA: (1) unoptimized implementation using global memory only and (2) block matrix multiplication using shared memory.

In this assignment, your task is implementing 1024 × 1024 matrix multiplication using these two approaches.

<ul>

 <li>Approach 1 (unoptimized implementation using global memory only):

  <ul>

   <li>Name this program as ‘p1.cu’</li>

   <li>The value of each element of <em>A </em>is 1</li>

   <li>The value of each element of <em>B </em>is 2</li>

   <li>Thread block configuration: 16 × 16</li>

   <li>Grid configuration: 64 × 64</li>

   <li>After computation, print the value of <em>C</em>[451][451]</li>

  </ul></li>

 <li>Approach 2 (block matrix multiplication using shared memory):

  <ul>

   <li>Name this program as ‘p2.cu’</li>

   <li>The value of each element of <em>A </em>is 1</li>

   <li>The value of each element of <em>B </em>is 2</li>

   <li>Thread block configuration: 32 × 32</li>

   <li>Grid configuration: 32 × 32</li>

   <li>More details of this algorithm can be found in the paper ‘Matrix Multiplication with CUDA’ under the ‘Readings’ category of blackboard.</li>

   <li>After computation, print the value of <em>C</em>[451][451]</li>

  </ul></li>

 <li>Report: measure the execution time of the kernel of Approach 1 and Approach 2, respectively. Briefly discuss your observations.</li>

</ul>

2