Simpson's 1/3rd rule using C language:-

In this rule, n must be EVEN.

It is used when it is very difficult to solve the given integral mathematically.
This rule gives approximation easily without actually knowing the integration rules.

Example :

Evaluate logx dx within limit 4 to 5.2.

First we will divide interval into six equal 
parts as number of interval should be even.

x    :  4     4.2   4.4   4.6   4.8  5.0  5.2
logx :  1.38  1.43  1.48  1.52  1.56 1.60 1.64

Now we can calculate approximate value of integral
using above formula:
     = h/3[( 1.38 + 1.64) + 4 * (1.43 + 1.52 + 
                      1.60 ) +2 *(1.48 + 1.56)]
     = 1.84
Hence the approximation of above integral is 
1.827 using Simpson's 1/3 rule.
