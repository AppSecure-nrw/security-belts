# Environment-Dependent Configuration Parameters

## Activities

- Provide all environment-dependent configuration as parameters.
- Avoid hard-coded environment-dependent data (e.g., credentials, paths) in application and infrastructure source code.

## Benefits

- No leakage of confidential data through compromised source code.
- Changing configurations of your application does not require source code changes and redeployment.
- Credentials are not located in the version control system repositories.
- The tested source code is the one which is deployed. No environment specific changes are required right before production deployment. Therefore, bugs introduced by these changes are prevented.

## Assessment

- Show your configuration files for all your different environments like dev, test and production
  - URL specification for different environments
  - Configuration parameters for backend / database systems

## Related Activities

- [<img src="https://raw.githubusercontent.com/AppSecure-nrw/security-belts/assets/belt-img/03_security-belt-orange.svg" width="25" />](#) [Same Artifact for Environments](../orange/same-artifact-for-environments.md)
- [<img src="https://raw.githubusercontent.com/AppSecure-nrw/security-belts/assets/belt-img/04_security-belt-green.svg" width="25" />](#) [Prevent Secrets in Source Code](../green/prevent-secrets-in-source-code.md)

## Further Readings

- Tool: [SonarQube](https://www.sonarqube.org/)

<p align="right"><a href="https://www.surveymonkey.de/r/MNWNVRB">Send Feedback</a></p>
