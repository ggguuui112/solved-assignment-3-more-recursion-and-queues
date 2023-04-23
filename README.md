Download Link: https://assignmentchef.com/product/solved-assignment-3-more-recursion-and-queues
<br>
<em>Write pseudo-code not Java for problems requiring code. You are responsible for the appropriate level of detail.</em>

<em>Q1 and Q2 are intended to help you get comfortable with recursion by thinking about something familiar in a recursive manner. Q3 – Q4 are practice in working with nontrivial recursive functions. Q5 and Q6 deal with the idea of conversion between iteration and recursion.</em>

<ol>

 <li><strong>Write a recursive algorithm to compute <em>a+b</em>, where <em>a</em> and <em>b</em> are nonnegative integers.</strong></li>

</ol>




<ol start="2">

 <li><strong>Let A be an array of integers. Write a recursive algorithm to compute the average of the elements of the array. </strong>Solutions calculating the sum recursively, instead of the average, are worth fewer points.</li>

 <li><strong>A generalized Fibonacci function is like the standard Fibonacci function,, except that the starting points are passed in as parameters. Define the generalized Fibonacci sequence of f0 and f1 as the sequence gfib( f0, f1, 0), gfib(f0, f1, 1), gfib(f0, f1, 2), …, where</strong></li>

</ol>

<strong>gfib(f0, f1, 0) = f0 gfib(f0, f1, 1) = f1</strong>

<strong>gfib(f0, f1, n) = gfib(f0, f1, n-1) + gfib(f0, f1, n-2) if n&gt; 1</strong>

<strong> </strong>

<strong>Write a recursive method to compute gfib(f0,f1,n).</strong>

<ol start="4">

 <li><strong>Ackerman’s function is defined recursively on the nonnegative integers as follows:</strong></li>

</ol>

a(m, n) = n + 1                               if m = 0

a(m, n) = a(m-1, 1)                        if m  0, n = 0 a(m, n) = a(m-1, a(m, n-1))           if m  0, n  0

Using the above definition, show that a(2,2) equals 7.

<ol start="5">

 <li><strong>Convert the following recursive program scheme into an iterative version that does not use a stack. <em>f(n)</em> is a method that returns TRUE or FALSE based on the value of n, and <em>g(n)</em> is a method that returns a value of the same type as <em>n</em> (without modifying <em>n</em>).</strong></li>

</ol>

int rec(int n)

{

if ( f(n) == FALSE ) {

/* any group of statements that  do not change the value of n */         return (rec(g(n)));

}//end if     return (0); }//end rec

<ol start="6">

 <li><strong>Develop an ADT specification for a priority queue. A priority queue is like a FIFO queue except that items are ordered by some priority setting instead of time. In fact, you may think of a FIFO queue as a priority queue in which the time stamp is used to define priority.</strong></li>

</ol>