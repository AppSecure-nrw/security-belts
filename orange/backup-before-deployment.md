# Backup before deployment

Changes to the application might corrupt its data. Preparations are being made to restore the data to a state before deployment.

## Risk

- By deploying the application the database gets corrupted.
- This results in downtime or customer data is lost.

## Assessment

- Show preparations of your restore procedure for the last release.
- Execute your restore procedure in a test environment.
