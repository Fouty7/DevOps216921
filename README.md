# DevOps216921

Aminu Ndakun

AWS CLOUDFORMATION
Deploying/provisioning Network and Compute AWS resources using AWS CloudFormation templates
Templates have been written generally in .yml format.

Dependencies:
AWS Account
AWS Programmatic IAM user with Access Key and Secret Key
Code Editor to change some parameters/resource ids
Git Bash/Power shell

Getting Started:
Clone this repo
Open Git Bash or power shell
Cd to the directory in which your cloned files are
Configure AWS account by using the command bellow

  aws configure

on prompt enter the Access Key and Secrete Key
to create any stack, find the <template-body>.yml and matching <parameter>.json files and type the commands below.

  aws cloudformation create-stack --stack-name <value> --template-body file://<value> --parameters file://<value>

to verify stack creation, go to AWS Console, CloudFormation or enter the command below in CLI

  aws cloudformation describe-stacks 

to update a stack after making your changes type the command

  aws cloudformation update-stack --stack-name <value> --template-body file://<value> --parameters file://<value>

to delete a stack, enter the command

  aws cloudformation delete-stack --stack-name <value>



