# Prevent Secrets in Source Code

## Activities

- Avoid hard-coded secrets (e.g., credentials) in application and infrastructure source code.
- Automate this task by using Git pre-commit hooks or similar techniques.

## Benefits

- No leakage of confidential data through compromised source code.
- Credentials are not located in the version control system repositories.

## Assessment

- Show the usage of the tool(s).
- Show the handling of the results.
- Show the latest *n* findings.
- Show your false positive list.

## Related Activities

- [<img src="https://raw.githubusercontent.com/AppSecure-nrw/security-belts/assets/belt-img/04_security-belt-green.svg" width="25" />](#) [Environment-Dependent Configuration Parameters](../green/environment-dependent-configuration-parameters.md)

## Further Readings

- Tool: [truffleHog](https://github.com/dxa4481/truffleHog)
- Tool: [Gitrob](https://github.com/michenriksen/gitrob)
- Tool: [SonarQube](https://www.sonarqube.org/)

<p align="right"><a href="https://www.surveymonkey.de/r/MNWNVRB">Send Feedback</a></p>
