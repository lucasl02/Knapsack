# Knapsack
This project using lpsolve was conducted regarding on a hypothetical scenario: 
  
Suppose you have 100 unique objects with various values, weights and volumes.

Suppose object i (where 1 ≤ i ≤ 100) has the following value, weight and volume:
value = floor(50+41 cos( 14i ) dollars
weight = floor(22+13 cos( 5i+1 )) kg [typo corrected 1/8/23 1:14 PM]
volume =floor(25+19 cos( 4i-2)) liters

[The floor function truncates a real value x to the largest integer less than or equal to x.

For example, floor(3.2)=3, and floor(3)=3.]

Suppose you have a container that has a weight capacity of 200 kg and volume capacity of 200 liters.

(a) What objects should you put into the container to maximize the total value? Are any constraints binding?

(b) What if we put a lower bound on the number of objects that we put into the container?  Discuss the solutions (not just the value of the objective function, but the set of objects chosen) for all possible lower bounds. Be sure to explain how you know you have considered all possible lower bounds.

(c) Investigate how the total value of the solution changes if we change the weight and volume bounds. Consider a bunch of cases where the weight bound and volume bound are numerically equal (e.g., 300 kg and 300 liters, or 100 kg and 100 liters), so that the total value is a function of x, where the weight bound is x kg and the volume bound is x liters.  Make a table and plot of your results (in your plot, be sure to make it clear what data you have: there should be a definite marker (e.g., dot) for each data point).  Describe some key features of this function. Be sure to consider x large enough that your function becomes constant.
  
