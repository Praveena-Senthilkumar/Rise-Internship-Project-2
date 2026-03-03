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
