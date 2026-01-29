# AWS Cloud Security Checklist

Practical security controls for AWS environments.

## IAM
- Enable MFA
- Use least privilege
- Avoid root usage

## VPC
- Private subnets for workloads
- NAT Gateway for outbound access
- Restrict security groups

## S3
- Block public access
- Enable encryption
- Enable logging

## Monitoring
- CloudTrail enabled
- GuardDuty enabled
- CloudWatch alerts

## Containers
- Scan Docker images
- Avoid running as root
- Limit exposed ports

## CI/CD
- Integrate SonarQube
- Perform security scans
- Protect main branches
