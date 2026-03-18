# kerre
A respository to document how to create an EC2 instance
# 1. Log in to AWS Console
Go to the AWS Management Console (console.aws.amazon.com in Bing).

From the services menu, select EC2.

# 2. Launch a New Instance
Click Launch Instance.

Give your instance a name (e.g., MyFirstEC2).

# 3. Choose an Amazon Machine Image (AMI)
Select an operating system image, such as:

Amazon Linux 2 (lightweight, AWS-optimized).

Ubuntu Server (popular for development).

# 4. Select Instance Type
For beginners, choose t2.micro (eligible for the free tier).

# 5. Configure Instance Details
Leave defaults for now (1 instance, default VPC).

Advanced users can customize networking and IAM roles.

# 6. Add Storage
Default 8 GB is fine for testing.

Increase if you plan to store more data.

# 7. Add Tags
Add a tag like Name: MyFirstEC2 to easily identify your instance.

# 8. Configure Security Group
Create a new security group.

Allow SSH (port 22) for remote access.

Optionally allow HTTP (port 80) or HTTPS (port 443) if hosting a website.

# 9. Key Pair
Create a new key pair (RSA).

Download the .pem file — this is your private key for SSH access.

# 10. Launch Instance
Click Launch.

Wait a few minutes for AWS to provision your instance.
