# Host-Static-Website-with-S3-CloudFront-

Project link -
https://dp994uagzkjd9.cloudfront.net/

---

## 🌐 Static Website Hosting using AWS S3 and CloudFront

This project demonstrates how to **host a static website** using **Amazon S3** for storage and **Amazon CloudFront** as a Content Delivery Network (CDN) for fast, global access.

### 🚀 Features

* ✅ Static website hosting via **Amazon S3**
* ✅ Global content delivery using **CloudFront**
* ✅ Secure access to S3 via **Origin Access Control (OAC)**
* ✅ Custom **index.html** as root object
* ✅ Optional public access configuration for testing

---

### 🏗️ Architecture Overview

1. **S3 Bucket**: Stores all static web files like `index.html`, `style.css`, and images.
2. **CloudFront Distribution**: Delivers website content globally via CDN.
3. **OAC (Origin Access Control)**: Ensures only CloudFront can access the S3 bucket securely.
4. **Default Root Object**: Set as `index.html` for homepage delivery.

---

### 📁 Folder Structure

```
📦your-project/
 ┣ 📄index.html
 ┣ 📄style.css
 ┗ 📄README.md
```

---

### 🛠️ Deployment Steps

1. **Create an S3 bucket** and upload static site files (`index.html`, etc.)
2. **Disable public access** (optional if using OAC)
3. **Create a CloudFront distribution**

   * Set S3 bucket as origin
   * Enable OAC for secure access
   * Set default root object to `index.html`
4. **Test via CloudFront domain URL** (e.g., `https://dxxxxxxxxxx.cloudfront.net`)

---

### 🔐 Security

* Used **Origin Access Control (OAC)** to restrict direct access to S3.
* S3 bucket policy allows access **only from the specific CloudFront distribution**.

---

### 🔗 Live Demo (Optional)

> 🌐 [https://dp994uagzkjd9.cloudfront.net]

---

### 📚 Technologies Used

* [AWS S3](https://aws.amazon.com/s3/)
* [AWS CloudFront](https://aws.amazon.com/cloudfront/)
* \[HTML/CSS]

---


