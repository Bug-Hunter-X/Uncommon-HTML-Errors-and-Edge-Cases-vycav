# Uncommon HTML Errors and Edge Cases

This repository showcases some uncommon errors that can occur in HTML code.  These errors are often subtle and might not immediately throw a JavaScript error, but can lead to unexpected behavior or silent failures.

The `bug.html` file contains the erroneous code.  `bugSolution.html` provides corrected versions. The focus is on errors related to event handling, DOM manipulation, and attribute usage, going beyond the typical syntax errors.

## Errors Demonstrated:

* **Incorrect Event Listener Attachment:** Demonstrates a less-than-ideal way to attach event listeners, which might lead to issues with multiple listeners or memory leaks in complex scenarios.
* **Non-Existent Attribute Usage:** Shows the impact of using attributes that are not part of the HTML specification. This can silently fail or cause unexpected behaviors in different browsers.
* **Missing DOM Element Manipulation:** Attempts to access and modify a DOM element that does not exist, leading to a runtime error.

## How to Reproduce

1. Clone this repository.
2. Open `bug.html` in a web browser.
3. Observe the behavior (or lack thereof) and compare with the corrected version in `bugSolution.html`.