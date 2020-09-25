# Limits Continued

## Example 1
Find lim<sub>x->0</sub> (sqrt(9 + x) - 3)/x


lim<sub>x->0</sub> (sqrt(9 + x) - 3)/x = lim<sub>x->0</sub> ((sqrt(9 + x) - 3)(sqrt(9 + x) + 3))/(x(sqrt(9 + x) + 3))

= lim<sub>x->0</sub> (x)/(x(srqt(9 + x) + 3))

= lim<sub>x->0</sub> (1)/((srqt(9 + x) + 3))

= lim<sub>x->0</sub> (1)/((srqt(9 + x) + 3))

= 1/6

## Example 2
Find lim<sub>x->-1</sub> (1/(3x + 1) + 1/2)/(x + 1)

lim<sub>x->-1</sub> (1/(3x + 1) + 1/2)/(x + 1) = lim<sub>x->-1</sub> ((1/(3x + 1) + 1/2)*2(3x + 1))/((x + 1) * 2(3x + 1))

= lim<sub>x->-1</sub> (3x + 3)/(2(x + 1)(3x + 1))

= lim<sub>x->-1</sub> 3/(2(3x + 1))

= -3/4

# Continuity
A function y = f(x) is continuous at a if the following conditions are met
+ lim<sub>x->a</sub> f(x) exists
+ f(a) is defined
+ lim<sub>x->a</sub> f(x) = f(a)

## Example 1
Consider y = f(x) = (x<sup>2</sup> - 1)/(x + 1)

This function is not continuous at x = -1 as it is not defined.

## Example 2
Consider y = f(x) = { 1/(x + 1) if x != -1, -2 if x = -1

This function is not continuous at x = -1 as lim<sub>x->-1</sub> f(x) != f(-1)

## Example 3
Consider y = f(x) = {(x<sup>2</sup> - 1)/(x + 1) if x != -1, 1/2 if x = -1

This function is not continuous at x = -1 as lim<sub>x->-1</sub> f(x) != f(-1)

## Continuity Rules
Consider f(x) and g(x) which are continuous at x = a, the following are also continuous at a
+ f(x) + g(x)
+ f(x) - g(x)
+ f(x)g(x)
+ f(x)/g(x) if g(x) != 0
+ (f(x))<sup>n</sup> where n is a positive real nmber
+ A polynomial p(x) is continuous at all real numbers.
+ A rational function is continuous at any number which is in the domain of the rational function
