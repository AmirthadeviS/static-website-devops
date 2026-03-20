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
👉(http://localhost:8082/)

---

## 📸 Screenshots

## 📁 GitHub Repository
![GitHub Repo](https://github.com/user-attachments/assets/667d0e2e-e3cb-4505-9f3b-cbee623c8025)

## 🚀 Jenkins Pipeline (Build Success)
![Jenkins Pipeline](https://github.com/user-attachments/assets/bff4bb55-475f-4fec-ac63-11d5b4bf19ce)

✔️ Pipeline executed successfully using Jenkins CI/CD

---

## 📜 Console Output Logs

### 🔹 Build Start
![Build Start](https://github.com/user-attachments/assets/ad1c0fdb-4b39-4ca7-9568-8fbc1c2a74d5)

### 🔹 Docker Build
![Docker Build](https://github.com/user-attachments/assets/d770c363-f567-4043-b000-08e428ce87f6)

### 🔹 Build Success
![Success](https://github.com/user-attachments/assets/d484c876-3bf9-4665-8b6e-79af32c98e4a)

✔️ Logs confirm successful execution of all pipeline stages

---

## 🐳 Docker Running Container
![Docker Container](https://github.com/user-attachments/assets/caec93c8-83ec-4c39-a3a9-03c864440a2e)

✔️ Container successfully running after deployment  

This confirms that the Docker container is up and running successfully after the CI/CD pipeline execution.

---

## 🌐 Final Website Output
![Website Output](https://github.com/user-attachments/assets/4e71cc8a-725a-4c6c-b4e5-1167f36d146a)

✔️ Website successfully deployed and accessible  

This confirms that the application is running successfully after the complete CI/CD pipeline execution.


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
