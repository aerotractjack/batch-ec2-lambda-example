# batch-ec2-lambda-example
This repo contains terraform scripts to build the following infrastructure:
- S3 buckets for input and output data
- S3 event configuration to trigger Lambda
- Lambda function which triggers Batch job
- ECR repo and Docker config to build and push image
- Batch EC2 compute environment, job queue, and job definition
- VPC, 2 public subnets, 2 private subnets, networking config
