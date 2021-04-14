# Prevent Secrets in Source Code

Avoid hard-coded secrets (e.g., credentials) in application and infrastructure source code. Automate this task by using Git pre-commit hooks or similar techniques.

## Benefits

- No leakage of confidential data through compromised source code.
- Credentials are not located in the version control system repositories.

## Assessment

- Show the usage of the tool(s).
- Show the handling of the results.
- Show the latest *n* findings.
- Show your false positive list.

## Related Activities

- [Environment-dependent configuration parameters](environment-dependent-configuration-parameters.md)

## Further Readings

- Tool: [truffleHog](https://github.com/dxa4481/truffleHog)
- Tool: [Gitrob](https://github.com/michenriksen/gitrob)
- Tool: [SonarQube](https://www.sonarqube.org/)
