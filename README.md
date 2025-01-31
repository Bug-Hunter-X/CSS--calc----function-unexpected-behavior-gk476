# CSS `calc()` Function Unexpected Behavior

This repository demonstrates a common issue encountered when using the `calc()` function in CSS.  The issue arises from inconsistent unit usage and unexpected percentage calculations within `calc()`. The `bug.css` file showcases the problem.  The `bugSolution.css` file provides the corrected CSS to address these issues. 

## Problem

The `calc()` function, while powerful, can produce unexpected results if units are not handled consistently. Mixing percentages and pixels without careful consideration can lead to unexpected layout behavior. This is demonstrated in the `bug.css` file. 

## Solution

The solution involves ensuring consistent unit usage within the `calc()` function.  Using the same unit throughout the calculation avoids potential conflicts and ensures predictable results. See `bugSolution.css` for the corrected code.