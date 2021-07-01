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

- [Continuous Integration](../yellow/continuous-integration.md)
- [Test for Default Credentials](test-for-default-credentials.md)
- [Logging of Security Events](../orange/logging-of-security-events.md)

## Further Readings

- Literature: [CIS Benchmark](https://www.cisecurity.org/cis-benchmarks/)
- Literature: [BSI IT-Grundschutz-Bausteine](https://www.bsi.bund.de/DE/Themen/Unternehmen-und-Organisationen/Standards-und-Zertifizierung/IT-Grundschutz/IT-Grundschutz-Kompendium/IT-Grundschutz-Bausteine/Bausteine_Download_Edition_node.html)
- Tool: [InSpec](https://www.chef.io/products/chef-inspec)
- Tool: [nessus](https://www.tenable.com/products/nessus)
- Tool: [OpenVAS](https://www.openvas.org/)
