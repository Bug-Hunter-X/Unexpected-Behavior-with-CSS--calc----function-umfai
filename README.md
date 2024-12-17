# Unexpected Behavior with CSS `calc()` function
This repository demonstrates some uncommon issues that can arise when using the `calc()` function in CSS.  The `calc()` function is powerful, but requires careful attention to detail. Incorrect spacing, operator precedence, or unit mismatches can lead to unexpected results.

## Issues Covered
* **Incorrect Spacing:** Extra spaces within the `calc()` expression can cause parsing errors.
* **Operator Precedence:** Without proper parenthesis, the order of operations might not be what you expect.
* **Unit Mismatches:** Mixing units (or missing them entirely) leads to calculation errors.

## How to Reproduce
1. Clone this repository.
2. Open `bug.css` to see examples of the problematic code.
3. Open `bugSolution.css` to see corrected versions.
4. Inspect the results in your browser's developer tools.