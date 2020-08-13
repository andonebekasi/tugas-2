# Terraform SNS to SQS to Lambda

Silakan BACA-SAYA.PDF 

## Architecture

SNS --> SQS --> LAMBDA


## Description

The code creates three resources:

1) An SNS topic
2) An SQS queue which subscribes to the SNS topic
3) A Lambda function which subscribes to the SQS queue


Please note that the code is NOT production ready and is only meant as an example.

source from 
https://github.com/cgiacomi/terraform_sns_sqs
