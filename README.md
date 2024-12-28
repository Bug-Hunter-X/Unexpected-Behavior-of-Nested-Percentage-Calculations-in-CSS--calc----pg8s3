# Unexpected Behavior of Nested Percentage Calculations in CSS `calc()`

This repository demonstrates an uncommon issue related to the `calc()` function in CSS when using percentage values in nested contexts. The problem arises when percentage calculations within nested `calc()` functions do not correctly resolve relative to the innermost element's containing block.

## Bug Description

The main problem lies in how `calc()` handles percentage values when nested. While seemingly simple, the unexpected outcome can cause layout issues.

## Steps to Reproduce

1. Clone this repository.
2. Open `bug.css` to see the problematic code.
3. Open `bugSolution.css` to view the corrected code.
4. Observe the differences in layout between the two CSS files.

## Solution

The solution involves a careful understanding of the containing block and how `calc()` functions within a nested structure.  Understanding the context of the percentage values is crucial for obtaining the correct results. The corrected solution is presented in `bugSolution.css`.