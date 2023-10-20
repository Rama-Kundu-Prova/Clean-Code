# Notes on Clean-Code
<h2>Comments</h2>
![Capture](https://github.com/Rama-Kundu-Prova/Clean-Code/assets/121850492/3bdfb6e3-a40a-468f-abbd-69793e902ccf)


<ul>
  <li>Avoid inappropriate information like meta data authors, last modified date etc, include technical notes about code and design</li>
  <li>Update old comments or just remove</li>
  <li>Avoid redundancy. i.e. i++; //increment i</li>
  <li>Write best comment</li>
  <li>Remove commented out code</li>
</ul>

<h2>Functions</h2>

![functionClean](https://github.com/Rama-Kundu-Prova/Clean-Code/assets/121850492/5015f488-9c36-4734-a297-d4b648b2b097)



<h2>General</h2>
<u>
  <li>Minimize number and extent of extra languages</li>
  <li>Implement Obvious behaviour</li>
  <li>DRY, instead use abstraction</li>
  <li>Check all boundary value, worst case, dont just believe your intuition</li>
  <li>Risky to override safety</li>
  <li>Burry dead code</li>
  
  <li>Variables and function should be defined close to where they are used</li>
  <li>Maintain consistency. i.e. <br>1)If you name a method processVerificationRequest,
then use a similar name, such as processDeletionRequest, for the methods that process
other kinds of requests.<br> 2) If within a particular function you use a variable named response to hold an
HttpServletResponse, then use the same variable name consistently in the other functions
that use HttpServletResponse objects.</li>

  
</u>

<h1>Having Problem in Understanding</h1>
<li>Code at wrong level of abstraction (pg 321)</li>
<li>Base class depending on their derivatives (pg 322)</li>
