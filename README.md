# Solver81 - Simple Linear Equation Solver for TI-81 Calculator

## About
I wrote this nugget my freshman year of high school to ~~get out of doing~~ verify solutions on my Algebra homework ;).  It lives over at [ticalc.org](https://www.ticalc.org/pub/81/basic/math/solver81.81) but also wanted to immortalize it here in my github repo as well. It was fun to stumble on this blast from the past and its probably one of the very first programs I ever wrote.  Its not unit-tested, so proceed with caution :P

 ## The Algorithm
Linear regression is a popular method used in statistics and machine learning for modeling the relationship between a dependent variable and one or more independent variables. In the case of a simple linear equation, where there is only one independent variable, linear regression can be used to find the best fit line for the data and thus solve the equation.  The TI-81 Solver allows you to input your relations in the `Y1` and `Y2` functions.  It then uses set points to compute the analyical solutions following the line of best-fits method:

1. Compute values for the independent variable (X) and dependent variable (Y).
2. Calculate the means of X and Y.
3. Calculate the variance of X and the covariance of X and Y.
4. Calculate the slope of the line (m) using the formula: m = covariance(X,Y) / variance(X).
5. Calculate the intercept of the line (b) using the formula: b = mean(Y) - m * mean(X).
6. Use the equation of the line (y = mx + b) to solve for the dependent variable given a value of the independent variable.
