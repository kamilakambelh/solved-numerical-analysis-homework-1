Download Link: https://assignmentchef.com/product/solved-numerical-analysis-homework-1
<br>



<ul>

 <li>To get full credit, <em>you must write down sufficient intermediate steps</em>, only giving the final answer earns you no credit!</li>

 <li>Please make sure that your handwriting is recognizable, otherwise you only get partial credit for the recognizable part.</li>

</ul>

<ol>

 <li>Consider the bisection method starting with the ini-tial interval [1<em>.</em>5<em>,</em>3<em>.</em>5]. In the following questions “the interval” refers to the bisection interval whose width changes across different loops.

  <ul>

   <li>What is the width of the interval at the <em>n</em>th step?</li>

   <li>What is the maximum possible distance between the root <em>r </em>and the midpoint of the interval?</li>

  </ul></li>

 <li>In using the bisection algorithm with its initial in-terval as [<em>a</em><sub>0</sub><em>,b</em><sub>0</sub>], we want to determine the root with its <em>relative </em>error no greater than . Assume <em>a</em><sub>0 </sub><em>&gt; </em></li>

</ol>

Prove that the number of steps <em>n </em>must satisfy

<em>.</em>

<ul>

 <li>Perform four iterations of Newton’s method for thepolynomial equation <em>p</em>(<em>x</em>) = 4<em>x</em><sup>3 </sup>− 2<em>x</em><sup>2 </sup>+ 3 = 0 with the starting point <em>x</em><sub>0 </sub>= −1. Use a hand calculator and organize results of the iterations in a table.</li>

</ul>

<ol>

 <li>Consider a variation of Netwon’s method in whichonly the derivative at <em>x</em><sub>0 </sub>is used,</li>

</ol>

<em>.</em>

Find <em>C </em>and <em>s </em>such that

<em>.</em>

<ol>

 <li>Within (), will the iteration <em>x<sub>n</sub></em><sub>+1 </sub>= tan<sup>−1 </sup><em>x<sub>n </sub></em>converge?</li>

 <li>Let <em>p &gt; </em> What is the value of the following continued fraction?</li>

</ol>

Prove that the sequence of values converges. (Hint: this can be interpreted as <em>x </em>= lim<em><sub>n</sub></em><sub>→∞ </sub><em>x<sub>n</sub></em>, where , and so forth.

Formulate <em>x </em>as a fixed point of some function.)

<ul>

 <li>What happens in problem II if <em>a</em><sub>0 </sub><em>&lt; </em>0 <em>&lt; b</em><sub>0</sub>? Derive an inequality of the number of steps similar to that in II. In this case, is the relative error still an appropriate measure?</li>

 <li>(∗) Consider solving <em>f</em>(<em>x</em>) = 0 by Newton’s method with the starting point <em>x</em><sub>0 </sub>close to a root of multiplicity <em>k</em>. We assume that <em>f </em>∈C<em><sup>k</sup></em><sup>+1</sup>. Note that <em>α </em>is a zero of multiplicity <em>k </em>of the function <em>f </em>iff <em>f</em><sup>(<em>k</em>)</sup>(<em>α</em>) 6= 0; ∀<em>i &lt; k, f</em><sup>(<em>i</em>)</sup>(<em>α</em>) = 0<em>.</em>

  <ul>

   <li>How can a multiple zero be detected by examining the behavior of the points (<em>x<sub>n</sub>,f</em>(<em>x<sub>n</sub></em>))?</li>

   <li>Prove that if <em>r </em>is a zero of multiplicity <em>k </em>of the function <em>f</em>, then quadratic convergence in Newton’s iteration will be restored by making this modification:</li>

  </ul></li>

</ul>

<em>.</em>

<ol>

 <li>(∗) Analysis of the secant method for a root of multiplicity <em>k </em>by assuming that it converges.

  <ul>

   <li>Prove that if <em>r </em>is a zero of multiplicity <em>k &gt; </em>1 of the function <em>f</em>, the secant method only has linear convergence.</li>

   <li>Use the same argument to show that the convergence rate of the secant method is .</li>

  </ul></li>

</ol>

