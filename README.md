<!--
  Fernando Silva | GitHub profile
  Positioning: Python Backend · Application Security · Secure Software Development
  Documentation language: English
-->

<div align="center">

<a href="https://github.com/silvatechf">
  <img width="100%" src="https://capsule-render.vercel.app/api?type=waving&height=185&color=0:080B18,45:111B37,100:174C70&text=FERNANDO%20SILVA&fontColor=F3F7FF&fontSize=44&fontAlignY=38&desc=PYTHON%20BACKEND%20%E2%80%A2%20APPLICATION%20SECURITY&descAlignY=60&descSize=14&animation=fadeIn" alt="Fernando Silva — Python Backend and Application Security" />
</a>

<br/>

<a href="https://www.linkedin.com/in/fernando-silva-83b155a4/">
  <img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="Connect on LinkedIn" />
</a>
<a href="https://github.com/silvatechf?tab=repositories">
  <img src="https://img.shields.io/badge/GitHub-Explore%20projects-161B22?style=for-the-badge&logo=github&logoColor=white" alt="Explore repositories" />
</a>
<a href="https://github.com/silvatechf/silvatechf/blob/main/PORTFOLIO_MAP.md">
  <img src="https://img.shields.io/badge/Portfolio-Project%20map-7C5CFC?style=for-the-badge&logo=readthedocs&logoColor=white" alt="Open portfolio map" />
</a>
<a href="https://silvatechf-portifolio.vercel.app/">
  <img src="https://img.shields.io/badge/Portfolio-Live%20site-0A7F5A?style=for-the-badge&logo=vercel&logoColor=white" alt="Open the live portfolio" />
</a>

<br/><br/>

### Building useful software. Making security part of the design.

**Python Backend Developer · Application Security (AppSec)**

Barcelona, Spain · Open to junior backend and AppSec opportunities

<br/>

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=500&size=16&duration=3000&pause=900&color=62E6FF&center=true&vCenter=true&width=620&lines=Python+Backend+%7C+Application+Security;Designing+clear%2C+testable+APIs;Building+security+into+the+development+workflow" alt="Python backend, application security, and secure development" />

</div>

---

## About

I’m a Python developer based in Barcelona, focused on **backend engineering and application security**. I build practical projects to strengthen the way applications are designed, implemented, tested, and operated.

My interests meet at a concrete engineering question: how do we make software behavior explicit and security controls verifiable? That includes API design, identity and authorization, input validation, vulnerability handling, auditability, automated testing, and security checks in CI.

I use personal projects, collaborative contributions, and security labs to develop these skills. I document implementation choices, test evidence, assumptions, and limitations rather than presenting prototypes as production systems.

**Current target:** Junior Python Backend Developer roles, especially in teams that value secure software development and offer room to grow toward AppSec and DevSecOps.

