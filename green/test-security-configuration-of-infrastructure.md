# Test Security Configuration of Infrastructure

## Activities

- Perform security assessments of your server side infrastructure components.
- These should include the operating system, middleware, application server, and database.
- Be aware that these components might be running inside docker containers.

## Benefits

- The infrastructure is hardened against common attacks and misconfigurations.
- Resilience of your application is increased. Following the *defense in depth* methodology.

## Assessment

- Show the assessment reports.
- Show the handling of the results.
- Show the latest *n* findings.
- Show your false positive list.

## Related Activities

- [<img src="https://raw.githubusercontent.com/AppSecure-nrw/security-belts/assets/belt-img/02_security-belt-yellow.svg" width="25" />](#) [Continuous Integration](../yellow/continuous-integration.md)
- [<img src="https://raw.githubusercontent.com/AppSecure-nrw/security-belts/assets/belt-img/03_security-belt-orange.svg" width="25" />](#) [Logging of Security Events](../orange/logging-of-security-events.md)
- [<img src="https://raw.githubusercontent.com/AppSecure-nrw/security-belts/assets/belt-img/04_security-belt-green.svg" width="25" />](#) [Test for Default Credentials](../green/test-for-default-credentials.md)

## Further Readings

- Literature: [CIS Benchmark](https://www.cisecurity.org/cis-benchmarks/)
- Literature: [BSI IT-Grundschutz-Bausteine](https://www.bsi.bund.de/DE/Themen/Unternehmen-und-Organisationen/Standards-und-Zertifizierung/IT-Grundschutz/IT-Grundschutz-Kompendium/IT-Grundschutz-Bausteine/Bausteine_Download_Edition_node.html)
- Tool: [InSpec](https://www.chef.io/products/chef-inspec)
- Tool: [nessus](https://www.tenable.com/products/nessus)
- Tool: [OpenVAS](https://www.openvas.org/)
