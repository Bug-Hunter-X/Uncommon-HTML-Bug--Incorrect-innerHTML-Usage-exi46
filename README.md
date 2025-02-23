# Uncommon HTML Bug: Incorrect innerHTML Usage

This repository demonstrates a subtle but problematic error in using `innerHTML` in HTML.  The code attempts to prepend new content, but due to how `innerHTML` works, it can lead to unexpected behavior or duplication of content in some cases, particularly with complex DOM structures.

The `bug.html` file shows the incorrect implementation, and `bugSolution.html` offers a correct and more robust alternative.

## Bug Description
The issue arises from appending to `innerHTML` instead of using DOM manipulation methods like `insertBefore` or `appendChild`. The provided code directly manipulates the `innerHTML`, leading to unexpected behavior and potential layout issues. The solution demonstrates how to fix it correctly using standard DOM methods.