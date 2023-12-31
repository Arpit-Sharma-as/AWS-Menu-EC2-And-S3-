# AWS Resource Management Script

This Python script allows you to interact with AWS services using the Boto3 library. You can either launch an EC2 instance or create an S3 bucket based on user input.

## Prerequisites

- Python installed on your machine
- Boto3 library (`pip install boto3`)
- AWS credentials configured on your machine

## Usage

1. Clone the repository:

    ```bash
    git clone <repository-url>
    cd <repository-directory>
    ```

2. Install the required Python packages:

    ```bash
    pip install boto3
    ```

3. Run the script:

    ```bash
    python aws_resource_management.py
    ```

4. Choose the operation you want to perform:

    - For launching an EC2 instance, enter `1`.
    - For creating an S3 bucket, enter `2`.

5. Follow the on-screen prompts to complete the operation.

## Operations

### 1. Launch EC2 Instance

This option allows you to launch a new EC2 instance with the following specifications:

- AMI: <Your AMI ID>
- Instance Type: t2.micro
- Region: ap-south-1

### 2. Create S3 Bucket

This option allows you to create a new S3 bucket with the following specifications:

- Bucket Name: <Your Bucket Name>
- Region: ap-south-1
