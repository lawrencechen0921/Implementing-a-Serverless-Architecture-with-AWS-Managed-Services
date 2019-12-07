# Implementing-a-Serverless-Architecture-with-AWS-Managed-Services

Traditionally, applications run on servers. These can be physical servers or virtual environments running on top of physical servers, but they still need servers to be purchased and provisioned, and for capacity to be managed. 
On the other hand, AWS lambda can run serverless code without having to pre-allocate servers. 
Simply provide the code and define a trigger and the function can run whenever required –once per week or hundreds of times per second, and you only pay for what you use.
This lab demonstrates how to trigger an AWS Lambda function when a file is uploaded to Amazon S3.
The file will be loaded into an Amazon DynamoDB table, and the data will be available forviewing on a Dashboard page that pulls the data directly from DynamoDB.
The solution is completely serverless, automatically scalable and incurs very little cost.
The system does not use Amazon EC2. 
The system will automatically scale when it is used andincurs practically no cost when it is not being used.

# In this lab you will learn:
# •Use CloudFront to automatically deploy resources on AWS
# •Use AWS managed services to implement a serverless architecture
# •Trigger AWS Lambda functions from Amazon S3 and Amazon DynamoDB
# •Configure Amazon SNS to send notifications
