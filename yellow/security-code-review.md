# Security Code Review

## Activities

- Perform code reviews of security-related software and infrastructure with the Security Champion Guild.

The following areas of code tend to have a high-risk of containing security vulnerabilities:
  - Crypto implementations / usage
  - Parser, unparser
  - System configuration
  - Authentication, authorization
  - Session management
  - Request throttling
  - :unicorn: (self-developed code, only used in that one software)

## Benefits

- New vulnerabilities may be found before reaching production.
- Old vulnerabilities are found and fixed.

## Assessment

- Present the performed reviews (including participants, findings, consequences) and assess whether it is reasonable.

## Further Readings

- Literature: [CWE Top 25 Most Dangerous Software Weaknesses](https://cwe.mitre.org/top25/archive/2020/2020_cwe_top25.html)
