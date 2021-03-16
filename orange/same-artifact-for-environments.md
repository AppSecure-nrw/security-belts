# Same Artifact for Environments

Build your artifacts only once. Use the same artifact for testing as well as for production purposes. This ensures your artifact in production is the one you tested. Do not use environment names to configure your artifact.

## Benefits

- The tested artifact is the one which is deployed. No environment specific changes are required right before production deployment. Therefore, bugs introduced by these changes are prevented.

## Assessment

- Show the hash sum of your artifact after:
  - build
  - deploy in a test environment
  - deploy in the production environment
- Show all configuration parameters off your artifact.

## Further Readings
