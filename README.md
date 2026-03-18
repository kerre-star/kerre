# kerre
A respository to document how to create an EC2 instance
# 1. Log in to AWS Console
Go to the AWS Management Console (console.aws.amazon.com in Bing).

From the services menu, select EC2.
<img width="561" height="119" alt="search ec2" src="https://github.com/user-attachments/assets/85450d67-939f-404a-9fe3-b52cebc563c9" />


# 2. Launch a New Instance
Click Launch Instance.
<img width="944" height="320" alt="select luach instance" src="https://github.com/user-attachments/assets/c1d3a46b-aaff-42ef-89b7-943407ee1dbd" />


Give your instance a name (e.g., MyFirstEC2).

<img width="914" height="245" alt="name tag" src="https://github.com/user-attachments/assets/7cb409ed-0ae1-4e1a-95bd-b0c4c5375048" />

# 3. Choose an Amazon Machine Image (AMI)
Select an operating system image, such as:

Amazon Linux 2 (lightweight, AWS-optimized).
<img width="911" height="371" alt="AMI" src="https://github.com/user-attachments/assets/3e21477c-73d4-499e-bf2e-3d6f69054df5" />


Ubuntu Server (popular for development).

# 4. Select Instance Type
For beginners, choose t2.micro or t3.micro (eligible for the free tier).

<img width="574" height="201" alt="INSTANCE TYPE" src="https://github.com/user-attachments/assets/0bdb4e81-85b9-4447-b539-4714b476dacf" />

# 5. Configure Instance Details
Leave defaults for now (1 instance, default VPC).

Advanced users can customize networking and IAM roles.

# 6. Add Storage
Default 8 GB is fine for testing.

<img width="1803" height="692" alt="STORAGE" src="https://github.com/user-attachments/assets/dbd9a74c-0e51-450f-b4ec-edc48e0813a8" />

Increase if you plan to store more data.

# 7. Add Tags
Add a tag like Name: MyFirstEC2 to easily identify your instance.
<img width="914" height="245" alt="name tag" src="https://github.com/user-attachments/assets/a92fa0cc-ac0f-4c43-975e-afa462dd06d0" />


# 8. Configure Security Group
Create a new security group.
<img width="609" height="328" alt="SECURITY GROUP" src="https://github.com/user-attachments/assets/cd78eeed-fe43-4a37-bd6b-38ca09498750" />


Allow SSH (port 22) for remote access.
<img width="575" height="175" alt="ENABLE SSH" src="https://github.com/user-attachments/assets/3f13bd1b-d66c-4f10-a35f-07faff6faef4" />


Optionally allow HTTP (port 80) or HTTPS (port 443) if hosting a website.

# 9. Key Pair
Create a new key pair (RSA).
<img width="575" height="188" alt="CREATE KEY PAIR" src="https://github.com/user-attachments/assets/5ed3b5d6-6aef-483c-bb5f-d2300bf18b4d" />


Download the .pem file — this is your private key for SSH access.

# 10. Launch Instance
Click Launch.<img width="902" height="346" alt="LAUNCH INSTANCE" src="https://github.com/user-attachments/assets/035e2b66-bab4-4acd-8bca-a11c8a7ab87c" />


Wait a few minutes for AWS to provision your instance.<img width="387" height="98" alt="WAITING" src="https://github.com/user-attachments/assets/c2cf1bd8-14e7-4400-8e2a-3a57928169d7" />

