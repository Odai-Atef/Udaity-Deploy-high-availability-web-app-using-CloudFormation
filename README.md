# Udaity-Deploy-high-availability-web-app-using-CloudFormation
[![Build Status](https://travis-ci.org/joemccann/dillinger.svg?branch=master)](https://travis-ci.org/joemccann/dillinger)

This yaml file used to launch cloud formation stack with the following steps:
  - Create VPC
  - Create two private subnets
  - Create VPC
  - Create Security Group
  - Create IAM Role
  - Create S3 Policy
  - Create Instance Profile 
  - Create Launch Configuration
  - Create Auto Scale group
  - Launch 4 instance into two subents downloading code from S3 and deploy it and insatll apache2


### Run the stack using AWS CLI

```sh
$ aws cloudformation create-stack --stack-name udacity-projectII --template-body file://launch.yml --capabilities CAPABILITY_NAMED_IAM

```

License
----
Odai Atef
**Free to use**
