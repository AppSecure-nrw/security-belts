# Test for Default Credentials

Test for default credentials within all services (frontend, database, etc.) of your product. Automate this test using existing tools to reduce your effort. 

**TODO:** Why is this in the green belt and not in orange? Benefit is high und Effort is low if your automate it. Or is the benefit low as most devs change them?
**TODO:** Should we merge this activity with the yellow belt activity [Unit Tests for Security Features: Testing for Weak Password Policy](../yellow/unit-tests-for-security-features.md)? In this yellow belt activity, we already check for weak passworts - checking for default credentials is very similar.

**TODO:** Are there services with default credentials that are not analyzed by nmap or hydra? We assume that offline (non-http) services may need an extra script. If so: Your script shall contain all offline services that require credentials. Additionally, write down for each service what its default credential is.

## Benefits
- It is more complicated for attackers to gain access to one of your services. 
	- However, an attack is still possible, e.g., if you use weak passwords.

## Assessment
- Show the analysis results of your tools.

## Examples
- Try the following usernames - admin, administrator, root, system, guest, operator, or super.

## Related Activities

- [Unit Tests for Security Features: Testing for Weak Password Policy](../yellow/unit-tests-for-security-features.md)
	- **TODO:** add Hydra to this one

## Further Readings

- Tool: [Hydra](url), a network logon cracker, which tests for default credentials and weak passwords
- Tool: [nmap script for http default accounts](https://nmap.org/nsedoc/scripts/http-default-accounts.html)
- Literature: [OWASP Testing Guide 4.4.2](https://owasp.org/www-project-web-security-testing-guide/v42/4-Web_Application_Security_Testing/04-Authentication_Testing/02-Testing_for_Default_Credentials.html)
