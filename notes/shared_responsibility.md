# AWS Shared Responsibility Model — My Notes

## What AWS is responsible for (examples)
- Physical security of data centers (buildings, hardware, power, networking)
- Security of the underlying cloud infrastructure (servers, storage, networking)
- Managed service security (patching and availability of core AWS services)

## What the customer is responsible for (examples)
- Identity and access management (IAM users, roles, permissions, MFA)
- Data protection (encryption, backups, access control)
- Secure configuration of services (S3 bucket permissions, security groups, network rules)

## Why it matters
- Misunderstanding this model often leads to cloud security incidents caused by misconfiguration, not AWS failures.
