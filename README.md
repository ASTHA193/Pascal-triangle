# Pascal-triangle
A different approach for the pascal triangle pattern problem .
## Introduction
All values outside the triangle are considered zero (0).The first row is 0 1 0 whereas only 1 acquire a space in pascal's triangle, 0s are invisible. Second row is acquired by adding (0+1) and (1+0).The output is sandwiched between two zeroes. The process continues till the required level is achieved. <br/>
Pascal's triangle can be derived using binomial theorem.We can use combinations and factorials to achieve this . <br/>
![](https://www.tutorialspoint.com/learn_c_by_examples/images/pascals_triangle.jpg)
## Algorithm 
Assuming that we're well aware of factorials, we shall look into the core concept of drawing a pascal triangle in step-by-step fashion − <br/>

START <br/>
  Step  1 - Take number of rows to be printed, n . <br/>
  Step  2 - Make outer iteration I for n times to print rows <br/>
  Step  3 - Make inner iteration for J to (N - 1) <br/>
  Step  4 - Print single blank space " " <br/>
  Step  5 - Close inner loop. <br/>
  Step  6 - Make inner iteration for J to I <br/>
  Step  7 - Print nCr of I and J <br/>
  Step  8 - Close inner loop <br/>
  Step  9 - Print NEWLINE character after each inner iteration  <br/>
  Step 10 - Return <br/>
STOP <br/>

![link to the solution](https://github.com/ASTHA193/Pascal-triangle/blob/master/solution.c)
