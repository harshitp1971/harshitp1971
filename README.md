# Hi, I'm Harshit Patel 👋

**Application Security Engineer · Vulnerability Researcher · DevSecOps**
I find and fix security flaws in web apps & APIs, before attackers do.

[![Website](https://img.shields.io/badge/Hire_me-parakhwork.com-6C63FF?style=for-the-badge)](https://www.parakhwork.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-harshit682-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/harshit682)
[![Medium](https://img.shields.io/badge/Medium-@harshitp1971-12100E?style=for-the-badge&logo=medium&logoColor=white)](https://medium.com/@harshitp1971)
[![Email](https://img.shields.io/badge/Email-harshitp1971@gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:harshitp1971@gmail.com)

---

## 🛡️ What I do

| Service | What you get |
|---|---|
| **Web & API Pentesting (VAPT)** | OWASP Top 10 / API Top 10 testing with reproducible PoCs and clear fix guidance |
| **Secure Code Review** | Manual + SAST-assisted review (Python/Django, JS) focused on real, exploitable issues |
| **Threat Modeling** | Find design-level risks before they become bugs |
| **DevSecOps** | Security checks in CI/CD: SAST, secrets scanning, dependency scanning |

📫 Open for freelance projects, reach me via [parakhwork.com](https://www.parakhwork.com) or email.

---

## 🔬 Research

### [Can LLMs Find Broken Tokens?](https://github.com/harshitp1971/jwt-llm-detection) `in progress`
Empirical study of **LLMs vs. SAST** for detecting usage-level **JWT vulnerabilities** in Python, flaws that dependency scanners miss because they live in *how* a library is used.

- 252-sample labeled dataset (119 vulnerable / 133 safe) + scoring harness
- SAST baselines struggle: **Bandit F1 0.28**, **Semgrep F1 0.40**, with **0.00 recall** on 6 semantic flaw classes (alg confusion, `kid` path traversal, missing `exp`/`aud`/`iss`, …)
- Motivates semantic, LLM-based vulnerability detection

---

## 🧰 Tools I've built

| Project | What it does |
|---|---|
| [**ai-assisted-burp-extension**](https://github.com/harshitp1971/ai-assisted-burp-extension) | Burp Suite extension that uses an LLM (Claude) to analyze proxied HTTP traffic in real time and surface findings in a dedicated tab |
| [**js_endpoint**](https://github.com/harshitp1971/js_endpoint) | Fast multi-threaded recon tool: finds JS endpoints, API paths, hard-coded secrets and tokens |
| [**ip_finder**](https://github.com/harshitp1971/ip_finder) | OSINT tool to find the real origin server IP behind a CDN/WAF |
| [**Book**](https://github.com/harshitp1971/Book) | Practical guide to web hacking vulnerabilities, tooling and methodology |
| [**EpochCyber**](https://harshitp1971.github.io) | Blogs, tools and resources for the security community |

---

## 🧠 Skills

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Django](https://img.shields.io/badge/Django-092E20?style=flat-square&logo=django&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Burp Suite](https://img.shields.io/badge/Burp_Suite-FF6633?style=flat-square&logo=burpsuite&logoColor=white)
![OWASP](https://img.shields.io/badge/OWASP-000000?style=flat-square&logo=owasp&logoColor=white)
![Semgrep](https://img.shields.io/badge/Semgrep-3DDC84?style=flat-square)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)

**Security:** Web/API pentesting · Secure code review · Threat modeling · SAST/DAST · Recon & OSINT · JWT / auth flaws · DevSecOps
**Certification:** Google Cybersecurity Professional Certificate

---

## 🌱 Currently

- 🤖 Exploring **AI / LLM security** and AI red-teaming
- 🔬 Extending the JWT-vs-LLM study
- ✍️ Writing practical AppSec write-ups on [Medium](https://medium.com/@harshitp1971)

---

<sub>“Breaking things to make them safer.”</sub>
