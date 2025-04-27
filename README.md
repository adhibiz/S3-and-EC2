# CLOUD-STORAGE-CREATION-S3-AND-LAUNCHING-AN-EC2-INSTANCE-IN-AWS-
## Aim:
To create a Simple Storage Service (S3) in AWS and to launch an EC2
instance in AWS.
# To Create a Simple Storage Service (S3) in AWS and to Launch an EC2 Instance in AWS

## Procedure

### a) Steps to Create a First S3 Bucket:
1. **Sign in to the AWS Management Console**  
   Go to [https://console.aws.amazon.com/s3](https://console.aws.amazon.com/s3).
2. **Open the S3 Service**  
   In the console, type **S3** in the search bar and select **S3**.
3. **Create Bucket**  
   Click the **Create bucket** button.
4. **Configure Bucket Settings**  
   - **Bucket Name:** Choose a globally unique name.  
   - **AWS Region:** Select the desired region.
5. **Object Ownership**  
   - Choose between:  
     - **ACLs disabled (recommended)** – Bucket owner has full control.  
     - **ACLs enabled** – Control access via access control lists.
6. **Block Public Access Settings**  
   - By default, public access is blocked. Leave it unless required.
7. **Bucket Versioning (Optional)**  
   - Choose whether to enable versioning for objects.
8. **Encryption (Optional)**  
   - Select encryption option (SSE-S3, SSE-KMS, or none).
9. **Advanced Settings (Optional)**  
   - Add tags, configure logging, etc.
10. **Create the Bucket**  
    - Click **Create bucket** at the bottom of the page.

---

### b) Steps to Launch an EC2 Instance:
1. Go to the **EC2 Dashboard** in AWS Console.
2. Click on **Launch Instance**.
3. Choose an **Amazon Machine Image (AMI)** (e.g., Amazon Linux).
4. Select an **Instance Type** (e.g., t2.micro for Free Tier).
5. Create or choose a **Key Pair** for SSH access.
6. Configure **Network Settings** (default VPC/subnet is fine).
7. Configure **Storage** (default root volume is fine).
8. Review all settings and click **Launch Instance**.
9. Wait for the instance to enter the **Running** state.

---

### c) Connect to Your Instance:
- **Linux:** Use SSH command with your `.pem` key.
- **Windows:** Use RDP with decrypted admin password.

---

### d) Steps to Clean Up (Terminate the Instance):
1. Go to **EC2 Instances**.
2. Select your instance → **Instance State** → **Terminate**.


### Snap Shots:

Snap Shot 1: Simple Storage Service (S3)
![image](https://github.com/user-attachments/assets/58e317e5-83a6-43c0-b6ca-f2a6cff780ae)

Snap Shot 2: EC2 (Elastic Compute Cloud) – Instance
![image](https://github.com/user-attachments/assets/996e2d59-6ebf-4dbb-a9d0-309e7535f821)

## Result:
Thus, a Simple Storage Service (S3) and EC2 (Elastic Compute Cloud) - instance
has been successfully created and launched in AWS
