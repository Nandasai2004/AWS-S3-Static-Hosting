# ☁️ AWS S3 Static Website Hosting

## 📌 Project Overview

This project demonstrates how to host a static website using **Amazon Simple Storage Service (Amazon S3)**. The website is deployed using an S3 bucket and accessed through the static website hosting endpoint.

The project provides hands-on experience with AWS cloud storage, bucket configuration, permissions, and static website deployment.

## 🎯 Objectives

- Create an Amazon S3 bucket.
- Upload website files to the bucket.
- Enable static website hosting.
- Configure bucket permissions and a bucket policy.
- Access and test the hosted website using the S3 website endpoint.

## 🛠️ Technologies Used

- **Amazon S3** – Object storage and static website hosting.
- **AWS Management Console** – AWS resource configuration.
- **HTML** – Static website content.
- **Web Browser** – Website testing and verification.

## 🏗️ Architecture

```text
       User / Web Browser
               |
               v
     Amazon S3 Website Endpoint
               |
               v
       S3 Bucket Configuration
               |
               v
       Static Website Files
```

## 🚀 Implementation Steps

### Step 1: Create an S3 Bucket
- Open the AWS Management Console.
- Navigate to Amazon S3.
- Create a new bucket with a globally unique name.
- Select the required AWS Region.

### Step 2: Upload Files
- Open the created bucket.
- Upload the required website files.
- Verify that the upload is successful.

### Step 3: Enable Static Website Hosting
- Open the bucket's **Properties** tab.
- Locate Static website hosting.
- Enable website hosting.
- Configure the index document, such as `index.html`.

### Step 4: Configure Permissions
- Review the Block Public Access settings.
- Configure the required bucket policy to allow public read access to website objects, if public hosting is intended.
- Ensure the configuration follows AWS security best practices.

### Step 5: Test the Website
- Copy the S3 static website endpoint.
- Open it in a web browser.
- Verify that the website loads successfully.

## 🌐 Website Preview

The deployed website displays:

**Welcome to Nanda's Website!**

- My first static website hosted on AWS S3.
- Service: Amazon S3
- Learning Cloud Computing 🚀

## 📚 Key Learnings

- Understanding Amazon S3 buckets and objects.
- Uploading files to cloud storage.
- Configuring static website hosting.
- Understanding bucket policies and public access settings.
- Deploying and testing a static website on AWS.

## 🔐 Security Note

Public access should be enabled only when required. For production websites, consider using **Amazon CloudFront with Origin Access Control (OAC)** and keeping the S3 bucket private. S3 website endpoints do not provide HTTPS directly.

## 👨‍💻 Author

**Gorlamandala Nanda Sai**

B.Tech – Artificial Intelligence and Machine Learning

GitHub: [@Nandasai2004](https://github.com/Nandasai2004)

## ⭐ Conclusion

This project demonstrates the basic process of hosting a static website on Amazon S3 and provides practical experience with AWS storage, website hosting, permissions, and cloud deployment.
