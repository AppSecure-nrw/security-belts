# Environment-dependent configuration parameters

Provide all environment-dependent configuration as parameters. Avoid hard-coded environment-dependent data (e.g., credentials, paths) in application and infrastructure source code.

## Benefits

- No leakage of confidential data through compromised source code.
- Changing configurations of your application does not require source code changes and redeployment.
- The tested source code is the one which is deployed. No environment specific changes are required right before production deployment. Therefore, bugs introduced by these changes are prevented.

## Assessment

- TODO
## Related Activities

- [Same Artifact for Environments](../orange/same-artifact-for-environments.md)

## Further Readings