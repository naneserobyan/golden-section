 Golden Section Method 

This repository contains a Python implementation of the **Golden Section Search** method for finding the minimum of a function.

 What is the Golden Section Method?

The **Golden Section Search** is a technique to find the minimum (or maximum) of a **unimodal function** in a given interval `[a, b]`.  
It is called "golden" because it uses the **golden ratio** (≈ 0.618) to divide the interval in a way that efficiently reduces the search space.

The method does not require the derivative of the function, making it suitable for functions that are difficult to differentiate.

Accuracy / Tolerance

- In this implementation, the **tolerance** is defined as `eps = 0.5`.  
- The search stops when the length of the interval `[a, b]` becomes smaller than `eps`.  
- The smaller the `eps`, the more accurate the result.

Function Used
python
f(x) = x**4 - 8*x + 10
