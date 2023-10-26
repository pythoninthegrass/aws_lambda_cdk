# Welcome to your CDK TypeScript project

This is a blank project for CDK development with TypeScript.

The `cdk.json` file tells the CDK Toolkit how to execute your app.

## Setup
### Minimum Requirements
* [Install Node.js and npm](https://nodejs.org/en/download/)
  * Tested with Node.js v20.0.0
* [Install AWS CLI](https://docs.aws.amazon.com/cli/latest/userguide/cli-chap-install.html)
* [Install AWS CDK](https://docs.aws.amazon.com/cdk/latest/guide/getting_started.html)
* [Configure AWS CLI](https://docs.aws.amazon.com/cli/latest/userguide/cli-chap-configure.html)
* Install dependencies
    ```bash
    # install typescript
    npm install -g typescript

    # install cdk
    npm install -g aws-cdk

    # install dependencies
    npm install
    ```
### Recommended
* [asdf](https://asdf-vm.com/#/core-manage-asdf-vm)
    ```bash
    # install nodejs
    asdf plugin add nodejs
    asdf install nodejs 20.0.0
    ```

## Quickstart
```bash
# compile typescript to js
npm run build

# watch for changes and compile
npm run watch

# perform the jest unit tests
npm run test 

# setup cdk context
cdk bootstrap

# sanity check
cdk doctor

# deploy this stack to your default AWS account/region
cdk deploy

# compare deployed stack with current state
cdk diff

# emits the synthesized CloudFormation template
cdk synth 

# destroy stack
cdk destroy
```
