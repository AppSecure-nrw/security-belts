# Unit Tests for Security Features

## Activities

- Identify all security-related features. These commonly contribute to the following security goals:
  - confidentiality
  - integrity
  - availability
  - authentication
  - authorization
  - accountability
- Test functionality of these security-related features with unit tests.
  - Beware, unit tests should not only cover positive cases, but also negative cases (e.g., accessing admin resources as a normal user).

## Benefits

- Arising vulnerabilities due to faulty code changes in security features can be found immediately.

## Assessment

- Provide your unit tests for your security features and explain some of them.

## Examples

[OWASP Testing Guide](https://owasp.org/www-project-web-security-testing-guide) provides some good examples, which can be covered by unit tests:

- [4.4.7 Testing for Weak Password Policy](https://owasp.org/www-project-web-security-testing-guide/v42/4-Web_Application_Security_Testing/04-Authentication_Testing/07-Testing_for_Weak_Password_Policy.html)
  1. test for known passwords like $company2021, admin, $projectName, 123456, aaa
  1. test for [breached passwords](https://github.com/danielmiessler/SecLists/tree/master/Passwords)
- [4.5.3 Testing for Privilege Escalation](https://owasp.org/www-project-web-security-testing-guide/v42/4-Web_Application_Security_Testing/05-Authorization_Testing/03-Testing_for_Privilege_Escalation.html)
  1. Acquire a session for a normal user.
  1. Access admin functionality that the user should not be able to access. Use different values for all request parameters.
     - For each parameter define valid and invalid values.
     - Create tests for all combinations
  1. Fail the test if you have access
- [4.5.4 Testing for Insecure Direct Object References](https://owasp.org/www-project-web-security-testing-guide/v42/4-Web_Application_Security_Testing/05-Authorization_Testing/04-Testing_for_Insecure_Direct_Object_References.html)
  1. Acquire a session for a normal user.
  1. Get a reference to a document or resource accessible only by the user.
  1. Acquire a second session for another user.
  1. Use the reference to access the document or resource.
  1. Fail the test if you have access

## Further Readings

- Literature: [OWASP Testing Guide](https://owasp.org/www-project-web-security-testing-guide)