- Portfolio: [silvatechf-portifolio.vercel.app](https://silvatechf-portifolio.vercel.app/)
- Location: Barcelona, Spain
- Languages: Spanish (C1–C2) · English (B1–B2)

## Education & training

- **IFCD0112 — Object-Oriented Programming and Relational Databases:** training completed in November 2026; official professional certificate requested from the Servei Públic d'Ocupació de Catalunya (SOC), issuance pending.
- **IFCD072PO — Cybersecurity and Ethical Hacking:** 300-hour mixed-format training completed in July 2026; certificate of achievement issued by the training provider in August 2026. Topics included network architecture, Linux and Windows infrastructure, information gathering, scanning, vulnerability analysis, Wi-Fi auditing, exploits, and malware fundamentals.

These qualifications complement my practical backend and application-security projects; they are presented as training, not as professional experience or specialist certifications.

## Core focus

| Python Backend | Application Security | Engineering & Delivery |
|:--|:--|:--|
| Python · FastAPI · Django | Secure coding · Authorization | pytest · Automated testing |
| REST APIs · SQLAlchemy | Input validation · Vulnerability analysis | Git · GitHub Actions |
| PostgreSQL · SQLite | Auditability · Security controls | Docker · Linux · CI |

## Selected projects

These projects provide the clearest evidence of my current direction. Each repository contains its own implementation details, setup instructions, tests, and scope limitations.

<table>
<tr>
<td width="50%" valign="top">

### [DeviceTrust](https://github.com/silvatechf/DeviceTrust)

<img src="https://img.shields.io/badge/Python-FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" alt="Python and FastAPI" />
<img src="https://img.shields.io/badge/Product%20Security-SBOM%20%7C%20Audit-7C5CFC?style=flat-square" alt="Product security, SBOM and audit evidence" />

An early-stage Product Security prototype for managing product context, CycloneDX SBOM imports, component findings, vulnerability triage, and traceable assessment evidence.

**Engineering focus**
- Product-scoped SBOM persistence and component occurrences.
- SBOM comparison and append-only assessment history.
- Justified triage and hash-linked audit history.
- Transaction boundaries, concurrent writes, and rollback testing across SQLite and PostgreSQL.

<sub>Technical prototype — not a CRA compliance tool, conformity assessment, or production security service.</sub>

[Repository](https://github.com/silvatechf/DeviceTrust) · [CI](https://github.com/silvatechf/DeviceTrust/actions/workflows/ci.yml) · [Architecture](https://github.com/silvatechf/DeviceTrust/blob/main/docs/architecture.md)

</td>
<td width="50%" valign="top">

### [Authorization Gateway](https://github.com/silvatechf/authorization-gateway)

<img src="https://img.shields.io/badge/Python-FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" alt="Python and FastAPI" />
<img src="https://img.shields.io/badge/AppSec-Authorization%20policies-1D9BF0?style=flat-square" alt="Application security and authorization policies" />

A backend portfolio project exploring centralized authorization for APIs, with explicit policies and security-focused verification.

**Engineering focus**
- JWT/JWKS verification and authorization boundaries.
- Roles, scopes, ownership, and tenant isolation.
- Fail-closed behavior and denial-path testing.
- Security architecture documented as an implementation exercise.

<sub>Portfolio project — not a production-ready identity or authorization platform.</sub>

[Repository](https://github.com/silvatechf/authorization-gateway)

</td>
</tr>
<tr>
<td width="50%" valign="top">

### [AppSec Scanner](https://github.com/silvatechf/AppSec-Scanner)

<img src="https://img.shields.io/badge/Python-AST%20analysis-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python AST analysis" />
<img src="https://img.shields.io/badge/Security-Static%20analysis-7C5CFC?style=flat-square" alt="Static security analysis" />

A Python static-analysis project using AST-based rules to explore vulnerability detection, controlled remediation decisions, structured audit events, and CI security gates.

**Engineering focus:** bounded detection logic, explicit remediation criteria, observability, and repeatable checks.

<sub>Learning and portfolio project — not a replacement for mature SAST tooling or expert security review.</sub>

[Repository](https://github.com/silvatechf/AppSec-Scanner)

</td>
<td width="50%" valign="top">

### [DuckyArenas — Shop & Bank contribution](https://github.com/Martret92/duckyarenas-team5)

<img src="https://img.shields.io/badge/Python-Django-092E20?style=flat-square&logo=django&logoColor=white" alt="Python and Django" />
<img src="https://img.shields.io/badge/Backend-Transactions%20%7C%20Testing-1D9BF0?style=flat-square" alt="Backend transactions and testing" />

Individual backend contribution to an academic team project, focused on shop/catalog workflows, wallet transactions, purchase coordination, idempotency, and HTTP integration.

**Evidence:** [PR #122](https://github.com/Martret92/duckyarenas-team5/pull/122) · [#127](https://github.com/Martret92/duckyarenas-team5/pull/127) · [#129](https://github.com/Martret92/duckyarenas-team5/pull/129) · [#130](https://github.com/Martret92/duckyarenas-team5/pull/130) · [#132](https://github.com/Martret92/duckyarenas-team5/pull/132)

<sub>Academic team contribution; not ownership of the complete project.</sub>

</td>
</tr>
</table>

[**Explore the portfolio map →**](PORTFOLIO_MAP.md) · [Browse all repositories →](https://github.com/silvatechf?tab=repositories)

## Security labs

Smaller, focused exercises that complement the backend portfolio. They are learning environments, not commercial security products.

| Repository | Focus |
|---|---|
| [Triage Pipeline](https://github.com/silvatechf/triage-pipeline) | Authentication telemetry and heuristic triage |
| [Async EASM](https://github.com/silvatechf/Async-EASM) | Asynchronous attack-surface discovery for authorized targets |
| [Spec CTI](https://github.com/silvatechf/spec-cti) | Threat intelligence and security-analysis workflows |
| [SSH Monitoring Lab](https://github.com/silvatechf/ssh-monitoring-lab) | SSH security monitoring and event analysis |
| [Network Security Analytics](https://github.com/silvatechf/network-security-analytics) | Network-security data analysis |
| [AWS Security Foundation](https://github.com/silvatechf/aws-security-foundation) | Cloud-security fundamentals and configuration |

I assess only systems I own or am explicitly authorized to test. Each lab should be evaluated according to its own README, implementation, and evidence.

## Additional work

Projects outside the primary backend/AppSec focus:

- [MEI em Dia](https://github.com/silvatechf/mei-app) — React/Vite PWA for guided information and local task organization.
- [AI Job Agent](https://github.com/silvatechf/ai-job-agent) — Java Spring Boot and React application for CV/job-description analysis.
- [SmartSpend](https://github.com/silvatechf/SmartSpend-Java-React-Python-Fullstack) — multi-technology finance application.
- [Wildfire Observer](https://github.com/silvatechf/wildfire-observer) — Python-based geospatial and wildfire-analysis project.

For the broader archive of coursework and experiments, see the [complete repository list](https://github.com/silvatechf?tab=repositories).

## Tools and technologies

<div align="center">

<img src="https://skillicons.dev/icons?i=python,fastapi,django,pytest,postgres,sqlite,docker,linux,git,githubactions&perline=5&theme=dark" alt="Python, FastAPI, Django, pytest, PostgreSQL, SQLite, Docker, Linux, Git, and GitHub Actions" />

<br/><br/>

<img src="https://img.shields.io/badge/Backend-REST%20APIs%20%7C%20SQL-14213D?style=flat-square" alt="Backend: REST APIs and SQL" />
<img src="https://img.shields.io/badge/AppSec-Authorization%20%7C%20Secure%20coding-302B63?style=flat-square" alt="AppSec: authorization and secure coding" />
<img src="https://img.shields.io/badge/Delivery-Tests%20%7C%20CI%20%7C%20Static%20checks-0F766E?style=flat-square" alt="Delivery: tests, CI, and static checks" />

</div>

Technologies shown are used across projects and exercises; depth varies by repository. This is a visual index, **not a claim of professional production experience with every tool**.

## Engineering principles

- **Security by design:** define trust boundaries, validate inputs, and make authorization explicit.
- **Fail safely:** test denied access, invalid states, and failure paths — not only successful requests.
- **Evidence over claims:** connect statements to code, tests, CI results, and documented limitations.
- **Maintainability:** prefer modular, testable solutions over unnecessary complexity.
- **Continuous improvement:** strengthen automated quality and security checks as projects mature.

---

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=rect&height=2&color=0:62E6FF,50:7C5CFC,100:62E6FF&section=footer" width="100%" alt="" />

### Let’s build software that earns trust.

For opportunities, collaboration, or a technical conversation:

<a href="https://www.linkedin.com/in/fernando-silva-83b155a4/">
  <img src="https://img.shields.io/badge/LinkedIn-Fernando%20Silva-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="Fernando Silva on LinkedIn" />
</a>

<br/><br/>

<sub>Python Backend · Application Security · Barcelona, Spain</sub>

</div>
