# DevOps
# 🚀 DevOps (Basics)
---
## 🔹 1. What is DevOps?
- **Definition** → DevOps is a culture & set of practices that combine **Development (Dev)** and **Operations (Ops)**.  
- **Goal** → Deliver software **faster, more reliable, and continuously**.  
- **Focus** → Collaboration, automation, monitoring, and feedback.  

---

## 🔹 2. Key Principles of DevOps
1. **Collaboration** → Dev + Ops teams work together.  
2. **Automation** → Automate repetitive tasks.  
3. **Continuous Integration & Continuous Deployment (CI/CD)**.  
4. **Monitoring & Feedback** → Detect issues quickly.  
5. **Scalability & Security** → System grows safely.  

---

## 🔹 3. DevOps Lifecycle
1. **Plan** → Collect requirements (Jira, Trello).  
2. **Code** → Write & manage code (Git, GitHub).  
3. **Build** → Compile/package code (Maven, Jenkins).  
4. **Test** → Automated testing (Selenium, JUnit, pytest).  
5. **Release** → Prepare version for users.  
6. **Deploy** → Push to production (Docker, Kubernetes).  
7. **Operate** → Manage servers & infra (Ansible, Terraform).  
8. **Monitor** → Track performance (Prometheus, Grafana).  

---
## 🔹 4. Example DevOps Workflow
- Developer pushes code → GitHub.
- Jenkins pipeline runs build & tests.
- Docker image is created.
- Image deployed on Kubernetes cluster.
- Nginx routes traffic.
- Prometheus + Grafana monitor system.

---

## 🔹 5. Benefits of DevOps
- 🚀 Faster delivery
- 🤝 Improved collaboration
- ✅ Higher quality software
- 🐞 Early bug detection
- 📈 Better scalability & reliability

---
## 🔹 6. Important DevOps Tools
- **Version Control** → Git, GitHub, GitLab, Bitbucket  
- **CI/CD** → Jenkins, GitHub Actions, GitLab CI, CircleCI  
- **Containers** → Docker, Podman  
- **Orchestration** → Kubernetes, OpenShift  
- **Infrastructure as Code (IaC)** → Terraform, Ansible, Puppet, Chef  
- **Monitoring & Logging** → Prometheus, Grafana, ELK Stack, Splunk  
- **Cloud Platforms** → AWS, Azure, GCP  

---
---
## 🔹 7. Core Concepts in DevOps

### ✅ Version Control (Git)  
- Tracks code changes.  
- Allows collaboration.  
```bash
git init
git add .
git commit -m "message"
git push origin main
```
---
### ✅ CI/CD (Continuous Integration / Continuous Deployment)
- **CI** → Merge code frequently + test automatically.  
- **CD** → Deploy new versions automatically.  
---

### ✅ Containers (Docker)
- Packages app + dependencies in one unit.  
- Runs anywhere (portable).  

```bash
docker build -t myapp .
docker run -p 8080:8080 myapp
docker ps
```
### ✅ Orchestration (Kubernetes)
- **Kubernetes (K8s)** is an **open-source container orchestration platform**. 
- Manages multiple containers.
- Handles scaling, self-healing, load balancing.

### ✅ Infrastructure as Code (IaC)
- Manage servers using code instead of manual setup.
- Example: Terraform (cloud infra), Ansible (server config).

### ✅ Monitoring & Logging
- Track performance, errors, system health.
- Tools: Prometheus, Grafana, ELK Stack.

---
---
## 🔹 8. Web Server in DevOps (Nginx Basics)
- A **web server** is software that **serves web content (HTML, CSS, JS, APIs, etc.)** to users over the internet.  
- It listens to **HTTP/HTTPS requests** and sends back responses.  

---

### 🔹 Role of Web Servers in DevOps
1. **Serve static content** → HTML, CSS, JS, images.  
2. **Reverse Proxy** → Forward requests to backend apps (Node.js, Python, Java).  
3. **Load Balancer** → Distribute traffic across multiple servers.  
4. **Caching** → Improve speed by storing frequently accessed content.  
5. **Security (HTTPS)** → Handle SSL/TLS certificates.  
6. **High Availability** → Ensure websites and APIs are always accessible.  

---

### 🔹 Popular Web Servers in DevOps
- **Nginx** → Lightweight, fast, reverse proxy + load balancer.  
- **Apache HTTP Server** → Flexible, widely used, modular.  
- **Caddy** → Easy to configure, automatic HTTPS.  
- **Lighttpd** → Lightweight alternative for small apps.  

---

##  🌐 Nginx Basics (Most Common in DevOps)
- Nginx → Web server, reverse proxy, load balancer.
### ✅ Commands
```bash
sudo systemctl start nginx     # Start server
sudo systemctl stop nginx      # Stop server
sudo systemctl restart nginx   # Restart server
sudo systemctl status nginx    # Check status
nginx -t                       # Test configuration
```
### ✅ Why Nginx is Popular in DevOps ?
- Handles thousands of concurrent requests efficiently.
- Uses event-driven architecture (faster than Apache for high traffic).
- Works great as a reverse proxy + load balancer in CI/CD pipelines.
- Commonly used in Docker & Kubernetes deployments.



