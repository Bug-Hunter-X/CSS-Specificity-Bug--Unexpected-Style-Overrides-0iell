# CSS Specificity Bug
This repository demonstrates a common issue in CSS: unexpected style overrides due to specificity problems.  The `bug.css` file contains the problematic code. The solution is provided in `bugSolution.css`.

**Problem:** The styles applied are not as expected due to the cascade and specificity of selectors. 

**Solution:**  The solution involves adjusting selectors, adding or removing the `!important` flag, or reorganizing CSS rules based on specificity rules. 