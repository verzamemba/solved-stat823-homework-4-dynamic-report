Download Link: https://assignmentchef.com/product/solved-stat823-homework-4-dynamic-report
<br>
<ol>

 <li>A total of 30 Masters students in a Statistics course were asked to state how long they take to finish their weekly homework.</li>

</ol>

The following is the reported time in hours:

2<em>,</em>3<em>,</em>1<em>.</em>5<em>,</em>3<em>.</em>5<em>,</em>4<em>,</em>3<em>,</em>1<em>,</em>3<em>,</em>2<em>,</em>3<em>.</em>5<em>,</em>4<em>,</em>3<em>,</em>2<em>.</em>5<em>,</em>2<em>.</em>5<em>,</em>2<em>,</em>2<em>,</em>1<em>.</em>5<em>,</em>2<em>,</em>2<em>,</em>3<em>,</em>3<em>,</em>

3<em>,</em>1<em>,</em>1<em>,</em>1<em>,</em>1<em>.</em>5<em>,</em>2<em>,</em>2<em>.</em>5<em>,</em>2<em>.</em>5<em>,</em>3

(a) Write your own R code (function) to calculate the sample mean without using the <em>mean</em>() R function then confirm

your answer using the <em>mean</em>() function

<sup>1 </sup>X<em>n</em>

<em>x</em>¯ =  <em> x<sub>i </sub>n </em><em>i</em>=1

(b) Write your own R code (function) to calculate the sample variance without using the <em>sd</em>() and <em>var</em>() R functions. You can use the <em>mean</em>() and <em>sum</em>() functions, then confirm your answer using the <em>var</em>() function

1  <em>n                             </em>

<h1>2                                                    X 2          2</h1>

<em>s </em>=      <em><sup>x</sup><sub>i </sub>− nx</em>¯  <em>n − </em>1 <em>i</em>=1

<ol start="2">

 <li>Caleb wishes to take <em>P </em>= $10<em>,</em>000 loan from a bank. The bank offers the loan at a monthly interest rate <em>r </em>= 3% for a period of <em>n </em>= 24 months. Calculate the monthly instalments <em>m </em>that Caleb will have to remit to the bank given that the principal is calculated as</li>

</ol>

1 <em>− </em>(1 + <em>r</em>)<em>−n</em>

<em>P </em>= <em>m</em>   

<em>r</em>

(Hint: First, make <em>m </em>the subject of the formula. That is, re-write the expression to obtain <em>m </em>= (<em>.</em>) then solve for <em>m</em>)

<em>r</em>

<em>m </em>= <em>P ∗</em>

1 <em>− </em>(1 + <em>r</em>)<em><sup>−n</sup></em>




<table width="632">

 <tbody>

  <tr>

   <td width="632"><strong>Proof: Not reqired</strong>2                                  1 <sub>X</sub><em><sup>n                         </sup></em>2<em>S                      </em>=          (<em>x<sub>i </sub>− x</em>¯)  <em>n − </em>1 <em>i</em>=11 <sub>X</sub><em><sup>n          </sup></em>2                             2 =  (<em><sup>x</sup><sub>i </sub>− </em>2<em>x<sub>i</sub>x</em>¯ + ¯<em>x </em>) <em>n − </em>1 <em>i</em>=11 X<em>n         </em>2                X<em>n                     </em>2=  <em><sup>x</sup><sub>i </sub>− </em>2<em>x</em>¯ <em>x<sub>i </sub></em>+ <em>nx</em>¯  <em>n − </em>1 <em>i</em>=1 <em>i</em>=1Notice that    <sup>¯         </sup>=               1 <sup>X<em>n </em></sup><em>X<sub>i </sub>⇒ </em><sup>X<em>n </em></sup><em>X<sub>i </sub></em>= <em>nX</em><sup>¯</sup><em>X n </em><em>i</em>=1                <em>i</em>=11  <em>n                                               </em>∴ <em>S</em><sup>2 </sup>=        <sup>X </sup><em>x                                 </em><em>n − </em>1 <em>i</em>=11 <sub>X</sub><em>n                                              </em>=          <em>x      </em> <em>n − </em>1 <em>i</em>=1=          <em>n − </em>1 <em>i</em>=1</td>

  </tr>

 </tbody>

</table>


