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

## 🔹 4. Important DevOps Tools
- **Version Control** → Git, GitHub, GitLab, Bitbucket  
- **CI/CD** → Jenkins, GitHub Actions, GitLab CI, CircleCI  
- **Containers** → Docker, Podman  
- **Orchestration** → Kubernetes, OpenShift  
- **Infrastructure as Code (IaC)** → Terraform, Ansible, Puppet, Chef  
- **Monitoring & Logging** → Prometheus, Grafana, ELK Stack, Splunk  
- **Cloud Platforms** → AWS, Azure, GCP  

---

## 🔹 5. Core Concepts in DevOps

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
- Manages multiple containers.
- Handles scaling, self-healing, load balancing.

### ✅ Infrastructure as Code (IaC)
- Manage servers using code instead of manual setup.
- Example: Terraform (cloud infra), Ansible (server config).

### ✅ Monitoring & Logging
- Track performance, errors, system health.
- Tools: Prometheus, Grafana, ELK Stack.

---

## 🔹 6. Web Server in DevOps (Nginx Basics)
- Nginx → Web server, reverse proxy, load balancer.
```bas
sudo systemctl start nginx
sudo systemctl status nginx
nginx -t   # test config
```
---

##🔹 7. Example DevOps Workflow
- Developer pushes code → GitHub.
- Jenkins pipeline runs build & tests.
- Docker image is created.
- Image deployed on Kubernetes cluster.
- Nginx routes traffic.
- Prometheus + Grafana monitor system.

---

##🔹 8. Benefits of DevOps
- 🚀 Faster delivery
- 🤝 Improved collaboration
- ✅ Higher quality software
- 🐞 Early bug detection
- 📈 Better scalability & reliability
