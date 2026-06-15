# Static Website Hosting on AWS S3

## 🌐 Live Website
**Visit:** http://statichoster.s3-website.eu-north-1.amazonaws.com

## 📋 Project Overview
A static portfolio website hosted on Amazon S3. This project demonstrates cloud hosting fundamentals and AWS service knowledge.

## 🎯 Key Features
- ✅ Low-cost hosting (~$0.50/month)
- ✅ High availability and reliability
- ✅ Fast loading times
- ✅ Simple and scalable architecture
- ✅ Version controlled on GitHub

## 🏗️ Architecture
┌─────────────────┐

│  GitHub Repo    │ (Code Storage)

│  (index.html)   │

└────────┬────────┘

│ git push

↓

┌─────────────────┐

│  AWS S3 Bucket  │ (Web Hosting)

│ statichoster    │

└────────┬────────┘

│

↓

🌍 LIVE WEBSITE

## 💻 Technologies Used
- **HTML5** - Markup
- **CSS3** - Styling
- **AWS S3** - Static website hosting
- **AWS Region** - eu-north-1 (Stockholm)

## 🚀 Deployment Steps

### Local Setup
```bash
# Clone repository
git clone https://github.com/mugeshmk93/aws-s3-website.git
cd aws-s3-website
```

### AWS S3 Deployment
1. Create S3 bucket (`statichoster`)
2. Upload `index.html` to bucket
3. Enable Static Website Hosting
   - Settings → Properties → Static website hosting
   - Index document: `index.html`
4. Make files public (via bucket policies)
5. Access website via S3 endpoint

## 📁 Project Structure
aws-s3-website/

├── index.html      # Main website file

├── README.md       # Project documentation

└── .gitignore      # Git ignore file

## 💰 Cost Breakdown
- **S3 Storage:** ~$0.023/GB/month
- **Data Transfer:** ~$0.09/GB/month
- **Typical Monthly Cost:** $0.50 - $2.00

*Free tier eligible for first 12 months (5GB storage, 1GB data transfer)*

## 🔐 Security
- S3 bucket configured for public read access
- Files served via HTTP
- No sensitive data stored

## 📚 What I Learned
- AWS S3 bucket creation and configuration
- Static website hosting setup
- HTML/CSS design
- Cloud infrastructure basics
- Git version control

## 🎓 AWS Services Used
- **Amazon S3** - Object storage and web hosting
- **AWS Region** - eu-north-1 (Stockholm)

## 🔗 Quick Links
- **Live Website:** http://statichoster.s3-website.eu-north-1.amazonaws.com
- **GitHub:** https://github.com/mugeshmk93/aws-s3-website
- **My Portfolio:** [Add your portfolio link if you have one]

## 📞 Contact
- **Email:** mugeshmk93@gmail.com
- **GitHub:** @mugeshmk93

## 📝 Notes for Recruiters
This project demonstrates:
✅ Understanding of AWS cloud services  
✅ Hands-on experience with S3 and static hosting  
✅ HTML/CSS web development skills  
✅ Version control with Git  
✅ Ability to deploy and manage web applications  

---

**Created:** January 2025  
**Last Updated:** January 2025  
**Status:** ✅ Active and Live
