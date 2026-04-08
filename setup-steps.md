# Setup Steps (AWS EC2 + Docker)

## 1. Launch EC2 Instance
- Go to AWS Console
- Launch Ubuntu instance
- Allow ports: 22, 8080

---

## 2. Connect to EC2
```bash
ssh -i your-key.pem ubuntu@your-ec2-public-ip
```

---

## 3. Install Docker
```bash
sudo apt update
sudo apt install docker.io -y
sudo systemctl start docker
sudo systemctl enable docker
```

---

## 4. Install Docker Compose
```bash
sudo apt install docker-compose -y
```

---

## 5. Run the Application
```bash
docker run -d -p 8080:8080 ghcr.io/open-telemetry/opentelemetry-demo:latest
```

---

## 6. Access Application
Open in browser:
```
http://<EC2-PUBLIC-IP>:8080
```

---

## 7. Generate Load
- Use the built-in load generator
- Interact with UI (add to cart, checkout)

---

## 8. Access Observability Tools
- Grafana → /grafana
- Jaeger → /jaeger/ui
