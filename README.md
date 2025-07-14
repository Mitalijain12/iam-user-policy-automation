# IAM User & Policy Automation (AWS Boto3)

This project automates the creation of IAM users, attaches AWS-managed or custom policies, and generates access keys using Python (Boto3).

## 🔧 Features
- Create IAM users with programmatic access
- Attach AWS managed policy (e.g., `AmazonS3ReadOnlyAccess`)
- Optionally create and attach a custom policy
- Automatically generate and display access keys

## 💻 Tech Stack
- Python 3.x
- Boto3
- AWS IAM

## 🧪 Example Usage
```bash
$ python create_iam_user.py
Enter IAM username: dev-user-01
User created, policy attached, and keys generated.