Each of the first six problems weighs 5 points. Each of the other problems weighs 10 points. In particular, the last two problems are for extra credit and you do not have to solve them. However, <em>special students </em>such as my graduate students who audit this class have to solve all problems.

<h1>2           C++ programming</h1>

<ol>

 <li>Implement the bisection method in C++. Test your program on these functions and intervals.

  <ul>

   <li><em>x</em><sup>−1 </sup>− tan<em>x </em>on [0<em>,</em>],</li>

   <li><em>x</em><sup>−1 </sup>− 2<em><sup>x </sup></em>on [0<em>,</em>1],</li>

   <li>2<sup>−<em>x </em></sup>+ <em>e<sup>x </sup></em>+ 2cos<em>x </em>− 6 on [1<em>,</em>3],</li>

   <li>(<em>x</em><sup>3</sup>+4<em>x</em><sup>2</sup>+3<em>x</em>+5)<em>/</em>(2<em>x</em><sup>3</sup>−9<em>x</em><sup>2</sup>+18<em>x</em>−2) on [0<em>,</em>4].</li>

  </ul></li>

 <li>Implement Newton’s method in C++ to solve the equation <em>x </em>= tan<em>x</em>. Find the roots near 4<em>.</em>5 and 7<em>.</em></li>

 <li>Implement the secant method in C++. Test your program on the following functions and initial values.</li>

</ol>

1

<ul>

 <li>sin(<em>x/</em>2) − 1 with,</li>

 <li><em>e<sup>x </sup></em>− tan<em>x </em>with <em>x</em><sub>0 </sub>= 1<em>,x</em><sub>1 </sub>= 1<em>.</em>4,</li>

 <li><em>x</em><sup>3 </sup>− 12<em>x</em><sup>2 </sup>+ 3<em>x </em>+ 1 with <em>x</em><sub>0 </sub>= 0<em>,x</em><sub>1 </sub>= −0<em>.</em></li>

</ul>

You should play with other initial values and (if you get different results) think about the reasons.

Each of the above three coding assignments weighs 10 points. The total number of points of this homework without extra credit is thus 5 × 6 + 10 + 10 × 3 = 70. <strong>IMPORTANT</strong>:

<ul>

 <li>Under the signature of your function in .m file, you must clearly state

  <ul>

   <li>the purpose of this C++ function,</li>

   <li>the meaning of each input parameter,</li>

   <li>preconditions on each input parameter,</li>

   <li>the meaning of each output parameter,</li>

   <li>postconditions on each output parameter.</li>

  </ul></li>

 <li>You must present in your solution your C++ code and corresponding test results.</li>

 <li>You need to send your source code to the course email <a href="/cdn-cgi/l/email-protection" class="__cf_email__" data-cfemail="dd93a8b09cadadafb2a5b4b0bca9b4b2b39decebeef3beb2b0f3">[email protected]</a></li>

</ul>

<h1>3           Extra credits</h1>

Additional 10% credits will be given to you if you typeset your solutions in L<sup>A</sup>TEX. You are welcome to use the L<sup>A</sup>TEX template available on my webpage. You can also get partial extra credit for typesetting solutions of <em>some </em>problems.

<strong>Note</strong>: If you choose to typeset your solutions in L<sup>A</sup>TEX, you still need to turn in a hard copy in class. In addition, please upload your latex source (.tex), supporting files, and C++ program in a single zip file (<strong>format</strong>: YourName_Homework1.zip) to the course email <a href="/cdn-cgi/l/email-protection" class="__cf_email__" data-cfemail="ce80bba38fbebebca1b6a7a3afbaa7a1a08efff8fde0ada1a3e0">[email protected]</a>

<h1>4           Reading</h1>

Download the electronic version of the following book from the library website:

<ul>

 <li>Numerical Analysis by W. Gautschi, 2nd Edition. ISBN: 978-0-8176-8259-0.</li>

</ul>

The above book will be referred to as NAG2012 in the rest of this class. Students who are eager to learn are encouraged to read pages 55-112 and 159-195.

<strong>Note</strong>: If you are a special student, you have to print out these pages and read the text before this semester ends. Otherwise you don’t have to do it.