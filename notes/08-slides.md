---
layout: slide
theme: white
transition: slide
---

<section data-markdown>

Consider a cube of constant charge density centered at the origin.

**True or False**: I can use Gauss' Law to find the electric directly above the center of the cube.

1. True and I can argue how we'd do it.
2. True. I'm sure we can, but I don't see how to just yet.
3. False. I'm pretty sure we can't, but I can't say exactly why.
4. False and I can argue why we can't do it.

</section>

<section data-markdown>

## Announcements
* First week for clickers is this week
  - I will drop the 3 lowest clicker grades
- Homework 2 (due Wed.)
  - No need to do Problem 5 (will be problem 1 on HW 4)
  - BTW, I will drop your lowest homework grade

</section>

<section data-markdown>

What is the value of:

$$\int_{-\infty}^{\infty} x^2 \delta(x-2)dx$$

1. 0
2. 2
3. 4
4. $\infty$
5. Something else

Note:
* CORRECT ANSWER: C

</section>

<section data-markdown>

**Activity**: Compute the following integrals. Note anything special you had to do.

* Row 1-2: $\int_{-\infty}^{\infty} xe^x \delta(x-1)dx$
* Row 3-4: $\int_{\infty}^{-\infty} \log(x) \delta(x-2)dx$
* Row 5-6: $\int_{-\infty}^{0} xe^x \delta(x-1)dx$
* Row 6+: $\int_{-\infty}^{\infty} (x+1)^2 \delta(4x)dx$

Note:
* Give them 2-3 minutes to work on it and ask for what they did.

</section>

<section data-markdown>

Compute:

$$\int_{-\infty}^{\infty} x^2\delta(3x+5)dx$$

1. $25/3$
2. $-5/3$
3. $25/27$
4. $25/9$
5. Something else


Note:
* CORRECT ANSWER: C
* Use a u substitution.

</section>

<section data-markdown>
A point charge ($q$) is located at position $\mathbf{R}$, as shown. What is $\rho(\mathbf{r})$, the charge density in all space?

<img src ="./images/pt_charge_at_R.png" align="right" style="width: 300px";/>


1. $\rho(\mathbf{r}) = q\delta^3(\mathbf{R})$
2. $\rho(\mathbf{r}) = q\delta^3(\mathbf{r})$
3. $\rho(\mathbf{r}) = q\delta^3(\mathbf{R}-\mathbf{r})$
4. $\rho(\mathbf{r}) = q\delta^3(\mathbf{r}-\mathbf{R})$
5. Something else??

Note:
* CORRECT ANSWER: E
* This one is a curious one because a delta function is always positive, both C and D are correct.
* Expect most everyone to pick C

</section>

<section data-markdown>

What are the units of $\delta (x)$ if $x$ is measured in meters?

1. $\delta(x)$ is dimension less (‘no units’)
2. [$\mathrm{m}$]:      Unit of length
3. [$\mathrm{m}^2$]:    Unit of length squared
4. [$\mathrm{m}^{-1}$]:   1 / (unit of length)
5. [$\mathrm{m}^{-2}$]:   1 / (unit of length squared)

Note:
* CORRECT ANSWER: D
* Think about what the integral must produce.

</section>

<section data-markdown>

What are the units of $\delta^3(\mathbf{r})$ if the components of $\mathbf{r}$ are measured in meters?

1. [$\mathrm{m}$]:      Unit of length
2. [$\mathrm{m}^2$]:    Unit of length squared
3. [$\mathrm{m}^{-1}$]:   1 / (unit of length)
4. [$\mathrm{m}^{-2}$]:   1 / (unit of length squared)
5. None of these.

Note:
* CORRECT ANSWER: E
* Should be m^-3

</section>

<section data-markdown>

What is the divergence in the boxed region?

<img src ="./images/pt_charge_red_box.png" align="right" style="width: 400px";/>

1. Zero
2. Not zero
3. ???

Note:
* CORRECT ANSWER: A
* Just a check back in.
</section>
