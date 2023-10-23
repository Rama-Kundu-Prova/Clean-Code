# Notes on Clean-Code
<h2>Comments</h2>

![CommentClean (3)](https://github.com/Rama-Kundu-Prova/Clean-Code/assets/121850492/0c904bbb-3702-44cc-807c-ad1b7512088f)



<h2>Functions</h2>

![functionClean](https://github.com/Rama-Kundu-Prova/Clean-Code/assets/121850492/5015f488-9c36-4734-a297-d4b648b2b097)



<h2>General</h2>
<ol>
  <li>Minimize extra languages</li>
  <li>Implement Obvious behaviour</li>
  <li>Check boundary value</li>
  <li>Risky to override safety</li>
  <li>DRY, use abstraction</li>
  <li>Avoid wrong level abstraction</li>
  <li>Base class should not depend on derivatives</li>
  <li>Keep interface small and tight for loose coupling</li>
  <li>Variables and function should be defined close to where they are used</li>
  <li>Burry dead code</li>
  <li>Maintain consistency</li>
  <li>Remove clutter</li>
  <li>No artificial coupling</li>
  <li>Feature envy</li>
  <li>Avoid selector argument</li>
  <li>Avoid obscured content</li>
  <li>Misplaced responsibility</li>
  <li>Inappropriate static</li>
  <li>Use Explanatory Variables</li>
  <li>Function Names Should Say What They Do</li>
  <li>Understand the algorithm</li>
  <li>Make logical dependency physical, dependent module should not assume about the module it depends upon</li>
  <li>Prefer polymorphism to if-else or switch case</li>
  <li>Follow coding standard that the team uses</li>
  <li>Replace raw number and name with constant identifier</li>
  <li>Make decission precisely. Use integer while using currency</li>
  <li>Structure over convension</li>
  <li>Use less boolean inside a condition</li>
  <li>Avoid negetive conditional</li>
  <li>Function should do one thing</li>
  <li>Use temporal coupling when order of function must be followed</li>
  <li>Do not be arbitrary</li>
  <li>Encapsulate boundary condition. Instead using
    <code>level+1</code>
    Use
    <code>nextLevel=level+1</code>
  </li>
  <li>Function should descend only one level of abstraction</li>
  <li>Keep configuration data at higher level</li>
  <li>Avoid transitive negation</li>
  </ol>

  <h2>Java</h2>
  <ol>
  <li>Wildcard import is better than specific import</li>
   <li>Don't inherit constant</li>
   <li>Use Enum instead of constant</li>
   </ol>

   <h2>Names</h2>
   <ol>
     <li>Choose descriptive name</li>
     <li>Choose Names at the Appropriate Level of Abstraction</li>
     <li>Use Standard Nomenclature Where Possible</li>
     <li>Choose names that make the workings of a function or variable unambiguous</li>
     <li>Use Long Names for Long Scopes</li>
     <li>Names should not be encoded with type or scope information</li>
     <li>Don’t use a simple verb to describe a function that does more
than just that simple action. i.e.<br>
     <code>
       public ObjectOutputStream getOos() throws IOException {
if (m_oos == null) {
m_oos = new ObjectOutputStream(m_socket.getOutputStream());
}
return m_oos;
}
     </code>
      <br> Refractor the function name as <code>createOrReturnOos</code>
     </li>
   </ol>

   <h2>Tests</h2>
   <ol>
   <li>A test suite should test everything that could possibly break</li>
   <li>Coverage tools reports gaps in your testing strategy</li>
   <li>Don’t Skip Trivial Tests</li>
   <li>An Ignored Test Is a Question about an Ambiguity</li>
   <li>Test boundary condition</li>
   <li>Exhaustively Test Near Bugs</li>
   <li>Pattern of failed test cases can also help us in debug.<br>
i.e. we have wrote a program that add two integer, but when we are testing the result is like, (3, 5) = 15, (2, 7) = 14 or (5, 6) = 30. We can understand that we multiplied instead of summation. We need to check the equation again.</li>
<li>Looking at the code that is or is not executed by the passing tests gives clues to why the
failing tests fail.</li>
<li>Tests Should Be Fast</li>

     
   </ol>
  
  
 

  


