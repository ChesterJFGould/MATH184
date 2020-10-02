# Differentiation
## Continuity and Differentiation
If f'(a) exists then f is differentiable at x = 0.
If f'(a) is differentiable at a then f(a) is continuous at x = a.

lim <sub>x -> a</sub> (f(x) - f(a)) = lim<sub>x -> a</sub> [(f(x) - f(a))/(x - a))(x - a)]

= 0

If f(x) is continuous at x = a, then f(x) may not be differentiable at x = a.
For example consider f(x) = |a|.

lim<sub>h -> 0<sup>+</sup></sub> f'(0) = 1

lim<sub>h -> 0<sup>-</sup></sub> f'(0) = -1

Therefore f'(x) is not continuous at x = a and f(x) is not continuous at x = a.

## Rules of Differentiation
+ d/dx c = 0, where c is a constant
+ d/dx (f(x) &plusmn; g(x)) = d/dx f(x) &pm d/dx g(x)
+ d/dx cf(x) = c(d/dx f(x)), where c is a constant
+ d/dx f(x)g(x) = g(x) * d/dx f(x) + f(x) * d/dx g(x) 
+ d/dx 1/f(x) = -(d/dx f(x)) / f<sup>2</sup> (x)
+ d/dx f(x)/g(x) = (g(x) * d/dx f(x) - f(x) * d/dx g(x)) / g<sup>2</sup> (x)
+ d/dx x<sup>n</sup> = nx<sup>n - 1</sup>, where n is a constant
+ d/dx c<sup>x</sup> = ln(c)c<sup>x</sup>, where c is a constant
+ d/dx log<sub>c</sub> x = 1/(x ln(c)), where c is a constant
+ d/dx f(g(x)) = f'(g(x)) * g'(x)
+ dy/dx = dy/du * du/dx, same as previous
+ d/dx sin(x) = cos(x)
+ d/dx cos(x) = -sin(x)
+ d/dx tan(x) = sec<sup>2</sup> (x)
+ d/dx cot(x) = -csc<sup>2</sup> (x)
+ d/dx sec(x) = sec(x)tan(x)
+ d/dx csc(x) = -csc(x)cot(x)
