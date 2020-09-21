# Limits Continued

## One-sided limits
Suppose that a function f is defined for all x near a with x > a.
If f(x) is arbitrarily close to a number L for all x sufficiently close to a with x > a, we write this fact as lim<sub>x->a<sup>+</sup></sub> f(x) = L, and we say that the right hand limit of f(x) equals L as x approaches a (from the right).
The same is true for x < a, but this is called the left hand limit and is written as lim<sub>x->a<sup>-</sup></sub>.

### Example 1
Consider [the function](https://www.desmos.com/calculator/xuauawjccc) y = f(x) = { x<sup>2</sup> + 1 if x < 0, x if x >= 0.

lim<sub>x->0<sup>+</sup></sub> f(x) = 0

lim<sub>x->0<sup>-</sup></sub> f(x) = 1

### Normal limits and one-sided limits
Assume that f(x) is defined for all x near a, except possibly at a.
Then lim<sub>x->a</sub> f(x) = L if and only if lim<sub>x->a<sup>+</sup></sub> f(x) = lim<sub>x->a<sup>-</sup></sub> f(x) = L.

### Example 2
Let [the function]() f(x) = |x - 2|/(x - 2).

Evaluate lim<sub>x->2</sub> f(x).

lim<sub>x->2<sup>+</sup></sub> f(x) = lim<sub>x->2<sup>+</sup></sub> (x - 2)/(x - 2) = lim<sub>x->2<sup>+</sup></sub> 1 = 1, where x >= 2

lim<sub>x->2<sup>-</sup></sub> f(x) = lim<sub>x->2<sup>-</sup></sub> -(x - 2)/(x - 2) = lim<sub>x->2<sup>-</sup></sub> -1 = -1, where x < 2

## Limit Laws
+ lim<sub>x->a</sub> (f +- g) = lim<sub>x->a</sub> f +- lim<sub>x->a</sub> g
+ lim<sub>x->a</sub> (fg) = lim<sub>x->a</sub> f * lim<sub>x->a</sub> g
+ lim<sub>x->a</sub> (f/g) = lim<sub>x->a</sub> f / lim<sub>x->a</sub> g, where lim<sub>x->a</sub> g != 0
+ lim<sub>x->a</sub> (cf) = c * lim<sub>x->a</sub> f, where c is a constant
+ lim<sub>x->a</sub> (f)<sup>n</sup> = (lim<sub>x->a</sub> f)<sup>n</sup>, where n is a positive integer
+ lim<sub>x->a</sub> (c) = c, where c is a constant
+ lim<sub>x->a</sub> x = a
+ lim<sub>x->a</sub> (f(x))<sup>1/n</sup> = (lim<sub>x->a</sub> f(x))<sup>1/n</sup>, where n is a positive and even integer and the limit of f is positive

### Example 1
Suppose lim<sub>x->3</sub> f(x) = -1 and lim<sub>x->3</sub> g(x) = 5.
Find lim<sub>x->3</sub> (2g(x))/(f(x) - g(x)).

We know the limit of the numerator exists as lim<sub>x->3</sub> g(x) = 5.
But we must check if the limit of denominator is not 0.

lim<sub>x->3</sub> f(x) - lim<sub>x->3</sub> g(x) = -1 - 5 = -6 != 0

This means that lim<sub>x->3</sub> (2g(x))/(f(x) - g(x)) = -5/3.

### Limits and polynomials
Assume that p(x) and q(x) are polynomials.

lim<sub>x->a</sub>p(x) = p(a)

lim<sub>x->a</sub> p(x)/q(x) = p(a)/q(a) if q(a) != 0

### Example 2
Consider lim<sub>x->5</sub> (2x + 5)/(x<sup>2020</sup> - 1).
Obviously the denominator is not 0, therefore we can just evaluate the expression to 15/(5<sup>2020</sup> - 1)

### Example 3
Find lim<sub>x->2</sub>(x<sup>2</sup> - x - 2)/(x<sup>2</sup - 4).

We cannot just immediatly plug in 2 for x as the denominator would be 0.
Therefore we must factor the polynomials.

lim<sub>x->2</sub>(x<sup>2</sup> - x - 2)/(x<sup>2</sup> - 4) = ((x - 2)(x + 1))/((x - 2)(x + 2)) = (x + 1)/(x + 2).

Now we can evaluate it to become 3/4.
