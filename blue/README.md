# 5 - Blue Belt

TODO

DAST
Threat Modeling
Awareness

- [ ] Conduction of threat modelling
  - STRIDE
  - *requires* understanding of company security policies
  - *includes* Regularly review the security mechanisms of your architecture
- [ ] Approval by reviewing any new version // Code Review on all changes (Yellow Security Code review: add 'on each code change')
  - *requires* Security Champion knowledge
- [ ] PII (personally identifiable information) logging concept
- [ ] Simple Scan
  - *tools* Burp, ZAP
  - *includes* [OWASP Testing Guide 4.5.2](https://owasp.org/www-project-web-security-testing-guide/v42/4-Web_Application_Security_Testing/05-Authorization_Testing/01-Testing_Directory_Traversal_File_Include.html)
- [ ] API Fuzzing
  - *requires* Simple Scan
  - *tools* Burp/ZAP + OpenApi/Swagger
  - *includes* Coverage of hidden endpoints (word list)
- [ ] Load tests
- [ ] Testing for Bypassing Authentication Schema
  - *tools* gobuster, dirbuster
  - use OpenAPI
  - [OWASP Testing Guide 4.4.4](https://owasp.org/www-project-web-security-testing-guide/v42/4-Web_Application_Security_Testing/04-Authentication_Testing/04-Testing_for_Bypassing_Authentication_Schema.html)
- [ ] Advanced Mob-Hacking
  - include usage of tools like Burp


## pre belt
- [ ] Simple Mob-Hacking

## post belt
- [ ] Conduction of build-it, break-it, fix-it contests