# AWS SAM Reference<a name="serverless-sam-reference"></a>

## AWS SAM Specification<a name="serverless-sam-specification"></a>

The AWS SAM specification is an open\-source specification under the Apache 2\.0 license\. The current version of the AWS SAM specification is available in the [AWS SAM GitHub repo](https://github.com/awslabs/serverless-application-model/blob/master/versions/2016-10-31.md)\.

AWS SAM templates are an extension of AWS CloudFormation templates\. That is, any resource that you can declare in an AWS CloudFormation template, you can also declare in an AWS SAM template\. For the full reference for AWS CloudFormation templates, see [AWS CloudFormation Template Reference](https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/template-reference.html)\.

## AWS SAM CLI<a name="serverless-sam-cli"></a>

The **AWS SAM CLI** is a command line tool that operates on an AWS SAM template and application code\. With the AWS SAM CLI, you can invoke Lambda functions locally, create a deployment package for your serverless application, deploy your serverless application to the AWS Cloud, and so on\.

You can use the AWS SAM CLI commands to develop, test, and deploy your serverless applications to the AWS Cloud\. The following are some examples of AWS SAM CLI commands:
+ `sam init` – If you're a first\-time AWS SAM CLI user, you can run the `sam init` command without any parameters to create a Hello World application\. The command generates a preconfigured AWS SAM template and example application code in the language that you choose\. 
+ `sam local invoke` and `sam local start-api` – Use these commands to test your application code locally, before deploying it to the AWS Cloud\. 
+ `sam package` – Use this command to bundle your application code and dependencies into a "deployment package" that's needed in order to upload to the AWS Cloud\.
+ `sam deploy` – Use this command to deploy your serverless application to the AWS Cloud\. It creates the AWS resources and sets permissions and other configurations that are defined in the AWS SAM template\.

**Topics**
+ [Installing the AWS SAM CLI](serverless-sam-cli-install.md)
+ [AWS SAM CLI Command Reference](serverless-sam-cli-command-reference.md)