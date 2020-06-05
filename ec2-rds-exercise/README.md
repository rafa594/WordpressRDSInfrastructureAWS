# WordpressRDSInfrastructureAWS
Cloudformation templates that deploy an infrastructure with a VPC, Public and Private Subnets, Route Tables, Security Groups, Internet Gateway, RDS and EC2 instance to manage a Wordpress Site.

# Project Diagram
![WordpressRDSInfrastructure](/images/diagram.png)

# Process

* Login to your account in AWS Console.
* Create an AWS S3 Bucket and upload the files on the repository to this bucket.
* Navigate to AWS CloudFormation page and create a CloudFormation Stack.
* Select Amazon S3 URL option and set the URL of the Master.yml file.
* Wait to CloudFormation and check the outputs of the stack to find the DNS of the AWS EC2 resource.