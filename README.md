# 👋 Hi there, I'm Orenjji!

### 🧪 QA Automation Engineer → DevOps

I'm a **Quality Assurance Engineer** who builds test automation and the pipelines that run it.
I'm growing toward **DevOps**: reliable CI/CD, containers, and secure, reproducible environments.

* 🔍 Manual, functional and regression testing
* 🎭 Playwright test automation in **Python (pytest)** and **Java (Cucumber BDD)**
* 🚀 CI/CD with **GitHub Actions**: linting, testing, and publishing container images
* 🐳 **Docker**: hardened, reproducible test images
* 🐧 Daily development on **Linux (Ubuntu on WSL2)**
* ☁️ Currently learning **AWS**
* ⚡ Fun fact: I love breaking things so they can be made better!

---

## 🚀 Featured project: Playwright + pytest automation framework (Python)

An end-to-end test framework for a real warehouse management web application, with a full CI/CD pipeline.

**Test framework**
* Page Object Model, reusable **flows**, and shared components
* pytest **fixtures** that create their own test data and **clean it up** afterwards
* Automatic **evidence capture** on failure: screenshots and Playwright **traces**
* Waits on real application signals (no fixed sleeps); locators independent of user accounts and test data

**CI/CD (GitHub Actions)**
* Pipeline: **lint → test → publish**, with job timeouts and concurrency control
* Tests run in **Docker**; the **exact image that passed** is published to **GitHub Container Registry**
* **GitHub Environments** for per-environment secrets; **least-privilege** token permissions per job
* Nightly scheduled runs, manual runs, and a pre-flight health check of the test environment

**Quality & security**
* **pre-commit** hooks shared locally and in CI: **Ruff**, **actionlint**, **hadolint**
* Docker image pinned by **digest**, running as a **non-root** user
* GitHub Actions pinned to **commit SHAs**; **Dependabot** keeps dependencies, actions and the base image current
* Dependencies declared in `requirements.in` and locked with **pip-tools**

---

## 🛠️ Skills & Technologies

**🧪 QA & Test Automation:** Manual, Regression & Functional Testing · Test Case Design · Bug Reporting ·
Playwright · Selenium · Cucumber / BDD · pytest · TestNG · Postman · Apache JMeter

**⚙️ DevOps & CI/CD:** GitHub Actions · Docker · Docker Compose · GitHub Container Registry ·
pre-commit · Dependabot · Linux / Ubuntu · WSL2 · Bash

**💻 Programming:** Python · Java · JavaScript · SQL / MySQL · HTML · CSS

**🔧 Tools:** Git · GitHub · Jira · TestRail · Maven · Ruff · pip-tools

---

## 🎭 Other automation projects

* **Playwright + Java + Cucumber BDD**: Java, Playwright, Cucumber, Gherkin, TestNG, Maven
* **Selenium + Java + Cucumber**: Selenium WebDriver, Cucumber, TestNG, Maven, Excel test data, Extent Reports

---

## 📚 Currently learning

* ☁️ **AWS**: IAM, S3, ECR, running containers (ECS)
* 🏗️ Next: **Terraform**, **Kubernetes**, monitoring, and DevSecOps scanning
