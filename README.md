# Simple CI/CD Pipeline with Bash, Python, and Cron

This project sets up a lightweight CI/CD pipeline that automatically deploys a simple HTML website to an Nginx server hosted on an AWS EC2 or local Linux instance. It uses Bash, Python, and cron jobs to check for new commits and redeploy changes.

---

## 🚀 Features

- Auto-checks GitHub for new commits
- Pulls and deploys latest code automatically
- Restarts Nginx to serve updated content
- Lightweight and easy to configure

---

## 📁 Project Structure

├── check_commits.py # Python script to check GitHub for updates
├── deploy.sh # Bash script to deploy latest code
├── index.html # Sample HTML content
├── setup_cron.sh # Bash script to register cron job
└── README.md # This file

🧪 Testing the CI/CD Pipeline
Push a new commit to your GitHub repository.

Wait ~2 minutes.

Visit your server’s IP address — changes should be live!


![image](https://github.com/user-attachments/assets/45bb6f5f-1473-43d6-a280-b1441b12d663)

![image](https://github.com/user-attachments/assets/984fb708-f8ce-41e7-b536-b7718ea5d52e)

![image](https://github.com/user-attachments/assets/2c7089b6-eeab-4548-b7fa-f3602e7c7daf)
![image](https://github.com/user-attachments/assets/cf543966-6412-4e67-a6cb-84402d2e962d)


![image](https://github.com/user-attachments/assets/2fd36a27-2861-40cf-b66c-1a096e857290)
![image](https://github.com/user-attachments/assets/09388277-98e3-4c7f-9db4-cf72ea60cdc9)

