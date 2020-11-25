# Same Artifact for Environments

An artifact is build once and deployed for testing, as well as production purpose. This ensures your artifact in production is the one you tested. Do not use environment names to configure your artifact.

## Risk

- Environment specific artifacts require changes right before production deployment. These changes are made outside the continuous integration cycle. Therefore bugs in these changes can not be found via continuous integration.

## Assessment

- Show the hash sum of your artifact after:
  - build
  - deploy in a test environment
  - deploy in the production environment
- Show all configuration parameters off your artifact.
