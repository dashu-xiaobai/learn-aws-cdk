# Welcome to your CDK TypeScript project

This is a demo project for CDK development with TypeScript.

The `cdk.json` file tells the CDK Toolkit how to execute your app.

## Prerequisite
1. set up AWS account and AWS CLI
2. install nvm
3. install node using `nvm install 16`
4. install aws-cdk using `npm install -g aws-cdk` and verify cdk version `cdk --version`
5. bootstrap using `cdk bootstrap`

## Build
 run `npm run build`

## synthesize
 run `cdk synth`

## deploy
 run `cdk deploy`
  
## Useful commands

* `npm run build`   compile typescript to js
* `npm run watch`   watch for changes and compile
* `npm run test`    perform the jest unit tests
* `cdk deploy`      deploy this stack to your default AWS account/region
* `cdk diff`        compare deployed stack with current state
* `cdk synth`       emits the synthesized CloudFormation template
