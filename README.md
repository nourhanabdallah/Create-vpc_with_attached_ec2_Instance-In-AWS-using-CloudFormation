# Create-vpc_with_attached_ec2_Instance-In-AWS-using-CloudFormation

AWS CloudFormation is a service that helps you model and set up your AWS resources so that you can spend less time managing those resources and more time focusing on your applications that run in AWS. You create a template that describes all the AWS resources that you want (like Amazon EC2 instances or Amazon RDS DB instances), and CloudFormation takes care of provisioning and configuring those resources for you. You don't need to individually create and configure AWS resources and figure out what's dependent on what

steps

*Create a new VPC (isolated network) to hold our resources.

*Create a new public_subnet and private_subnet. in a VPC we can have one or more subnets.

*Add new security group that allows SSH and HTTP traffic.

*Create a new instance with this security group and attached it to public subnet of vpc.
