# AWS CDK Project

This project acts as the communication API layer for the mock CDK service in aws-cdk-mock.

The project mirrors the mock endpoints and handler structure. For example:

- `check-handler` -> `check-mock-handler`
- `initiate-handler` -> `initiate-mock-handler`
- `status-handler` -> `status-mock-handler`
- `submission-handler` -> `submission-mock-handler`

This keeps the main application flow aligned with the mock service while preserving the same function-based contract.

## Useful commands

* `npm run build`   type-check the project
* `npm run watch`   watch for changes and type-check
* `npm run test`    perform the jest unit tests
* `npx cdk deploy`  deploy this stack to your default AWS account/region
* `npx cdk diff`    compare deployed stack with current state
* `npx cdk synth`   emits the synthesized CloudFormation template
# aws-cdk-project
