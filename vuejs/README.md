# Github Actions example Vuejs - S3

Vue. js is an open-source progressive JavaScript framework for building user interfaces (UIs) and single-page applications; it is commonly referred to as Vue. This framework uses “high decoupling”, allowing developers to progressively create user interfaces.

## Config AWS

- Create an AWS account.
- Create an IAM Group and attach policies.
- Add IAM Users to the Created Group.
- Create a bucket in AWS S3 that will store my static files.
- Set up the backend API or the endpoints with Node. js and Express that will access the AWS S3 bucket via the SDK.
- Create our Vue.

## Config Vuejs project

We need create folder `.github/workflows/ci.yml`

## Enviroment

We need to go to a settings -> secrets and create:

AWS_ACCESS_KEY_ID

AWS_SECRET_ACCESS_KEY

Optional:

FONTAWESOME_NPM_AUTH_TOKEN