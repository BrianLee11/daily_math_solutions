<!--
date: 2026-07-07
day_of_week: Tuesday
topic: Algebra
subtopic: Completing the Square
source_type: textbook exercise
source_title: Calculus
source_author: James Stewart
source_edition: 8th edition
source_page: xxvii
source_section: Diagnostic Tests
-->

| Date | Day of week | Topic | Subtopic |
|---|---|---|---|
| 2026-07-07 | Tuesday | Algebra | Completing the Square |

# Rewrite by Completing the Square

## Problem

Rewrite the expression by completing the square.

$$
x^{2}+x+1
$$

## Answer

$$
\boxed{\left(x+\frac{1}{2}\right)^2+\frac{3}{4}}
$$

## Explanations

To complete the square means to find constants $b$ and $c$ such that

$$
x^{2}+x+1=(x+b)^2+c.
$$

| Equation | Reason |
|---|---|
| $x^{2}+x+1=(x+b)^2+c$ | target form |
| $\Leftrightarrow\quad x^{2}+x+1=x^{2}+2bx+b^{2}+c$ | expand $(x+b)^2$ |
| $\Rightarrow\quad 2b=1$ and $b^{2}+c=1$ | compare coefficients of like powers of $x$ |
| $\Rightarrow\quad b=\frac{1}{2}$ and $\left(\frac{1}{2}\right)^2+c=1$ | solve $2b=1$ |
| $\Rightarrow\quad b=\frac{1}{2}$ and $c=1-\frac{1}{4}$ | subtract $\frac{1}{4}$ from both sides |
| $\Rightarrow\quad b=\frac{1}{2}$ and $c=\frac{3}{4}$ | simplify |
| $\Rightarrow\quad x^{2}+x+1=\left(x+\frac{1}{2}\right)^2+\frac{3}{4}$ | substitute $b$ and $c$ |
| $\therefore\quad \left(x+\frac{1}{2}\right)^2+\frac{3}{4}$ | completed square form |

## What's the Use?

Completing the square is, in short:

> A technique for rewriting a quadratic expression into a form that is easier to understand and use.

For example,

$$
x^2+6x+5
$$

can be rewritten as

$$
x^2+6x+5=(x+3)^2-4.
$$

This new form reveals the structure of the expression more clearly.

---

### 1. Solving Quadratic Equations

Completing the square can be used to solve quadratic equations.

For example,

$$
x^2+6x+5=0
$$

can be rewritten as

$$
(x+3)^2-4=0.
$$

Then,

$$
(x+3)^2=4
$$

so

$$
x+3=\pm 2.
$$

Therefore,

$$
x=-1 \quad \text{or} \quad x=-5.
$$

This method is also used to derive the quadratic formula.

---

### 2. Finding the Vertex of a Parabola

Consider the quadratic function

$$
y=x^2+6x+5.
$$

By completing the square, we get

$$
y=(x+3)^2-4.
$$

In this form, the vertex is easy to identify:

$$
(-3,-4).
$$

So completing the square is very useful for understanding the graph of a parabola.

---

### 3. Finding Minimum or Maximum Values

From

$$
y=(x+3)^2-4,
$$

we know that

$$
(x+3)^2 \ge 0.
$$

The smallest value occurs when

$$
(x+3)^2=0.
$$

At that point,

$$
y=-4.
$$

Therefore, the minimum value of the function is

$$
-4.
$$

---

### 4. Rewriting the Equation of a Circle

Completing the square is also useful when rewriting the equation of a circle.

For example,

$$
x^2+y^2-6x+4y-3=0
$$

can be rewritten as

$$
(x-3)^2+(y+2)^2=16.
$$

In this form, the center and radius are immediately visible:

$$
\text{center}=(3,-2)
$$

and

$$
\text{radius}=4.
$$

---

### 5. Applications in Calculus, Probability, and Statistics

Completing the square also appears in more advanced mathematics.

For example,

$$
x^2+4x
$$

can be rewritten as

$$
x^2+4x=(x+2)^2-4.
$$

This type of transformation is useful in integration, Gaussian integrals, normal distributions, and exponential expressions.

In fact, completing the square is hidden inside the formula for the normal distribution.

---

## Summary

Completing the square is useful for:

- solving quadratic equations
- deriving the quadratic formula
- finding the vertex of a parabola
- finding minimum or maximum values
- rewriting equations of circles
- understanding later topics in calculus, probability, and statistics

In short:

> Completing the square is not just a calculation trick.  
> It is a way to reveal the hidden structure of a quadratic expression.

It is more of a mathematical transformation skill than a coding-test or algorithmic technique.



## Source

- Textbook: *Calculus*
- Author: James Stewart
- Edition: 8th edition
- Section: Diagnostic Tests
- Page: xxvii