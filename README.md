Download Link: https://assignmentchef.com/product/solved-cs40032-assignment-1-%ce%bb-calculus
<br>
: Please solve the questions using pen and paper and scan the images. Every image should contain your roll number and name.

<ol>

 <li>Fully parenthesize the following <em>λ</em>-expressions: <strong>[1.5 * 3 = 4.5]</strong>

  <ul>

   <li><em>λx. x z λy. x y</em></li>

   <li>(<em>λx. x z</em>) <em>λy. w λw. w y z x</em></li>

   <li><em>λx. x y λx. y x</em></li>

  </ul></li>

 <li>Mark the free variables in the following <em>λ</em>-expressions: <strong>[1.5 * 3 = 4.5]</strong>

  <ul>

   <li><em>λx. x z λy. x y</em></li>

   <li>(<em>λx. x z</em>) <em>λy. w λw. w y z x</em></li>

   <li><em>λx. x y λx. y x</em></li>

  </ul></li>

 <li>Prove the following using encoding in <em>λ</em>-calculus: <strong>[2 * 8 = 16]</strong>

  <ul>

   <li><em>NOT</em>(<em>NOT TRUE</em>) = <em>TRUE</em></li>

  </ul></li>

</ol>

Given:

<em>NOT </em>= <em>λx. </em>((<em>x FALSE</em>) <em>TRUE</em>)

<em>TRUE </em>= <em>λx. λy. x</em>

<em>FALSE </em>= <em>λx. λy. y</em>

<ul>

 <li><em>OR FALSE TRUE </em>= <em>TRUE</em></li>

</ul>

Given:

<em>OR </em>= <em>λx. λy. </em>((<em>x TRUE</em>) <em>y</em>)

<em>TRUE </em>= <em>λx. λy. x</em>

<em>FALSE </em>= <em>λx. λy. y</em>

<ul>

 <li><em>SUCC </em>2 = 3</li>

</ul>

Given:

<ul>

 <li>= <em>λf. λy. f </em>(<em>f y</em>)</li>

 <li>= <em>λf. λy. f </em>(<em>f </em>(<em>f y</em>))</li>

</ul>

<em>SUCC </em>= <em>λz. λf. λy. f </em>(<em>z f y</em>)

<ul>

 <li>(<em>Y FACT</em>) 2 = 2</li>

</ul>

Given:

<em>Y </em>= <em>λf. </em>(<em>λx. f </em>(<em>x x</em>)) (<em>λx. f </em>(<em>x x</em>))

<em>FACT </em>= <em>λf. λn. IF n </em>= 0 <em>THEN </em>1 <em>ELSE n </em><sup>∗ </sup>(<em>f </em>(<em>n </em>− 1))

<ul>

 <li>Given: <em>mul </em>= <em>λn.λm.λx. </em>(<em>n </em>(<em>m x</em>))</li>

</ul>

Solve: <em>mul </em>3 3

<ul>

 <li>Solve: <em>add </em>8 1</li>

</ul>

Given: <em>add </em>= <em>λn.λm.λf.λx. n f </em>(<em>m f x</em>)

<ul>

 <li><em>IF FALSE THEN x ELSE y </em>= <em>y</em></li>

</ul>

Given:

<em>IF a THEN b ELSE c </em>= <em>a b c</em>

<em>TRUE </em>= <em>λx. λy. x</em>

<em>FALSE </em>= <em>λx. λy. y</em>

<ul>

 <li>Prove: <em>add </em>and <em>mul </em>are commutative Given:</li>

</ul>

<em>mul </em>= <em>λn.λm.λx. </em>(<em>n </em>(<em>m x</em>))

<em>add </em>= <em>λn.λm.λf.λx. n f </em>(<em>m f x</em>)

1