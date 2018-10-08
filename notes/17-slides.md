---
layout: slide
theme: white
transition: slide
---

<section data-markdown>

For the 1D Laplace problem ($\nabla^2 V = \partial^2 V/\partial x^2 = 0$), we can choose the following ansatz:

1. $k_0\,x$
2. $k_0\,x+k_1$
3. $k_0\,x^2+k_1\,x+k_2$
4. Can't tell

</section>

<section data-markdown>

<img src="./images/hogwarts.png" align="center" style="width: 800px";/>


</section>

<section data-markdown>
## Announcements

* Exam 1 graded
  * Average: 79.5
* HW 6 Problem 1 and 2
  * On your exam, you will see the grade you will receive if you choose to do problem 1 and 2
  * You need to collect your exam to do these problems!

</section>


<section data-markdown>

## Exam 1 Distribution

<img src="./images/exam1grades.png" align="center" style="width: 800px";/>


</section>

<section data-markdown>

## Exam 1 (re)Distribution*


<img src="./images/exam1grades_corr.png" align="center" style="width: 800px";/>


</section>

<section data-markdown>

<img src="./images/wamps_gre.png" align="center" style="width: 1000px";/>

</section>


<section data-markdown>

<img src="./images/cubical_lattice.png" align="center" style="width: 300px";/>


If you put a positive test charge at the center of this cube of charges, could it be in stable equilibrium?

1. Yes
2. No
3. ???

Note:
* CORRECT ANSWER: B

</section>

<section data-markdown>

### Method of Relaxation

<img src="./images/convergence_relax.png" align="center" style="width: 700px";/>


</section>

<section data-markdown>

Consider a function $f(x)$ that is both continuous and continuously differentiable over some domain. Given a step size of $a$, which could be an approximate derivative of this function somewhere in that domain? $df/dx \approx$

1. $f(x_i+a) - f(x_i)$
2. $f(x_i) - f(x_i-a)$
3. $\frac{f(x_i+a) - f(x_i)}{a}$
4. $\frac{f(x_i) - f(x_i-a)}{a}$
5. More than one of these


Note:
* Correct Answer: E (C and D)
</section>

<section data-markdown>
If we choose to use:

$$\dfrac{df}{dx} \approx \dfrac{f(x_i+a) - f(x_i)}{a}$$

Where are we computing the approximate derivative?

1. $a$
2. $x_i$
3. $x_i + a$
4. Somewhere else

Note:
* Correct Answer: D (it's halfway between)

</section>

<section data-markdown>

Taking the second derivative of $f(x)$ discretely is as simple as applying the discrete definition of the derivative,

$$f''(x_i) \approx \dfrac{f'(x_i + a/2) - f'(x_i - a/2)}{a}$$

Derive the second derivative in terms of $f$.

</section>

<section data-markdown>

With the approximate form of Laplace's equation:

$\dfrac{V(x_i+a) - 2V(x_i) + V(x_i-a)}{a} \approx 0$

What is a the appropriate estimate of $V(x_i)$?

1. ${1}/{2}(V(x_i+a)-V(x_i-a))$
2. ${1}/{2}(V(x_i+a)+V(x_i-a))$
3. ${a}/{2}(V(x_i+a)-V(x_i-a))$
4. ${a}/{2}(V(x_i+a)+V(x_i-a))$
5. Something else

Note:
* Correct answer: B

</section>

<section data-markdown>

To investigate the convergence, we must compare the estimate of $V$ before and after each calculation. For our 1D relaxation code, $V$ will be a 1D array. For the kth estimate, we can compare $V_k$ against its previous value by simply taking the difference.

Store this in a variable called ``err``. What is the type for ``err``?

1. A single number
2. A 1D array
3. A 2D array
4. ???

Note:
* Correct Answer: B

</section>
