# Base Serverless Framework Template

## What's included

- Folder structure used consistently across our projects.
- [serverless-pseudo-parameters plugin](https://www.npmjs.com/package/serverless-pseudo-parameters): Allows you to take advantage of CloudFormation Pseudo Parameters.
- [serverless-bundle plugin](https://www.npmjs.com/package/serverless-pseudo-parameters): Bundler based on the serverless-webpack plugin - requires zero configuration and fully compatible with ES6/ES7 features.
- [serverless-iam-roles-per-function plugin](https://www.npmjs.com/package/serverless-iam-roles-per-function): A Serverless plugin to easily define IAM roles per function via the use of iamRoleStatements at the function definition block.

## Getting started

```
sls create --name YOUR_PROJECT_NAME --template-url https://github.com/0xBABA/sls-base
cd YOUR_PROJECT_NAME
yarn install
```

You are ready to go!
