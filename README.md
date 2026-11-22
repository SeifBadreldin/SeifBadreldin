<table>
<tr>
<td width="58%" valign="top">

# Seif Badreldin
**Network & Cybersecurity Engineer** · *AppSec · Secure Backends · Enterprise Networks*

Network & Cybersecurity Technology undergraduate at **SUTech – ElSewedy University of Technology** (**3.7 CGPA · Excellence**), focused on offensive web application testing, authentication-hardened backend systems, segmented network architecture, and AI-driven threat detection.

<br/>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-SeifBadreldin-10B981?style=flat-square&logo=linkedin&logoColor=0B1120)](https://www.linkedin.com/in/SeifBadreldin)
[![Email](https://img.shields.io/badge/Email-seifmohamed3535%40gmail.com-0F172A?style=flat-square&logo=gmail&logoColor=10B981)](mailto:seifmohamed3535@gmail.com)
[![WhatsApp](https://img.shields.io/badge/WhatsApp-%2B20_1025590726-0F172A?style=flat-square&logo=whatsapp&logoColor=10B981)](https://wa.me/201025590726)
![Location](https://img.shields.io/badge/Cairo%2C_Egypt-0F172A?style=flat-square&logo=googlemaps&logoColor=06B6D4)

</td>
<td width="42%" valign="top">

```json
{
  "operator": "Seif Badreldin",
  "degree": "B.Sc. Network & Cybersecurity",
  "university": "SUTech (2023 - 2027)",
  "standing": "3.7 CGPA | Excellence",
  "recent_role": "Security Tester @ BRMJA Tech",
  "languages": [
    "Arabic (Native)",
    "English (IELTS 6.5 · B2)"
  ],
  "availability": "Open to AppSec, SOC & Network roles"
}
```

</td>
</tr>
</table>

---

## Core Engineering Domains

<table>
<tr>
<td width="50%" valign="top">

### 🛡️ Offensive Security & AppSec
Identifying and exploiting **OWASP Top 10** vulnerabilities—including SQL Injection, reflected/stored XSS, IDOR, and Broken Access Control. Intercepting and manipulating HTTP/S traffic via **Burp Suite** to deliver severity-rated remediation reports.

`OWASP Top 10` · `Burp Suite` · `Kali Linux` · `Vulnerability Reporting`

</td>
<td width="50%" valign="top">

### 🔐 Backend Hardening & Cryptography
Engineering zero-trust API authentication flows featuring **JWT token blacklisting**, email-OTP **2FA**, **Google OAuth**, **RBAC**, brute-force lockout, **PBKDF2-SHA256** hashing, and **AES-256-GCM** authenticated encryption.

`Flask` · `FastAPI` · `JWT / 2FA / OAuth` · `AES-256-GCM` · `PBKDF2`

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🌐 Enterprise Networks & DevSecOps
Designing segmented multi-VLAN enterprise topologies with **OSPF**, **Extended ACLs**, hardened **DMZs**, and **SSH-only** management, alongside automated **Kubernetes** container vulnerability scanning and GitOps pipelines.

`Cisco Packet Tracer` · `VLANs / OSPF / ACLs` · `Scapy` · `Kubernetes` · `Trivy` · `ArgoCD`

</td>
<td width="50%" valign="top">

### 🤖 AI-Driven Fraud & Threat Defense
Building machine-learning and NLP pipelines for phishing URL analysis, `.eml` header forensics, scam call/text classification, and explainable candidate-role matching.

`Python` · `Sentence-BERT` · `XGBoost` · `Whisper` · `scikit-learn`

</td>
</tr>
</table>

---

## Flagship Systems

### 01 · [SANAD — AI Digital Fraud & Scam Defense Platform](https://github.com/SeifBadreldin/sanad) &nbsp;[![Live Demo](https://img.shields.io/badge/Live_Demo-↗-10B981?style=flat-square)](https://sanad-web-beryl.vercel.app)
> **Multi-engine threat detection API** built to counter Egyptian-Arabic social engineering and digital fraud across text, web, and voice channels.
- **Detection Architecture:** Orchestrates 5 specialized engines via `FastAPI`—analyzing scam SMS/messages, inspecting phishing URLs for typosquatting and look-alike domains, transcribing suspicious calls with `Whisper`, and screening voice deepfakes.
- **Hardening & Deployment:** Containerized with `Docker` and deployed across `Railway` and `Vercel` with strict CORS policies and rate limiting.
- **Stack:** `Python` · `FastAPI` · `OpenAI Whisper` · `Docker` · `Railway` · `Vercel`

### 02 · [FutureIntern — AI-Powered Internship Marketplace](https://github.com/SeifBadreldin/futureintern) &nbsp;![Capstone](https://img.shields.io/badge/Capstone_Project-8--Member_Team-0F172A?style=flat-square)
> **End-to-end backend and security architecture** powering a full-stack web (`React`) and mobile (`React Native`) talent-matching platform.
- **Security Controls:** Built a 10-blueprint `Flask` REST API fortified with `JWT` access/refresh token blacklisting, email-OTP `2FA`, Google `OAuth`, `RBAC`, account lockout, `PBKDF2-SHA256` password hashing, SQLi-safe ORM queries, and hardened HTTP security headers.
- **Recommendation Engine:** Engineered a hybrid `TF-IDF` + `Sentence-BERT` matching pipeline with explainable skill-gap insights, achieving **85%+ skill-alignment accuracy**.
- **Stack:** `Python` · `Flask` · `PostgreSQL` · `React` · `React Native` · `Sentence-BERT` · `Railway`

---

## Security & Network Engineering Tools

<table>
<tr>
<td width="33.3%" valign="top">

#### 🔒 [Secure Password Manager](https://github.com/SeifBadreldin/PasswordManager)
Zero-knowledge desktop vault where master passwords are never stored. Derives keys via **PBKDF2**, seals credentials with **AES-256-GCM**, checks breaches via **HIBP k-anonymity**, detects password reuse, and auto-clears the clipboard.

`Python` · `PyQt5` · `AES-256-GCM` · `HIBP`

</td>
<td width="33.3%" valign="top">

#### 🐳 [Container Sentry](https://github.com/SeifBadreldin/container-sentry)
Automated Kubernetes container vulnerability scanner. Executes **Trivy** CVE scans as ephemeral K8s Jobs, stores findings in **PostgreSQL** via a **FastAPI** service, visualizes risk on a dashboard, and deploys via **ArgoCD** GitOps.

`Kubernetes` · `Trivy` · `FastAPI` · `ArgoCD`

</td>
<td width="33.3%" valign="top">

#### 📡 [Packet Sniffer](https://github.com/SeifBadreldin/Packet-Sniffer)
Real-time network traffic analyzer built with **Scapy** and a **Tkinter** desktop GUI. Captures and decodes live Ethernet, IPv4, TCP, and UDP headers with protocol filtering and `.pcap` export for **Wireshark** inspection.

`Python` · `Scapy` · `Tkinter` · `Wireshark`

</td>
</tr>
</table>

<details>
<summary><b>📂 Expand Academic & Security Engineering Labs (3 Systems)</b></summary>
<br/>

- **SafeHire — AI Job Fraud & Phishing Detection System** (`Python`, `FastAPI`, `XGBoost`, `scikit-learn`)
  Trained an `XGBoost` classifier on **18,000+ job postings** using TF-IDF features, SMOTE class balancing, and 5-fold cross-validation, paired with an `.eml` forensics parser (detecting spoofed headers and malicious attachments) and heuristic URL risk scoring.
- **Secure University Campus Network Design** (`Cisco Packet Tracer`, `VLANs`, `OSPF`, `Extended ACLs`, `SSH`, `DMZ`)
  Designed a multi-floor campus topology (300+ lab PCs, IP phones, cameras, WAPs) segmented into **8 VLANs** with router-on-a-stick inter-VLAN routing, per-VLAN DHCP pools, extended ACL isolation, a hardened DMZ (DNS, Web, Mail, File, DB servers), and SSH-only device management.
- **Phishing Defense & Awareness Platform** (`Python`, `Streamlit`, `Email Parsing`, `LLM Integration`)
  Built a bilingual (Arabic/English) phishing-simulation trainer that generates realistic test campaigns, tracks click and report metrics, inspects suspicious emails, and exports PDF awareness reports.

</details>

---

## Experience & Education Timeline

- **`Jan 2026 – Feb 2026`** · **Security Tester Intern** — *BRMJA Tech Company* `(Cairo, Egypt)`
  Conducted OWASP Top 10 security testing across web applications (SQLi, XSS, IDOR), intercepted and manipulated HTTP/S traffic in `Burp Suite` (Proxy, Repeater), and documented severity-classified findings with actionable remediation steps.
- **`Aug 2024 – Sep 2024`** · **Data Network Engineering Intern** — *Orange Egypt — Technology Dept.* `(Cairo, Egypt)`
  Configured enterprise routers and switches in `Cisco Packet Tracer`, implementing IP subnetting, `VLAN` segmentation, and `OSPF` routing to validate and troubleshoot simulated network topologies.
- **`Nov 2022 – Jan 2023`** · **Oracle APEX Developer** — *Ain Shams University — Faculty of Dentistry* `(Cairo, Egypt)`
  Built a database-driven patient management system for the Radiology Department using `Oracle APEX`, `SQL`, and `PL/SQL`, streamlining dental status tracking and automated physician report generation.
- **`Jun 2026 – Sep 2026`** · **Summer Work & Travel Exchange Program (J-1)** — *Big Splash & Wendy's* `(New York, USA)`
  Completed an international cultural exchange program in New York as a Lifeguard and Crew Member, building operational discipline, fast-paced teamwork, and cross-cultural communication.
- **`Oct 2023 – Expected 2027`** · **Bachelor of Network & Cybersecurity Technology** — *SUTech, ElSewedy University of Technology* `(Cairo, Egypt)`
  **CGPA: 3.7 · Academic Status: Excellence**

---

## Tech Stack & Verified Credentials

<p>
  <img src="https://skillicons.dev/icons?i=py,cpp,java,php,js,ts,html,css,flask,fastapi,react,postgres,mysql,kali,linux,docker,kubernetes,git,github,vercel,sklearn&theme=dark" alt="Core Tech Stack" />
</p>

<p>
  <img src="https://img.shields.io/badge/Burp_Suite-FF6633?style=flat-square&logo=burpsuite&logoColor=white" alt="Burp Suite" />
  <img src="https://img.shields.io/badge/OWASP_Top_10-0B1120?style=flat-square&logo=owasp&logoColor=10B981" alt="OWASP Top 10" />
  <img src="https://img.shields.io/badge/Cisco_Packet_Tracer-1BA0D7?style=flat-square&logo=cisco&logoColor=white" alt="Cisco Packet Tracer" />
  <img src="https://img.shields.io/badge/Trivy-1904DA?style=flat-square&logo=aqua&logoColor=white" alt="Trivy" />
  <img src="https://img.shields.io/badge/ArgoCD-EF7B4D?style=flat-square&logo=argo&logoColor=white" alt="ArgoCD" />
  <img src="https://img.shields.io/badge/Oracle_APEX-F80000?style=flat-square&logo=oracle&logoColor=white" alt="Oracle APEX" />
  <img src="https://img.shields.io/badge/NIST_SP_800--61-0F172A?style=flat-square&logoColor=10B981" alt="NIST SP 800-61" />
</p>

**Verified Certifications:**
- ![Huawei](https://img.shields.io/badge/Huawei_ICT_Academy-5G_Mobile_Network_Deployment_&_Industry_Applications_(May_2026)-CF0A2C?style=flat-square&logo=huawei&logoColor=white)
- ![Huawei](https://img.shields.io/badge/Huawei_ICT_Academy-5G_Basics:_What_It's_All_About_(May_2026)-CF0A2C?style=flat-square&logo=huawei&logoColor=white)
- ![Cisco](https://img.shields.io/badge/Cisco_Networking_Academy-Network_Addressing_&_Basic_Troubleshooting_(May_2026)-1BA0D7?style=flat-square&logo=cisco&logoColor=white)
- ![IELTS](https://img.shields.io/badge/IELTS_Academic-Overall_Band_6.5_·_CEFR_B2_(Mar_2025)-10B981?style=flat-square&logoColor=0B1120)

---

## GitHub Activity & Metrics

<div align="center">
  <img width="100%" src="https://github-readme-activity-graph.vercel.app/graph?username=SeifBadreldin&bg_color=0B1120&color=10B981&line=10B981&point=06B6D4&area=true&area_color=10B981&hide_border=true&custom_title=Contribution%20Activity" alt="Seif Badreldin Contribution Graph" />
  <br/>
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=SeifBadreldin&show_icons=true&hide_border=true&bg_color=0B1120&title_color=10B981&icon_color=06B6D4&text_color=CBD5E1" alt="Seif Badreldin GitHub Stats" />
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=SeifBadreldin&layout=compact&hide_border=true&bg_color=0B1120&title_color=10B981&text_color=CBD5E1" alt="Top Languages" />
</div>

<p align="center"><sub><code>Seif Badreldin</code> · Offensive Mindset · Defensive Engineering</sub></p>
