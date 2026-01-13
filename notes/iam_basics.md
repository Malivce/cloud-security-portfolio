# IAM Basics — My Notes

## What is IAM
IAM (Identity and Access Management) is used to control who can access AWS resources and what actions they are allowed to perform.

## IAM User
- Represents a person or service with long-term credentials
- Typically used for administrators or automation accounts
- Should always be protected with MFA

## IAM Role
- Provides temporary access to AWS resources
- Commonly used by applications and services
- Reduces the risk of leaked long-term credentials

## IAM Policy
- Defines permissions using allow or deny rules
- Attached to users, roles, or groups
- Should follow the principle of least privilege

## Why IAM is critical for cloud security
- Most cloud security incidents are caused by excessive permissions
- Misconfigured IAM can lead to data exposure or account compromise
