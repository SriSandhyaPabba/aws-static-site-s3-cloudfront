# Static Website Hosting using Amazon S3 and CloudFront

This project involved hosting a fully static HTML/CSS website on AWS using S3 and delivering content globally via CloudFront.

## Features

- **Static Hosting**: Enabled on S3 with public read access via bucket policy
- **CDN Integration**: CloudFront configured for HTTPS delivery
- **Routing**: index.html and error.html implemented
- **Optional**: Route 53 mapping for custom domain
- **Security**: IAM permissions for S3 access

## Services Used

- Amazon S3
- AWS CloudFront
- IAM Roles
- Route 53 (optional)
- SSL via AWS Certificate Manager

## Outcome

Website successfully deployed and accessible over HTTPS via CloudFront. Secure, serverless, and highly available. Total cost well within Free Tier.
