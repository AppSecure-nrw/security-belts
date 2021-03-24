# Test of Container Images Regarding Known Vulnerabilities

Perform tests for known vulnerabilities in all container images used by your software. Use tools to automate your tests.

Note that this can result in many found vulnerabilities. Check whether they are fixed in the next build of the container image. See related Belt Activity: Container Update Enforcement.

## Benefits

- Known vulnerabilities in used containers are found and can be fixed.
- The system is not vulnerable to well known attacks in middle-ware it relies on.

## Assessment

- Show the tests and usage of the tool(s).
- Show the handling of the results.
- Show the latest *n* findings.
- Show your false positive list.

## Related Activities
 - Container Update Enforcement (in development)

## Further Readings
 - [Tool: JFrog Xray](https://jfrog.com/xray/)
 - [Tool: Anchore](https://anchore.com/)
 - [Tool: Clair](https://github.com/quay/clair/releases)
 
