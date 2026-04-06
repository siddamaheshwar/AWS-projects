
# 🔐 Project 02: Secure Static Website using Private S3 & CloudFront

---

## 📌 Objective

To host a secure static website using a private S3 bucket and deliver content through CloudFront using Origin Access Control (OAC).

---

## 📖 Project Description

This project demonstrates how to secure a static website by restricting direct public access to the S3 bucket and allowing access only through CloudFront. This improves security while maintaining performance.

---

## 🛠️ AWS Services Used

* Amazon S3 (Private Bucket)
* Amazon CloudFront
* Origin Access Control (OAC)

---

## ⚙️ Implementation Steps

### Step 1: Create Private S3 Bucket

* Create bucket
* Keep public access BLOCKED

### Step 2: Upload Website Files

* Upload HTML/CSS files

### Step 3: Create CloudFront Distribution

* Select S3 as origin

### Step 4: Enable OAC

* Create and attach Origin Access Control

### Step 5: Update Bucket Policy

* Allow access only from CloudFront

### Step 6: Test via CloudFront

* Access using CloudFront URL

### Step 7: Verify Security

* Direct S3 URL should be blocked

---

## 🔐 Security Concept

* S3 bucket is private ❌ public access
* CloudFront acts as secure gateway ✅
* Only CloudFront can access S3

---

## 🌍 Output

Secure static website accessible only via CloudFront, not directly from S3.

---

## 👨‍💻 Author

Mahesh
