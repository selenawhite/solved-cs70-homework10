Download Link: https://assignmentchef.com/product/solved-cs70-homework10
<br>
Family Planning

Mr. and Mrs. Brown decide to continue having children until they either have their first girl or until they have three children. Assume that each child is equally likely to be a boy or a girl, independent of all other children, and that there are no multiple births. Let <em>G </em>denote the numbers of girls that the Browns have. Let <em>C </em>be the total number of children they have.

<ul>

 <li>Determine the sample space, along with the probability of each sample point.</li>

 <li>Compute the joint distribution of <em>G </em>and <em>C</em>. Fill in the table below.</li>

</ul>

<table width="265">

 <tbody>

  <tr>

   <td width="68"> </td>

   <td width="67"><em>C</em>=1</td>

   <td width="65"><em>C</em>=2</td>

   <td width="65"><em>C</em>=3</td>

  </tr>

  <tr>

   <td width="68"><em>G</em>=0</td>

   <td width="67"> </td>

   <td width="65"> </td>

   <td width="65"> </td>

  </tr>

  <tr>

   <td width="68"><em>G</em>=1</td>

   <td width="67"> </td>

   <td width="65"> </td>

   <td width="65"> </td>

  </tr>

 </tbody>

</table>

<ul>

 <li>Use the joint distribution to compute the marginal distributions of <em>G </em>and <em>C </em>and confirm that the values are as you’d expect. Fill in the tables below.</li>

</ul>

<table width="439">

 <tbody>

  <tr>

   <td width="160">


    <table width="155">

     <tbody>

      <tr>

       <td width="95">P(<em>G</em>=0)</td>

       <td width="60"> </td>

      </tr>

      <tr>

       <td width="95">P(<em>G</em>=1)</td>

       <td width="60"> </td>

      </tr>

     </tbody>

    </table></td>

   <td width="279">


    <table width="274">

     <tbody>

      <tr>

       <td width="91">P(<em>C</em>=1)</td>

       <td width="91">P(<em>C</em>=2)</td>

       <td width="91">P(<em>C</em>=3)</td>

      </tr>

      <tr>

       <td width="91"> </td>

       <td width="91"> </td>

       <td width="91"> </td>

      </tr>

     </tbody>

    </table></td>

  </tr>

 </tbody>

</table>

<ul>

 <li>Are <em>G </em>and <em>C </em>independent?</li>

 <li>What is the expected number of girls the Browns will have? What is the expected number of children that the Browns will have?</li>

</ul>

CS 70, Fall 2018, HW 10                                                                                                                                                                        1

2        Will I Get My Package?

A delivery guy in some company is out delivering <em>n </em>packages to <em>n </em>customers, where <em>n</em>∈N, <em>n </em><em>&gt; </em>1. Not only does he hand a random package to each customer, he opens the package before delivering it with probability 1<em>/</em>2. Let <em>X </em>be the number of customers who receive their own packages unopened.

<ul>

 <li>Compute the expectation E(<em>X</em>).</li>

 <li>Compute the variance var(<em>X</em>).</li>

</ul>

3         Double-Check Your Intuition Again

<ul>

 <li>You roll a fair six-sided die and record the result <em>X</em>. You roll the die again and record the result <em>Y</em>.

  <ul>

   <li>What is cov(<em>X</em>+<em>Y</em><em>,X</em>−<em>Y</em>)?</li>

   <li>Prove that <em>X</em>+<em>Y </em>and <em>X</em>−<em>Y </em>are not independent.</li>

  </ul></li>

</ul>

For each of the problems below, if you think the answer is “yes” then provide a proof. If you think the answer is “no”, then provide a counterexample.

<ul>

 <li>If <em>X </em>is a random variable and var(<em>X</em>)= 0, then must <em>X </em>be a constant?</li>

 <li>If <em>X </em>is a random variable and <em>c </em>is a constant, then is var(<em>cX</em>)=<em>c</em>var(<em>X</em>)?</li>

 <li>If <em>A </em>and <em>B </em>are random variables with nonzero standard deviations and Corr(<em>A</em><em>,B</em>)= 0, then are <em>A </em>and <em>B </em>independent?</li>

 <li>If <em>X </em>and <em>Y </em>are not necessarily independent random variables, but Corr(<em>X</em><em>,Y</em>)= 0, and <em>X </em>and <em>Y </em>have nonzero standard deviations, then is var(<em>X</em>+<em>Y</em>)= var(<em>X</em>)+var(<em>Y</em>)?</li>

 <li>If <em>X </em>and <em>Y </em>are random variables then is E(max(<em>X</em><em>,Y</em>)min(<em>X</em><em>,Y</em>))=E(<em>XY</em>)?</li>

 <li>If <em>X </em>and <em>Y </em>are independent random variables with nonzero standard deviations, then is</li>

</ul>

Corr(max(<em>X</em><em>,Y</em>)<em>,</em>min(<em>X</em><em>,Y</em>))= Corr(<em>X</em><em>,Y</em>)?

CS 70, Fall 2018, HW 10