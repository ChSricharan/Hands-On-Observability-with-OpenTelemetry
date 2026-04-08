<img width="1536" height="1024" alt="Copilot_20260407_220241" src="https://github.com/user-attachments/assets/3461fe7e-57f8-40d8-8ea5-bbdd01fadae7" /><img width="1536" height="1024" alt="Copilot_20260407_220241" src="https://github.com/user-attachments/assets/6c7b8fb8-4b89-44ec-9f17-9f3cac75593d" /><img width="1536" height="1024" alt="Copilot_20260407_220241" src="https://github.com/user-attachments/assets/f40e8e8b-a976-4754-ab8f-acc39cc1aa2c" /># Hands-On-Observability-with-OpenTelemetry
# End-to-End Observability Project (Beginner Friendly)

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

### Jaeger Traces
![Jaeger](screenshots/jaeger-traces.png)

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
