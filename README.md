# Uncommon innerHTML Injection Bug
This repository demonstrates a subtle bug related to the use of `innerHTML` in HTML.  Dynamically injecting HTML using `innerHTML` is convenient but it can be dangerous if the input is not properly sanitized. This bug shows a scenario where this can lead to unexpected behavior or security risks. 

The `bug.html` file contains the erroneous code.  The `bugSolution.html` file shows the corrected version.

This bug is uncommon because it's related to how browsers handle dynamic HTML injection, it's not a syntax error.  It is crucial to avoid directly using untrusted user-input in `innerHTML` to prevent Cross-Site Scripting (XSS) vulnerabilities.