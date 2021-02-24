# Unit Tests for Security Features

Test functionality of security related features like authentication and authorization with unit tests.

- [OWASP Testing Guide 4.4.7 Testing for Weak Password Policy](https://owasp.org/www-project-web-security-testing-guide/v42/4-Web_Application_Security_Testing/04-Authentication_Testing/07-Testing_for_Weak_Password_Policy.html)
  - test for known passwords like $company2021, admin, $projcetName, 123456, aaa
  - test for [breached passwords](https://github.com/danielmiessler/SecLists/tree/master/Passwords)
- [4.5.3 Testing for Privilege Escalation](https://owasp.org/www-project-web-security-testing-guide/v42/4-Web_Application_Security_Testing/05-Authorization_Testing/03-Testing_for_Privilege_Escalation.html)
  1. Acuire a session for a normal user.
  1. Access admin functionality that the user should not be able to access.
  

## Benefits

- Arising vulnerabilities due to faulty code changes in security features can be found immediately.

## Assessment

- Provide your unit tests for your security features and explain some of them.

## Further Readings
