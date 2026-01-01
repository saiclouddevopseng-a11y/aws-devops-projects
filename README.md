# Centralized File Sharing & Backup System (AWS)

## Project Overview
Designed and implemented a centralized file sharing and backup solution using core AWS services.
Multiple EC2 instances access a shared file system using Amazon EFS, with automated backups to Amazon S3.

## AWS Services Used
- Amazon EC2
- Amazon EFS
- Amazon S3
- AWS IAM
- Amazon CloudWatch

## Implementation Summary
- Launched EC2 instances in the same VPC
- Created and mounted Amazon EFS across multiple EC2 instances
- Configured IAM roles for secure S3 access
- Implemented automated file backup from EFS to S3 using Linux scripting
- Monitored system health using CloudWatch

## Tools & Technologies
- Linux (Shell scripting)
- systemd
- inotify

## Outcome
- Centralized and highly available shared storage
- Automated and secure backup solution
- Scalable architecture suitable for enterprise workloads

## Documentation
Detailed implementation steps are available in the attached project document.
