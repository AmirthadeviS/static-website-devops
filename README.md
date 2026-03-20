#  Static Website Auto Deployment using CI/CD (DevOps Project)

## 📌 Project Overview

This project demonstrates a fully automated CI/CD pipeline to deploy a static website using modern DevOps tools.
Whenever code is pushed to GitHub, the deployment process is triggered automatically without any manual intervention.

---

## 🛠️ Tech Stack

* 🔹 Version Control: GitHub
* 🔹 CI/CD Tool: Jenkins
* 🔹 Containerization: Docker
* 🔹 Web Server: Nginx

---

## ⚙️ CI/CD Workflow

1️⃣ Developer pushes code to GitHub
2️⃣ Jenkins detects the change via webhook / polling
3️⃣ Jenkins pulls the latest code
4️⃣ Docker image is built automatically
5️⃣ Container is created and deployed
6️⃣ Nginx serves the website

✅ Entire process is automated (Zero manual deployment)

---

## 📂 Project Structure

```
static-website-devops/
│── index.html
│── Dockerfile
│── Jenkinsfile
│── README.md
```

---

## 🐳 Docker Configuration

* Base Image: Nginx
* Static files copied to `/usr/share/nginx/html`
* Exposed Port: `8080`

---

## 🌐 Live Output

The application runs locally at:
👉 http://localhost:8080

---

## 📸 Screenshots

✔️ GitHub Repository
✔️ Jenkins Pipeline (Build Success)
✔️ Console Output Logs
✔️ Docker Running Container
✔️ Final Website Output

*(Add screenshots here by dragging images into GitHub README)*

---

## 🎯 Key Features

* 🔥 Fully automated deployment
* 🔄 Continuous Integration & Continuous Delivery
* 🐳 Containerized application
* ⚡ Fast and scalable deployment
* 📦 Easy to replicate setup

---

## 📚 Learning Outcomes

* Hands-on experience with CI/CD pipelines
* Understanding Jenkins automation
* Docker image creation & container deployment
* Real-time DevOps workflow implementation

---

## 👩‍💻 Author

**AmirthaDevi S**

---

## ⭐ Future Improvements

* Add Kubernetes deployment
* Enable HTTPS using SSL
* Deploy on cloud (AWS / Azure)
* Add monitoring (Prometheus + Grafana)

---

## 🙌 Support

If you like this project, feel free to ⭐ the repository and share your feedback!
