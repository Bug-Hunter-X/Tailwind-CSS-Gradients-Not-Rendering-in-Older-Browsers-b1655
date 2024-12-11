# Tailwind CSS Gradients and Older Browser Compatibility

This repository demonstrates a common issue with using Tailwind CSS gradients in older browsers.  The problem arises because Tailwind's gradient utilities rely on the CSS `linear-gradient` function, which isn't universally supported across all browsers.  This can lead to gradients failing to render correctly, or not rendering at all.

The `bug.html` file shows the code with the issue. The `bugSolution.html` demonstrates a solution to this problem.