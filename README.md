# 🌐 Vahini Ananthoju — Personal Portfolio

A personal portfolio website hosted as a static site on **AWS S3**, accessible globally with zero server provisioning.

🔗 **Live Site:** [vahini-portfolio-2026.s3-website.ap-south-1.amazonaws.com](http://vahini-portfolio-2026.s3-website.ap-south-1.amazonaws.com)

---

## 📌 Project Overview

This project is part of **Project 1: The Global Launch** — a cloud internship initiative focused on hosting static websites using cloud storage services without managing any backend infrastructure.

**Scenario:** As a freelance developer, the goal was to build and deploy a personal portfolio website that loads instantly anywhere in the world — without paying for expensive servers.

---

## ☁️ Hosting Architecture

| Detail | Value |
|---|---|
| Cloud Provider | AWS |
| Service | Amazon S3 (Simple Storage Service) |
| Region | ap-south-1 (Mumbai) |
| Hosting Type | Static Website Hosting |
| Access | Public via Bucket Policy |

---

## 🚀 Deployment Steps

1. **Created an S3 Bucket** — Named `vahini-portfolio-2026` in the `ap-south-1` region
2. **Enabled Static Website Hosting** — Set `index.html` as the entry point
3. **Uploaded Portfolio Files** — HTML resume/portfolio files uploaded to the bucket
4. **Configured Bucket Policy** — Set public read access to make the site accessible over the internet
5. **Accessed the Live URL** — The site is now live and shareable globally

---

## 📁 Project Structure

```
vahini-portfolio-2026/
├── index.html        # Main portfolio page
└── assets/           # Images, fonts, and other static assets
```

---

## 🎯 Outcome

- ✅ Live, shareable URL accessible over the internet
- ✅ No server provisioning required
- ✅ Instant global load performance via AWS infrastructure
- ✅ Cost-effective static hosting

---

## 🛠️ Tools & Technologies

- **AWS S3** — Static website hosting
- **HTML** — Portfolio markup
- **Amazon Web Services Console** — Bucket configuration and deployment

---

## 👩‍💻 Author

**Vahini Ananthoju**
GitHub: [@Vahini Ananthoju](https://github.com)

---

> *This project is part of a cloud internship program. Project 1 is the essential starting point — earn your badge by completing and verifying this deployment!* 🏅
