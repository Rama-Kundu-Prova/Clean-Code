# Notes on Clean-Code
<h2>Comments</h2>
<ul>
  <li>Avoid inappropriate information like meta data authors, last modified date etc, include technical notes about code and design</li>
  <li>Update old comments or just remove</li>
  <li>Avoid redundancy. i.e. i++; //increment i</li>
  <li>Write best comment</li>
  <li>Remove commented out code</li>
</ul>

<h2>Functions</h2>
<ul>
  <li>No argument best, highest 3 arguments</li>
  <li>Avoid output arguments. i.e:  public void appendFooter(StringBuffer report) -> NOOOOOOOOO!  , report.appendFooter();->YESSSSSSSS!
</li>
  <li>Avoid Flag arguments i.e:
  <code>render(true)</code>
    Refractor as:
    <code> renderForSuite()<br>renderForSingleTest()</code>
    
  </li>
  <li>Delete dead function that is never called</li>
</ul>

<h2>General</h2>
<u>
  <li>Minimize number and extent of extra languages</li>
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
