# CSS calc() function nested calculation bug

This repository demonstrates a bug in the CSS `calc()` function where nested calculations are not evaluated correctly.  The issue arises when attempting to nest `calc()` functions within each other. This can lead to unexpected results in the rendering of elements.

The `bug.css` file contains the problematic code, and `bugSolution.css` provides the correct implementation.

## Bug Description

When using nested `calc()` functions, the browser fails to properly evaluate the inner `calc()` function before evaluating the outer `calc()` function. This leads to incorrect calculations and unexpected layout issues.  The problem is demonstrated in `bug.css`.  The correct solution simplifies the expression into a single `calc()` function, as shown in `bugSolution.css`.