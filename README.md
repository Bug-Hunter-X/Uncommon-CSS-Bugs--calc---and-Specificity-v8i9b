# Uncommon CSS Bugs
This repository demonstrates two uncommon bugs that can occur in CSS:

1. **Issues with `calc()`:** The `calc()` function can behave unexpectedly if used improperly, especially within contexts where the values it relies on are not yet defined. This is particularly true within flexbox layouts.
2. **Specificity Conflicts:** CSS specificity rules determine which styles are applied when multiple selectors target the same element.  Conflicting rules can lead to unexpected results if not carefully considered.

The `bug.css` file contains the problematic code. The solution is shown in `bugSolution.css`.