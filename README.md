# CSS `calc()` Function Error with Dynamic Parent Container Sizes

This repository demonstrates a common error when using the CSS `calc()` function with percentages that depend on parent container sizes that are not yet determined.

The `bug.css` file contains the problematic code. The `bugSolution.css` shows a possible solution.

**Problem:** Using `calc()` with percentages dependent on dynamically sized parents causes unpredictable rendering.

**Solution:** Ensure that all parent container sizes are resolved before using `calc()` with percentage-based calculations.  You might need to use alternative layout techniques or JavaScript to ensure proper sizing before applying `calc()`.