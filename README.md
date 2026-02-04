# Ex No 2: CLOUD-STORAGE-CREATION-S3-AND-LAUNCHING-AN-EC2-INSTANCE-IN-AWS-

# Aim:
To create a Simple Storage Service (S3) in AWS and to launch an EC2 instance in AWS.

# Procedure
a) Steps to Create a first S3 Bucket:

Step 1: Sign in to the AWS Management Console Go to https://console.aws.amazon.com/s3. 

Step 2: Open the S3 Service In the console, type S3 in the search bar and select S3 to open the service dashboard. 

Step 3: Create Bucket Click the Create bucket button. 

Step 4: Configure Bucket Settings

• Bucket name: Choose a globally unique name. • AWS Region: Select the region where you want to store your data.

Step 5: Object Ownership Choose between: ▪ ACLs disabled (recommended) – Bucket owner has full control. ▪ ACLs enabled – Control access via access control lists.

Step 6: Block Public Access Settings By default, all public access is blocked. Leave it as-is unless you need public access. 

Step 7: Bucket Versioning (optional) Choose whether to enable versioning for objects in the bucket.

Step 8: Encryption (optional) Select encryption options (SSE-S3, SSE-KMS, or none). 

Step 9: Advanced Settings (optional) Add tags, configure logging, etc. 

Step 10: Create the Bucket Click Create bucket at the bottom of the page.

b) i. Steps to launch an EC2 Instance

Go to the EC2 Dashboard in AWS Console.

Click on “Launch Instance”.

Choose an Amazon Machine Image (AMI) (e.g., Amazon Linux).

Select an instance type (e.g., t2.micro for Free Tier).

Create or choose a key pair for SSH access.

Configure network settings (use default VPC/subnet).

Configure storage (default root volume is fine).

Review the settings and click “Launch Instance”.

Wait for the instance to enter the running state.

c) Step 3: Connect to Your Instance

• Linux: Use SSH command with your .pem key. • Windows: Use RDP with decrypted admin password.

d) Steps to Clean Up (Terminate the Instance)

Go to EC2 Instances.
Select your instance → Instance State → Terminate.

# Output:

Simple Storage Service:
<img width="1914" height="944" alt="Screenshot 2026-01-29 192624" src="https://github.com/user-attachments/assets/878ee371-6fae-4f16-8b78-90d41f303da2" />


EC2(Elastic Cloud Compute)


<img width="1899" height="939" alt="Screenshot 2026-01-29 192710" src="https://github.com/user-attachments/assets/7e5371a8-4b95-40bb-9b14-e261923faa79" />





# Result:
Thus, a Simple Storage Service (S3) and EC2 (Elastic Compute Cloud) - instance has been successfully created and launched in AWS







# output
<img width="1142" height="604" alt="image" src="https://github.com/user-attachments/assets/d65f4f7b-701c-4757-9214-c4ee68a8f31b" />

<img width="1151" height="633" alt="image" src="https://github.com/user-attachments/assets/648cccd7-e6c6-4fa8-a8ca-a52d1e4c5186" />

<img width="1152" height="593" alt="image" src="https://github.com/user-attachments/assets/efa940ab-f5f9-421b-be5e-ccac608865e0" />

<img width="1152" height="635" alt="image" src="https://github.com/user-attachments/assets/932bd786-df15-4c2d-9bf9-a9d14229c21d" />

 # RESULT
The AWS account was successfully created, with set up for the root user . Additionally, an IAM user was created with specified permissions, allowing for secure, controlled access to AWS resources without the use of the root account.
