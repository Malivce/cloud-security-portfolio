# S3 Security — My Notes

## What is Amazon S3
Amazon S3 is an object storage service commonly used to store application data, backups, logs, and static files.

## Why S3 is a common source of data leaks
- Buckets can be accidentally configured as public
- Misconfigured permissions may allow unauthorized access
- Sensitive data is often stored without proper access controls

## Key S3 security controls
- Block Public Access to prevent accidental public exposure
- Bucket policies to control who can access objects
- Encryption at rest and in transit to protect stored data

## Security mindset
S3 security is primarily about configuration. Most S3-related incidents are caused by human error, not AWS service failures.
Public access allows anyone on the internet to read S3 objects without authentication and is a common cause of data breaches.
