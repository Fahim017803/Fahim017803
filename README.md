# Hi, I'm Fahim 👋

**DevOps Engineer in training** | Information Systems student at Sydney Met College, Sydney 🇦🇺 | building and breaking real infrastructure

I learn by deploying things that actually run — live EC2 servers, CI/CD pipelines that ship to production, and Kubernetes clusters I've had to debug at 2am. Everything below is real, running, or documented as I built it.

---

## 🚀 What I'm building right now

**[devops-kb](https://github.com/Fahim017803/devops-kb)** — a Flask + MySQL + Docker knowledge base for DevOps concepts, deployed live on AWS EC2.
- Full CI/CD pipeline: GitHub Actions → Docker Hub → self-hosted EC2 runner
- nginx reverse proxy, admin panel for content management, search functionality
- Currently writing the technical content myself (AWS cost management, Linux fundamentals)

**[mdfahim.dev](https://github.com/Fahim017803/mdfahim.dev)** — my portfolio site with a production-grade DevSecOps pipeline.
- Parallel security scanning: Gitleaks, Trivy, OWASP ZAP, Hadolint, Lighthouse CI
- Staged deployments with manual production approval gates
- Two self-hosted EC2 runners (staging + production), SSL via Let's Encrypt

**[Ai-banking-app-with-Kubernates](https://github.com/Fahim017803/Ai-banking-app-with-Kubernates)** — a full Kubernetes deployment of a multi-service banking app, run on a KinD cluster on EC2.
- Debugged real cluster issues: namespace mismatches, a base64 newline bug in secrets, ImagePullBackOff, port conflicts
- Got both the MySQL and application pods to a stable Running state from scratch

**NexaKnow** — capstone project, an AI-powered company knowledge assistant for SMEs (Flask, Claude API, SQLite, Bootstrap, Chart.js). I'm the DevOps Lead — handling CI/CD, Docker, and AWS deployment for the team.

---

## 🛠 Core stack

**Systems & DevOps**
Linux · Bash · Docker · Docker Compose · Kubernetes (KinD) · GitHub Actions · self-hosted runners · nginx · AWS EC2

**Security & quality gates**
Gitleaks · Trivy · OWASP ZAP · Hadolint · Lighthouse CI

**Languages**
Python (Flask) · C++ (competitive programming) · SQL · JavaScript (frontend basics)

**Learning now**
Terraform · Prometheus/Grafana

---

## ⚙️ A pipeline I actually built

```
git push
   │
   ▼
GitHub Actions ── lint, build, parallel security scans
   │
   ▼
Docker Hub ── tagged image pushed
   │
   ▼
Self-hosted EC2 runner ── pulls image
   │
   ▼
docker compose up -d ── staging, then manual approval, then production
```

This isn't a tutorial pipeline — it's deployed and serving real traffic, and I've debugged real failures in it: runner label mismatches, SSL rate limiting, port mapping bugs, and a base64 newline issue that took a full afternoon to track down in a Kubernetes secret.

---

## 🧠 Why competitive programming

I'm rated **Pupil (1240)** on [Codeforces](https://codeforces.com/profile/Fahim017803), working toward Specialist — not as a separate hobby, but because the same skills show up in infrastructure work: reasoning under constraints, catching edge cases before they become production incidents, and not guessing when I can verify. Solving 6–9 problems a week in C++, mostly Div. 2 A–D range.

---

## 📂 Selected repositories

| Repo | What it is |
|---|---|
| [devops-kb](https://github.com/Fahim017803/devops-kb) | Flask/MySQL/Docker knowledge base, live on EC2 |
| [mdfahim.dev](https://github.com/Fahim017803/mdfahim.dev) | Portfolio site with full DevSecOps CI/CD pipeline |
| [Ai-banking-app-with-Kubernates](https://github.com/Fahim017803/Ai-banking-app-with-Kubernates) | Kubernetes (KinD) deployment of a multi-service banking app |
| [Full-CI-CD--potfolio](https://github.com/Fahim017803/Full-CI-CD--potfolio) | End-to-end Flask CI/CD: lint → build → Docker Hub → EC2 |
| [Complete_90_days](https://github.com/Fahim017803/Complete_90_days) | My structured 90-day DevOps execution plan |

---

## 🎯 Where I'm headed

Final months of an Information Systems degree, aiming for a junior DevOps role. Closing the gaps I know I have — Infrastructure as Code (Terraform) and observability (Prometheus/Grafana) — before I get there, rather than after.

---

## 📫 Reach me

**LinkedIn:** [linkedin.com/in/mainul-islam-fahim-a7b7ab223](https://linkedin.com/in/mainul-islam-fahim-a7b7ab223)
**Email:** mainulislamfahim017803@gmail.com
**Codeforces:** [Fahim017803](https://codeforces.com/profile/Fahim017803)
