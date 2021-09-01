# Testing for Bypassing Authentication Schema

A common mistake is to assume that authenticating a user only on the main page is sufficient and other locations don't require authentication, because every access occurs via the main page.

## Activities

- Test that all resources delivered by your application require authentication, except for the public ones.
- Leverage API specifications like [OpenAPI](https://www.openapis.org/) to discover all endpoints of your application.
- Use tools to discover and access resources, e.g., [Gobuster](https://github.com/OJ/gobuster).

## Benefits

- Ensure that private data is in fact not public.

## Assessment

- Show your tests.
- Show the usage of the tool(s).
- Show the handling of the results.

## Related Activities

- [<img src="https://raw.githubusercontent.com/AppSecure-nrw/security-belts/assets/belt-img/02_security-belt-yellow.svg" width="25" />](#) [Security Code Review](../yellow/security-code-review.md)
- [<img src="https://raw.githubusercontent.com/AppSecure-nrw/security-belts/assets/belt-img/02_security-belt-yellow.svg" width="25" />](#) [Unit Tests for Security Features](../yellow/unit-tests-for-security-features.md)

## Further Readings

- Tool: [Burp](https://portswigger.net/burp)
- Tool: [OWASP ZAP](https://www.zaproxy.org/)
- Tool: [ffuf](https://github.com/ffuf/ffuf)
- Tool: [Gobuster](https://github.com/OJ/gobuster)
- Specification: [OpenAPI](https://www.openapis.org/)

<p align="right"><a href="https://www.surveymonkey.de/r/MNWNVRB">Send Feedback</a></p>
