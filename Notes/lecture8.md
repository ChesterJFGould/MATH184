# Derivatives

## Velocity
For a given position function s(t), velocity is given by lim<sub>t->t<sub>0</sub></sub> (s(t) - s(t<sub>0</sub>))/(t - t<sub>0</sub>).

## Slope of a tangent line
The slope of the tangent line to the graph of y = f(x) at a point P(a, f(a)) is defined as the following.

lim<sub>x->a</sub> (f(x) - f(a))/(x - a)

## Definition
The derivative of f(x) at a number a is denoted by f '(a), and is defined by the following.

f'(a) = lim<sub>x->a</sub> (f(x) - f(a))/(x - a)

This can also be expressed as the following.

let h = x - a, then x = a + h

f'(a) = lim<sub>h->0</sub>(f(a + h) - f(a))/h

If f'(a) exists, then the line tangent to the graph of y = f(x) at the point (a, f(a)) is given by the following.

y - f(a) = f'(a)(x - a)

## Notation
f' = f'(x) = df/dx = d/(dx)(f)

## Example 1
let y = f(x) = 3x<sup>2</sup> + 2x - 1

Find f'(a)

f'(a) = lim<sub>h->0</sub> (f(a + h) - f(a))/h

= lim<sub>h->0</sub> ((3(a + h)<sup>2</sup> + 2(a + h) - 1) - (3a<sup>2</sup> + 2a - 1))/h

= lim<sub>h->0</sub> (3(a<sup>2</sup> + 2ah + h<sup>2</sup>) + 2a + 2h - 1 - 3a<sup>2</sup> - 2a + 1)/h

= lim<sub>h->0</sub> (6ah + 6h<sup>2</sup>) + 2h)/h
 
= lim<sub>h->0</sub> (6a + 6h + 2)

= 6a + 2

## Example 2
let f(x) = 1/(2x - 1)

Find f'(x) using the definition of the derivative

f'(x) = lim<sub>h->0</sub> ((1/(2(x + h) - 1)) - (1/(2(x) - 1)))/h

= lim<sub>h->0</sub> (((1/(2(x + h) - 1)) - (1/(2(x) - 1)))(2(x + h) - 1)(2x - 1))/(h(2(x + h) - 1)(2x - 1))

= lim<sub>h->0</sub> ((2x - 1) - (2(x + h) - 1))/(h(2(x + h) - 1)(2x - 1))

= lim<sub>h->0</sub> (-2h)/(h(2(x + h) - 1)(2x - 1))

= lim<sub>h->0</sub> (-2)/((2(x + h) - 1)(2x - 1))

= (-2)/((2(x) - 1)(2x - 1))

= -2/(2x - 1)<sup>2</sup>

Now find the equation of the tangent line at a point (-1, f(-1))

y = f'(-1)(x - -1) + f(-1)

= (-2(-1))/(2(-1) - 1)<sup>2</sup>(x + 1) + 1/(2(-1) - 1)

= 2/9(x + 1) + 1/3

## Relating f' to f
Consider y = f(x).
+ f'(a) = 0 iff the tangent line is horizontal.
+ f'(x) > 0 iff f(x) is increasing
+ f'(x) < 0 iff f(x) is decreasing

## Graphs of f and f'
Take a look at [these](https://www.desmos.com/calculator/ofzljtxlqr) graphs.
Look for the relationship between f' (the blue line) and f (the red line).
