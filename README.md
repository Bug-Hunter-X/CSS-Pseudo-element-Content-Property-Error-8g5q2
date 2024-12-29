# CSS Pseudo-element Content Property Error

This repository demonstrates a subtle but potentially problematic error related to the `content` property in CSS when used with `::before` or `::after` pseudo-elements.  Incorrectly using this property can lead to unexpected behavior and visual glitches.

The `bug.css` file shows the problematic code, while `solution.css` provides the corrected version.  The error stems from not properly quoting strings or escaping special characters when setting the generated content.  This can cause rendering errors or unexpected display of content.

This repository is useful for understanding potential pitfalls when manipulating generated content in CSS and for demonstrating the importance of proper string handling in this context. 