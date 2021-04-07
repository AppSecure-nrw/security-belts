# Test for Default Credentials

Test for default credentials within all services (frontend, database, etc.) of your product that are reachable within your network. Automate this test using existing tools within a testing environment. 

Be aware that accounts might get locked if your login attempt fails too many times and that intrusion detection alerts might be raised at your central security. Furthermore, both problems can already occur in your testing environment - depending on your it-security infrastructure. 

Note that we only focus on network attacks. Offline services may have also default credentials but if an attacker can access your offline files, then you have other problems than having weak credentials.

**TODO:** Lars and Stefan agree: The benefit is very high but effort is currently medium. We need to check whether the effort is in fact medium. If it is less, this activity should be a orange one.  Questions we need to answer: How complex is it to run hydra? Does it need a full list of end points? How complex is it to set up a test environment that does not close all accounts and does not raise intrusion detection alerts? We need feedback for this. 

**TODO:** Stefan asks: Is a week passwort check activity missing? We only have an activity in the yellow belt activity for the password policy: [Unit Tests for Security Features: Testing for Weak Password Policy](../yellow/unit-tests-for-security-features.md).

## Benefits
- It is more complicated for attackers to gain access to one of your services. 
	- However, an attack is still possible, e.g., if you use weak passwords.

## Assessment
- Show the analysis results of your tools.

## Examples
- Try the following usernames - admin, administrator, root, system, guest, operator, or super.

## Related Activities

- [Unit Tests for Security Features: Testing for Weak Password Policy](../yellow/unit-tests-for-security-features.md)
	- **TODO:** Lars and Stefan say: Explain in this activity better that it is not about weak password testing, but weak password policy testing.

## Further Readings

- Tool: [Hydra](https://github.com/vanhauser-thc/thc-hydra), a network logon cracker, which tests for default credentials and weak passwords
- Tool: [nmap script for http default accounts](https://nmap.org/nsedoc/scripts/http-default-accounts.html)
- Literature: [OWASP Testing Guide 4.4.2](https://owasp.org/www-project-web-security-testing-guide/v42/4-Web_Application_Security_Testing/04-Authentication_Testing/02-Testing_for_Default_Credentials.html)
