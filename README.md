# AWS-DVA-C02-cheatsheet
AWS Certified Developer Associate DVA-C02 cheat sheet


Useful resources:

- Stephane Mareek’s course: https://www.udemy.com/course/aws-certified-developer-associate-dva-c01/
- Stephane Mareek’s practice tests: https://www.udemy.com/course/aws-certified-developer-associate-practice-tests-dva-c01/
- TutorialsDojo practice tests (by Jon Bonso): https://tutorialsdojo.com/courses/aws-certified-developer-associate-practice-exams/
- ExamTopics “free” questions: 
  - https://www.examtopics.com/exams/amazon/aws-certified-developer-associate-dva-c02/
  - https://www.examtopics.com/exams/amazon/aws-certified-developer-associate/
- Digital Cloud AWS Developer Associate cheat sheet: https://digitalcloud.training/category/aws-cheat-sheets/aws-developer-associate/


Exam time - 2 hours and 10 minutes (+30 minutes if English isn't native language)

AWS DVA-C02 topics:
- Domain 1: Development with AWS Services (32%)
- Domain 2: Security (26%)
- Domain 3: Deployment (24%)
- Domain 4: Troubleshooting and Optimization (18%)

You can expect a lot of questions about:

AWS Services:

- AWS Lambda:
  - integration with API Gateway
  - running function inside VPC
  - difference between sync and async invocations (including Dead Letter Queues)
  - event-based Lambda invocation
  - deployment modes
  - versions and aliases
- DynamoDB:
  - WCU/RCUs
  - GSIs
  - LSIs
  - DAX
  - partition keys and sort keys
  - Streams
  - hot partition and how to avoid hot partition
  - eventually and strongly consistent reads
- API Gateway
- EC2
- SQS
- SNS
- Kinesis
- S3:
  - encryption options
- ECS
- CI/CD tools
- Elastic Beanstalk
- CloudFront
- SAM
- Step Functions
- Cognito
- CloudWatch
- CloudTrail
- X-Ray

Security:
- KMS
- Secrets Manager
- SSM Parameter Store

Deployment:
- Deployment strategies of different services
- CodeCommit
- CodeDeploy
- CodeBuild
- CodePipeline
- AWS CloudFormation
- CDK
- Understand when to use SAM vs CloudFormation vs CDK