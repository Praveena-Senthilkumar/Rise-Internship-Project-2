# Rise-Internship Project 2: Host Static Website using AWS S3 & CloudFront

##  Overview

This project demonstrates how to host a static website using Amazon S3 and deliver it globally using CloudFront CDN.

The goal is to improve website performance, availability, and scalability using AWS cloud services.

---

##  Architecture

User → CloudFront (CDN) → Amazon S3 → Static Website Files

CloudFront caches content at global edge locations to reduce latency and improve performance.

---

##  Services Used

- Amazon S3 (Static Website Hosting)
- Amazon CloudFront (Content Delivery Network)
- HTML
- CSS
- JavaScript

---

---

## Implementation Steps

### 1️⃣ Create S3 Bucket
- Created a new S3 bucket
- Disabled block public access
- Enabled static website hosting
- Set index document as `index.html`

### 2️⃣ Upload Static Files
- Uploaded HTML, CSS, and JS files
- Made objects publicly accessible

### 3️⃣ Configure CloudFront
- Created CloudFront distribution
- Selected S3 bucket as origin
- Enabled HTTPS redirection
- Set default root object as `index.html`

---

## Outcome

- Website hosted on Amazon S3
- Content delivered globally via CloudFront CDN
- Improved performance and availability
- Secure HTTPS access
---

## Key Learnings

- Static website hosting in AWS
- CDN configuration using CloudFront
- Difference between S3 endpoint and CloudFront distribution
- Global content delivery concepts
- Cloud architecture basics

---

## Screenshots
<img width="1919" height="1022" alt="Image" src="https://github.com/user-attachments/assets/1d077eda-b91c-4cde-b02b-7de66ea43ca4" />
<br><br>
<img width="1919" height="1024" alt="Image" src="https://github.com/user-attachments/assets/08d45e55-eaa4-465e-9ff0-cc358cf9bd86" />
<br><br>
<img width="1919" height="754" alt="Image" src="https://github.com/user-attachments/assets/40bd38ea-ad5a-4849-9b13-8ea0e7245510" />
<br><br>
<img width="1920" height="1080" alt="Image" src="https://github.com/user-attachments/assets/fb9b8272-7d24-470a-a210-0408fb34e639" />
<br><br>
<img width="1919" height="713" alt="Image" src="https://github.com/user-attachments/assets/496921f9-17a8-4763-a44b-a262a17b3fc8" />
