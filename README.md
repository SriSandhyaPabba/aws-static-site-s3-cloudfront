# 🌐 Static Website Hosting on AWS with S3 and CloudFront

## 📌 Project Overview
Built and deployed a secure, scalable, and cost-effective static website using Amazon S3 for object storage and CloudFront for global content delivery. This project demonstrates a complete serverless hosting solution including bucket setup, policy configuration, and performance optimization.

## 🧰 Key Technologies
- Amazon S3 (static website hosting)
- AWS CloudFront (CDN)
- IAM Roles & Policies
- S3 Bucket Policy
- Optional: Route 53 for custom domain
- Static HTML/CSS website

## 🏗️ Architecture Overview

[Local Dev]
│
▼
[S3 Bucket (Public Access - Static Website)]
│
▼
[CloudFront CDN Distribution]
│
▼
[Global Users]

## 🔧 Implementation Details

- Created a globally unique S3 bucket and enabled **static website hosting**
- Uploaded HTML, CSS, and image files into the bucket
- Configured **bucket policy** for public read access (while securing write access)
- Set `index.html` and `error.html` as default docs
- Set up **CloudFront distribution** with S3 as origin for caching and HTTPS
- (Optional) Integrated with Route 53 to use a custom domain name

## ⚙️ Configuration Notes

- **Index document**: `index.html`
- **Error document**: `error.html`
- **S3 Bucket Policy**: Public read-only access for website content
- **CloudFront**: Enabled default SSL (HTTPS) for secure delivery

## ✅ Outcome

- Successfully hosted a static website fully on AWS using only S3 + CloudFront
- CloudFront drastically improved performance by caching content globally
- Gained hands-on experience with IAM, public access policies, and serverless architecture

## 💡 Use Case

Perfect for:
- Static portfolios
- Marketing websites
- Landing pages
- Blogs or documentation pages

## 🧠 Skills Demonstrated

- ✅ S3 static website hosting
- ✅ Secure public access via IAM and S3 bucket policies
- ✅ CloudFront CDN configuration
- ✅ HTTPS hosting using AWS-managed certificates
- ✅ Optional Route 53 domain mapping

---

