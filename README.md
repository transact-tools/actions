# Actions

This repository contains a number of GitHub Actions that are used frequently throughout all https://transact.tools repositories.

Some are more complex actions, whilst others help us to quickly set up CI/CD for a service. Most actions use organisation secrets, so the content might not make sense.

## `standard-node-workflow`

Installs & tests dependencies. A pretty standard Node.JS workflow.

## `assume-credentials`

Assumes temporary IAM credentials for one of the AWS accounts, based upon the branch target. `master` is always deployed to production and others are deployed to development.
