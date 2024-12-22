# CSS Background Clipping Bug

This repository demonstrates a subtle bug related to background color rendering in CSS when using the `inline-block` display property with a width constraint.  The issue arises when the content of an inline-block element exceeds its declared width, causing the background color to be clipped.

The `bug.css` file showcases the problem.  The solution, implemented in `solution.css`, addresses this by using techniques to ensure the background color extends appropriately, even when content overflows.