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
  <li>Avoid Flag arguments</li>
  <li>Delete dead function that is never called</li>
</ul>

<h2>General</h2>
<u>
  <li>Minimize number and extent of extra languages</li>
  <li>DRY, instead use abstraction</li>
  <li>Check all boundary value, worst case, dont just believe your intuition</li>
  <li>Risky to override safety</li>

  
</u>

<h1>Having Problem in Understanding</h1>
<li>Obvious behaviour is unimplemented (pg 319)</li>
<li>Code at wrong level of abstraction (pg 321)</li>
<li>Base class depending on their derivatives (pg 322)</li>
