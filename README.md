# Hands-On-Observability-with-OpenTelemetry: End-to-End Observability Project (Beginner Friendly)

## 📌 Overview
This is a beginner-friendly end-to-end observability project using the OpenTelemetry Demo (Astronomy Shop).

The application is deployed on an AWS EC2 instance and runs inside Docker containers. This project demonstrates how logs, metrics, and traces are collected and visualized using modern observability tools.

---

## 🚀 Tech Stack
- AWS EC2
- Docker & Docker Compose
- OpenTelemetry
- Grafana (Visualization)
- Jaeger (Tracing)

---

## 🏗️ Architecture
User → EC2 Instance → Docker Containers → OpenTelemetry → Prometheus + Jaeger → Grafana
<img width="1536" height="1024" alt="Copilot_20260407_220241" src="https://github.com/user-attachments/assets/3461fe7e-57f8-40d8-8ea5-bbdd01fadae7" />
---

## ⚙️ Features
- Multi-microservice application (cart, checkout, payment, etc.)
- Real-time metrics monitoring
- Distributed tracing across services
- Pre-configured dashboards in Grafana
- Simulated traffic using load generator

---

## 📸 Screenshots

### Grafana Dashboard
![Grafana](screenshots/grafana-dashboard.png)
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/0e33d916-4aab-4a98-874d-16fdf2dedd4e" />

### Jaeger Traces
![Jaeger](screenshots/jaeger-traces.png)
<img width="1919" height="1006" alt="image (1)" src="https://github.com/user-attachments/assets/56de70dd-e118-4cfa-ae05-a13cd143e80d" />


---

## 🛠️ Setup Instructions
Follow detailed steps in 👉 setup-steps.md

---

## 📚 What I Learned
- Basics of observability (logs, metrics, traces)
- How OpenTelemetry works in real systems
- Deploying applications on AWS EC2
- Running microservices using Docker
- Monitoring using Grafana and Prometheus
- Debugging using Jaeger traces

---

## 💡 Future Improvements
- Deploy using Kubernetes (EKS)
- Add alerting in Grafana
- Integrate with tools like Datadog or Splunk

---

## 🙌 Author
Sricharan
