# Spring Boot Based Banking Web Application

A secure and modular Spring Boot-based banking application designed to demonstrate CI/CD automation, infrastructure provisioning, monitoring, and testing using modern DevOps tools.

---

## 👨‍💻 Client
**Star Agile**

---

## 🚀 Features

- Spring Boot RESTful banking APIs (e.g., account management, transactions)
- CI/CD pipeline with Jenkins, Docker, and GitHub
- Static code analysis with SonarQube
- Containerized deployment using Docker
- Infrastructure provisioning with Terraform and Ansible on AWS
- Monitoring with Prometheus and Grafana
- In-memory H2 database for quick setup and testing
- Automated testing with JUnit and TestNG

---

## 🔧 Tech Stack
--------------------------------------------------------------------------------
| Category         | Tools & Technologies                                       |
|------------------|----------------------------------------------------------- |
| **Backend**       | Java, Spring Boot, Maven, H2 Database                     |
| **CI/CD**         | Git, GitHub, Jenkins, Docker, SonarQube                   |
| **Testing**       | JUnit, TestNG                                             |
| **Infrastructure**| AWS, Terraform, Ansible                                   |
| **Monitoring**    | Prometheus, Grafana                                       |
| **IDE & OS**      | Eclipse, Linux                                            |
| **Scripting**     | Python (automation scripts)                               |
---------------------------------------------------------------------------------


## 📁 Project Structure
├── src/ # Java source code
├── terraform/ # Infrastructure as Code configs
├── Dockerfile # Docker build instructions
├── pom.xml # Maven dependencies
├── application.properties # Spring Boot config
├── Jenkinsfile (if used) # CI/CD pipeline script
├── README.md # Project documentation


---

## 🧪 Testing Strategy

- **JUnit** and **TestNG** for unit & integration tests
- Optional **Selenium** for UI automation (if implemented)
- Tests triggered automatically in CI/CD pipeline

---

## 🐳 Run with Docker

```bash
# Build Docker image
docker build -t springboot-banking-app .

# Run container
docker run -p 8080:8080 springboot-banking-app


#☁️ Infrastructure Deployment (Terraform + Ansible)
Configure AWS credentials.

Use Terraform to provision EC2 and security groups.

Use Ansible to install dependencies and deploy the app.



#📊 Monitoring
Prometheus scrapes application metrics.

Grafana dashboards visualize performance and health.

Alerts (optional) configured for resource limits or app errors.
