# 🚀 AWS CloudFront + Amazon S3 Static Website Deployment

## 📌 Project Overview

This project demonstrates a production-style static website deployment on AWS using Amazon S3 and AWS CloudFront CDN.

The architecture was designed to improve:
- Global content delivery
- Website performance
- Scalability
- HTTPS accessibility
- Static website optimization

The project also involved troubleshooting and resolving CloudFront origin configuration issues during deployment.

---

# 🏗️ Architecture

```text
User
   ↓
AWS CloudFront CDN
   ↓
Amazon S3 Static Website# aws-cloudfront-s3-static-website
Production-style AWS CloudFront CDN and Amazon S3 static website deployment project.

# ☁️ AWS Services Used

- Amazon S3
- AWS CloudFront
- Static Website Hosting
- CDN (Content Delivery Network)
- AWS Cloud Infrastructure

---

# 🔧 Key Implementations

✅ Configured Amazon S3 static website hosting

✅ Created AWS CloudFront distribution

✅ Integrated S3 static website endpoint with CloudFront

✅ Enabled global edge content delivery

✅ Implemented HTTPS website accessibility

✅ Optimized static website delivery performance

✅ Validated CDN architecture deployment

---

# 🛠️ Troubleshooting & Resolution

## Issue Encountered
CloudFront returned:

xml
<Code>AccessDenied</Code>
<Message>Access Denied</Message>


## Root Cause
The CloudFront origin was initially configured using the S3 REST endpoint instead of the S3 static website endpoint.

## Resolution
Updated the CloudFront origin configuration to use:

text
olajide-devops-s3-project-2026.s3-website-us-east-1.amazonaws.com


This successfully resolved the access issue and restored proper content delivery.

---

# 🌐 CloudFront Distribution

## Distribution Domain
text
https://d3qifnezr4ub6.cloudfront.net


---

# 📸 Project Screenshots

## Screenshot Files
- 01-cloudfront-distribution-overview.png
- 03-live-cloudfront-website.png
- 04-s3-static-website-hosting.png

---

# 💡 Skills Demonstrated

- AWS CloudFront CDN Deployment
- Amazon S3 Static Website Hosting
- CDN Configuration
- Cloud Infrastructure Deployment
- AWS Troubleshooting
- Static Website Optimization
- Cloud Architecture Validation
- HTTPS Content Delivery

---

# 🎯 Project Outcome

Successfully deployed and validated a production-style static website architecture using Amazon S3 and AWS CloudFront CDN with global content delivery and optimized website accessibility.

---

# 👨‍💻 Author

## Olajide Adedayo
AWS Cloud & DevOps Engineer

GitHub:
https://github.com/olajide-adedayo

LinkedIn:
https://www.linkedin.com/in/olajide-adedayo-9126593b3
