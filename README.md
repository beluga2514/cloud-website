# 🌐 Cloud Website Project - CI/CD Edition

## 🚀 Overview
This is a static website hosted on an **AWS EC2 instance using Apache**, and deployed automatically using **Jenkins CI/CD**. It was built as a solo DevOps project by Vijay.

## 📡 Live Site
Visit the live website here:  
👉 [http://107.21.86.49](http://107.21.86.49)

> ⚠️ Note: The site may stop working after AWS Lab ends, but the project is fully documented and reproducible.

## 🛠️ Tech Stack
- **HTML** (Frontend UI)
- **Apache** (Web Server)
- **Ubuntu EC2** (Cloud Hosting)
- **Git + GitHub** (Version Control)
- **Jenkins** (CI/CD Automation)
- **Linux Shell + SSH**

## 🔁 Workflow

1. HTML code is pushed to GitHub repo.
2. Jenkins pulls the repo using Git plugin.
3. Jenkins copies `index.html` to `/var/www/html/`.
4. Apache serves the updated website live at the public IP.

## 📁 Project Structure

```bash
cloud-website/
├── index.html        # Main HTML file
└── README.md         # Project documentation
