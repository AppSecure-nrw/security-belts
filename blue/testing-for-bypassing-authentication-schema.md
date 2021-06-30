# Testing for Bypassing Authentication Schema

A common mistake is to assume that authenticating a user only on the main page is sufficient and other locations don't require authentication, because every access occures via the main page.
Test that all resources deliverd by your application require authentication, exept for the public ones.
Leaverage API specifications like OpenAPI to discover all endpoints of your application.
In case you don't have white-box information about the application, use tools to discover and access resources, e.g., gobuster or dirbuster.

## Benefits

- Detect this common flaw and bug in your authentication system.
- You ensure, that private data is in fact not public.

## Assessment

- Show the usage of the tool(s).
- Show the handling of the results.
- Show the latest *n* findings.
- Show your false positive list.

## Related Activities

- [Security Code Review](../yellow/security-code-review.md) reviews the authentication and authorization concept and implementation.
- Unit Tests

## Further Readings

- Tool: [Burp](https://portswigger.net/burp)
- Tool: [OWASP ZAP](https://www.zaproxy.org/)
- Tool: [ffuf](https://github.com/ffuf/ffuf)
- Specification: [OpenAPI](https://www.openapis.org/)
