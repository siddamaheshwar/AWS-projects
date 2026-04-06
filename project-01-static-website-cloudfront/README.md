# 🌐 Project 01: Static Website Hosting using AWS S3 & CloudFront

---

## 📌 Objective

To deploy a static website using AWS S3 and enhance its performance and global availability using CloudFront.

---

## 📖 Project Description

This project demonstrates how to host a static website using Amazon S3 and distribute it globally with low latency using AWS CloudFront. The setup ensures high availability, scalability, and faster content delivery.

---

## 🛠️ AWS Services Used

* Amazon S3 (Simple Storage Service)
* Amazon CloudFront (Content Delivery Network)

---

## 🏗️ Architecture Overview

S3 bucket is used to store static files (HTML, CSS).
CloudFront is used to deliver content globally through edge locations.

---

## ⚙️ Implementation Steps

### Step 1: Login to AWS Console

Access AWS Management Console.

### Step 2: Create S3 Bucket

* Navigate to S3 service
* Create a bucket with a unique name

### Step 3: Disable Block Public Access

* Uncheck "Block all public access"
* Save changes

### Step 4: Upload Website Files

* Upload index.html and style.css files

### Step 5: Enable Static Website Hosting

* Enable static hosting
* Set index document as `index.html`

### Step 6: Add Bucket Policy

* Allow public read access to objects

### Step 7: Create CloudFront Distribution

* Open CloudFront service
* Create a new distribution

### Step 8: Configure Origin

* Select S3 bucket as origin
* Configure default settings

### Step 9: Access Website

* Use CloudFront domain URL to access the website

---

## 📸 Screenshots

## 📸 Screenshots

### 🔹 S3 Bucket Creation

![Create S3 Bucket](screenshots/step01-create-s3-bucket-page.png)
![Configure Bucket Settings](screenshots/step02-configure-bucket-settings.png)
![Block Public Access](screenshots/step03-block-public-access-settings.png)
![Bucket Created Successfully](screenshots/step04-bucket-created-success.png)
![S3 Bucket List](screenshots/step05-s3-bucket-list.png)

---

### 🔹 Upload Files to S3

![Upload Files](screenshots/step06-upload-files-to-bucket.png)
![Upload Success](screenshots/step07-upload-success.png)

---

### 🔹 Static Website Hosting Configuration

![Static Website Hosting Page](screenshots/step08-static-website-hosting-page.png)
![Enable Static Hosting](screenshots/step16-enable-static-hosting.png)
![Static Hosting Success](screenshots/step17-static-hosting-success.png)
![Static Website Endpoint](screenshots/step22-static-website-endpoint.png)

---

### 🔹 Bucket Policy Configuration

![Permissions Tab](screenshots/step09-permissions-tab.png)
![Policy Generator](screenshots/step10-policy-generator-page.png)
![Add Policy Statement](screenshots/step11-add-policy-statement.png)
![Policy Created](screenshots/step12-policy-created.png)
![Copy Policy JSON](screenshots/step13-copy-policy-json.png)
![Edit Bucket Policy](screenshots/step14-edit-bucket-policy.png)
![Policy Added](screenshots/step15-policy-added.png)
![Bucket Policy Section](screenshots/step19-bucket-policy-section.png)
![Bucket Policy Success](screenshots/step21-bucket-policy-success.png)

---

### 🔹 Website Output (S3)

![Website Output](screenshots/step20-website-output.png)

---

### 🔹 CloudFront Configuration

![Create Distribution](screenshots/step23-create-cloudfront-distribution.png)
![Review Settings](screenshots/step24-cloudfront-review-settings.png)
![Distribution Created](screenshots/step25-cloudfront-created-success.png)
![Distribution Details](screenshots/step26-cloudfront-distribution-details.png)
![Edit Settings](screenshots/step27-edit-cloudfront-settings.png)
![Security Settings](screenshots/step28-cloudfront-security-settings.png)

---

### 🔹 Final Output (CloudFront)

![Website via CloudFront](screenshots/step29-cloudfront-website-working.png)


---

## 🌍 Output

The website is successfully hosted and accessible globally using CloudFront with low latency.

---

## 💡 Key Learnings

* Static website hosting using S3
* Content delivery using CloudFront
* Managing public access using bucket policies
* Understanding AWS global infrastructure

---

## 👨‍💻 Author

Mahesh
