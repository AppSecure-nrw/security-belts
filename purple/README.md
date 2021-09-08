# [<img src="https://raw.githubusercontent.com/AppSecure-nrw/security-belts/assets/belt-img/06_security-belt-purple.svg" width="40" />](#) Purple Belt

TODO summary + order

- [Treatment of Vulnerabilities With Severity Medium](treatment-of-vulnerabilities-with-severity-medium.md)
- [Dynamic Scan With Different Roles](dynamic-scan-with-different-roles.md)
- Targeted alerting
  - *requires* (Simple application metrics || Simple system metrics) && Visualized metrics
  - Do you analyze log data for security incidents periodically?
- Limit access to application secrets according to the least privilege principle
  - Don't be stupid
- Inject production secrets into configuration files during deployment
- Infrastructure as Code
- Test the definition of virtualized environments
  - SAST on infrastructure code
  - *example tools* [cloudformation-guard](https://github.com/aws-cloudformation/cloudformation-guard)
- Coverage analysis
  - *related* Dynamic Scan for Security Vulnerabilities
  - *related* Unit Tests for Security Features
  - *related* API Fuzzing
- Enrich Threat model with Checks for Security by Design Principles
   - *requires*: Get to know Security by Design Principles
   - *requires*: Conduction of Threat Modeling
- Know your Attack Surface
       Proxy do not protect you webapp from attacks; Note: may be included in threat model activity

<p align="right"><a href="https://www.surveymonkey.de/r/MJWT29X">Send Feedback</a></p>
