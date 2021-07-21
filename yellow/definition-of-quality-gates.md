# Definition of Quality Gates

## Activities

- Define quality gates adhering to your companies policy.
- Make sure that all requirements are fulfilled.
- Also define quality gates for found vulnerabilities and provide feedback about vulnerabilities and time of exposure, i.e., break the CI build.

Be aware, by introducing this activity, you might have a backlog with many findings from the past.
- Provide transparency about this backlog and continuously fix the reported issues.
- Start with the most critical ones.
- Make sure to adhere to the policy from now on and do not introduce additional findings through code changes.

## Benefits

- Helps to find vulnerabilities earlier. As such, it helps to mitigate the risk of exploitation. This is important, as the risk of exploitation continuously increases over time for a given vulnerability.
- Vulnerabilities are fixed in time.

## Assessment

- Show the definition of the gates.
- Show the usage of the gates.
- Show the treatment of rejected cases.
- Show your current exposure.
- Show how you handle false positives.

## Related Activities

- [<img src="https://raw.githubusercontent.com/AppSecure-nrw/security-belts/assets/belt-img/02_security-belt-yellow.svg" width="25" />](#) [Continuous Integration](../yellow/continuous-integration.md)

## Further Readings

- Tool: [Jenkins Next Generation Warnings plugin](https://plugins.jenkins.io/warnings-ng/)
