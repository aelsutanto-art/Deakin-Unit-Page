# Input Validation Approach

The current Sprint 1 unit page is mainly static HTML and CSS and does not directly collect user input. However, if user input or dynamic content is added in future development, the following validation approach should be used.

1. Validate all user input before processing or displaying it.
2. Check that input matches the expected data type, format, and length.
3. Reject empty, invalid, or unexpected values where appropriate.
4. Do not directly insert untrusted user input into HTML.
5. Escape or sanitise dynamic content before displaying it to reduce the risk of HTML or script injection.
6. Use allow-lists where possible, so only expected values are accepted.
7. Perform validation on the server side as well as the client side if the website later uses a backend.
8. Test invalid and unexpected inputs to make sure they are handled safely.

This approach helps improve the security and reliability of the website and reduces the risk of malicious or incorrectly formatted input affecting the page.