
# 🚀 Deploy Your AWS Study Tracker to AWS S3 (Static Website Hosting)

Easily publish your `index.html` file online using AWS S3.

---

## 🛠️ What You Need

- An AWS account
- S3 (Simple Storage Service) access
- Optional: custom domain (via Route 53)

---

## ✅ Steps to Deploy

### 1. Create an S3 Bucket

1. Go to the [S3 Console](https://s3.console.aws.amazon.com/s3/)
2. Click **Create bucket**
3. Set a unique name like: `aws-study-tracker-username`
4. Uncheck **Block all public access**
5. Click **Create bucket**

---

### 2. Upload Your Website Files

1. Open your bucket
2. Click **Upload**
3. Upload `index.html`
4. After upload, select the file → **Actions** → **Make public**

---

### 3. Enable Static Website Hosting

1. Go to **Properties** tab of your bucket
2. Scroll to **Static website hosting**
3. Click **Edit**
4. Enable it and set:
   - **Index document:** `index.html`
5. Save changes

---

### 4. Access Your Website

You will get a URL like this:

```
http://your-bucket-name.s3-website-region.amazonaws.com
```

Share it or bookmark it!

my website hosted on AWS for your refrace =) :

[Aseel AWS study tracker](https://aws-study-tracker-aseelalawadh.s3.us-east-1.amazonaws.com/index.html)

---

## 💡 Optional Enhancements

- Use Route 53 to attach your own domain (e.g., `tracker.mydomain.com`)
- Use CloudFront for HTTPS and global speed
- Add versioning or backups to your S3 bucket

---

Enjoy hosting your AWS study tracker online! ☁️✨
