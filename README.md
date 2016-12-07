# Terraform Snippets for VS Code
Adds some useful snippets for configuration with Terraform

## Snippets:
```
tfout  // creates a new output
tfvar  // creates a new variable
```

## Requirements

Install the [Terraform Language](https://marketplace.visualstudio.com/items?itemName=mauve.terraform) support extension from the marketplace published by "Mikael Olenfalk"

## Currently Supported Snippets
* Output: `tfout`
* Variable: `tfvar`
* AWS Resources:
    * AWS Provider: `aws`
    * EC2 Instance: `aws-instance`
    * Beanstalk App: `aws-beanstalk-app`
    * Beanstalk Environment: `aws-beanstalk-env`
    * S3 Bucket: `aws-bucket`
    * S3 Bucket Hosting: `aws-bucket-hosting`
    * S3 Bucket Notification: `aws-bucket-notification`
    * S3 Bucket Object: `aws-bucket-object`
    * S3 Bucket Policy: `aws-bucket-policy`
    * SNS Topic: `aws-sns-topic`
    * SNS Topic Policy: `aws-sns-topic-policy`
    * SNS Topic Subscription: `aws-sns-topic-subscription`
    * SQS Queue: `aws-sqs-queue`
    * SQS Policy: `aws-sqs-queue-policy`
    * VPC: `aws-vpc`
    * Subnet: `aws-subnet`

## Todo

### Provider Specific Snippets