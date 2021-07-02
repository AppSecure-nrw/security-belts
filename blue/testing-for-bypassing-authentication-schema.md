# Testing for Bypassing Authentication Schema

A common mistake is to assume that authenticating a user only on the main page is sufficient and other locations don't require authentication, because every access occures via the main page.

## Activities

- Test that all resources delivered by your application require authentication, except for the public ones.
- Leverage API specifications like OpenAPI to discover all endpoints of your application.
- In case you do not have white-box information about the application, use tools to discover and access resources, e.g., gobuster or dirbuster.

## Benefits

- Detect this common flaw and bug in your authentication system.
- You ensure, that private data is in fact not public.

## Assessment

- Show your tests.
- Show the usage of the tool(s).
- Show the handling of the results.

## Related Activities

- [Security Code Review](../yellow/security-code-review.md) reviews the authentication and authorization concept and implementation.
- [Unit Tests for Security Features](../yellow/unit-tests-for-security-features.md)

## Further Readings

- Tool: [Burp](https://portswigger.net/burp)
- Tool: [OWASP ZAP](https://www.zaproxy.org/)
- Tool: [ffuf](https://github.com/ffuf/ffuf)
- Specification: [OpenAPI](https://www.openapis.org/)
