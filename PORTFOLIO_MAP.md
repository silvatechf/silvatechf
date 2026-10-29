# Fernando Silva — Portfolio Map

**Python Backend · Application Security · Secure Software Development**

I build projects to understand software from both sides: how to make useful applications work, and how to make their security boundaries clearer, testable, and easier to reason about.

This map is the wider view of my work in progress. It brings together backend projects, application-security experiments, defensive labs, product ideas, and coursework. The goal is not to make every repository look production-ready; it is to make the purpose of each project easy to understand and to give reviewers a clear path to the code and evidence.

## Start here

If you are reviewing my work for a Python Backend or AppSec opportunity, I recommend starting with:

- [Authorization Gateway](https://github.com/silvatechf/authorization-gateway) — API authorization, JWT/JWKS verification, tenant isolation, and policy tests.
- [AppSec Scanner](https://github.com/silvatechf/AppSec-Scanner) — Python static-analysis rules, structured audit events, and a CI security gate.
- [CyberReport-Pro](https://github.com/silvatechf/CyberReport-Pro) — Python automation that turns structured security findings into PDF reports.
- [Secure Data Vault & Threat Intelligence Lab](https://github.com/silvatechf/Secure-Data-Vault-Threat-Intelligence-Lab) — a hands-on security learning lab.

Each repository has its own README for setup, implementation details, tests, and limitations.

> **A note on scope:** this is a curated working map, not a blanket claim that every repository is maintained or production-ready. Some entries are experiments or learning exercises, and some still need deeper implementation and test reviews. I prefer to make that distinction explicit rather than overstate what the code proves.

## 1. Primary backend and AppSec portfolio

- [Authorization Gateway](https://github.com/silvatechf/authorization-gateway) — FastAPI authorization, JWT/JWKS verification, tenant isolation, and policy testing.
- [AppSec Scanner](https://github.com/silvatechf/AppSec-Scanner) — Python AST-based static-analysis learning project with structured audit events.
- [Secure Data Vault & Threat Intelligence Lab](https://github.com/silvatechf/Secure-Data-Vault-Threat-Intelligence-Lab) — security-focused data handling and threat-intelligence lab.
- [CyberReport-Pro](https://github.com/silvatechf/CyberReport-Pro) — Python security-reporting project.
- [MEI em Dia](https://github.com/silvatechf/mei-app) — React/Vite PWA; a complementary product project.

## 2. Security labs

### Detection, telemetry, and incident triage
- [Triage Pipeline](https://github.com/silvatechf/triage-pipeline) — simulated authentication telemetry and heuristic risk scoring.
- [SSH Monitoring Lab](https://github.com/silvatechf/ssh-monitoring-lab) — SSH security monitoring.
- [Network Security Analytics](https://github.com/silvatechf/network-security-analytics) — network-event and security-data analysis.
- [SecSmart](https://github.com/silvatechf/SecSmart) — security tooling; scope review pending.
- [NyxOne Security Command Center](https://github.com/silvatechf/NyxOne-Security-Command-Center) — security tooling and pipeline experiment; review pending.

### Attack-surface discovery and vulnerability analysis
- [Async EASM](https://github.com/silvatechf/Async-EASM) — asynchronous HTTP exposure checks and optional Nuclei orchestration for authorized targets.
- [RCESEC PHP](https://github.com/silvatechf/rcesec-php) — PHP security exercise; review pending.
- [CodeGuard AI](https://github.com/silvatechf/codeguard-ai) — security-analysis experiment; architecture and deployment claims require validation.
- [Framework F-Score](https://github.com/silvatechf/framework-fscore) — framework/security scoring experiment.
- [MICV Runtime](https://github.com/silvatechf/micv-runtime) — runtime/tooling project; review pending.

### Threat intelligence and research
- [Spec CTI](https://github.com/silvatechf/spec-cti) — threat-intelligence and security-analysis platform; an environment file was removed from the current tree and ignore rules were added. Git history requires separate review.
- [Veredict CTI Lite](https://github.com/silvatechf/veredict-cti-lite) — threat-intelligence experiment.
- [Global Intelligence Engine](https://github.com/silvatechf/Global-Intelligence-Engine) — intelligence aggregation and analysis experiment.
- [CIEF](https://github.com/silvatechf/CIEF) — security/intelligence project; review pending.
- [SICG Repo](https://github.com/silvatechf/sicg-repo) — security project; review pending.

### Cloud and broader security experiments
- [AWS Security Foundation](https://github.com/silvatechf/aws-security-foundation) — cloud-security learning.
- [Security Report Assistant](https://github.com/silvatechf/security-report-assistant) — security-reporting experiment.
- [Twin Transition Energy Optimization Agent](https://github.com/silvatechf/Twin-Transition-Energy-Optimization-Agent-) — energy optimization/AI experiment.
- [Aura Sentinel Microservices Architecture](https://github.com/silvatechf/aura-sentinel-microservices-architecture) — architecture experiment; review pending.

## 3. Application and full-stack projects

- [AI Job Agent](https://github.com/silvatechf/ai-job-agent) — Java/Spring Boot and React job/CV analysis application.
- [SmartSpend](https://github.com/silvatechf/SmartSpend-Java-React-Python-Fullstack) — Java, React, and Python finance application; some README claims need verification.
- [Wildfire Observer](https://github.com/silvatechf/wildfire-observer) — Python-based wildfire-analysis application.
- [PapoZen App](https://github.com/silvatechf/PapoZenApp) — application project.
- [Sabor Global Site](https://github.com/silvatechf/sabor-global-site) — web project.
- [Barcelona Urban Equity](https://github.com/silvatechf/barcelona-urban-equity) — civic/data project.
- [SPN Inmob](https://github.com/silvatechf/spn-inmob) — property-related web project.
- [Veredict BI Intelligence](https://github.com/silvatechf/veredict-bi-intelligence) — business-intelligence experiment.
- [MedicInApp](https://github.com/silvatechf/MedicinApp) — application project.
- [Escape Room HTML](https://github.com/silvatechf/escape-room-html) — web exercise.
- [Clone of a Page](https://github.com/silvatechf/clone_of_a_page) — frontend practice.
- [Mondrian Practice](https://github.com/silvatechf/mondrian-practica) — CSS/layout practice.
- [Bootstrap Practice](https://github.com/silvatechf/bootstrap-practic1) — Bootstrap exercise.
- [DCL Live Streamer](https://github.com/silvatechf/dcl-live-streamer) — streaming-related project.
- [Tools for Everyday Life](https://github.com/silvatechf/-Tools_For_Everyday_Life) — utilities project.
- [Personal HTML Portfolio](https://github.com/silvatechf/fernando-cv-html5-) — early portfolio exercise.

## 4. Academic work and coding exercises

These repositories show learning progression. They are not presented as equivalent to the featured projects.

### Team-based backend contribution
- [DuckyArenas — DuckyShop & DuckyBank](https://github.com/Martret92/duckyarenas-team5/pull/87) — academic team project; individual contribution focused on Django shop/catalog and wallet/transaction services, purchase coordination, idempotency, and related tests. [PR #122](https://github.com/Martret92/duckyarenas-team5/pull/122) covers additional idempotency edge-case tests and is listed separately as pending review, not as merged work.

### Python and cybersecurity fundamentals
- [Python Cybersecurity OOP](https://github.com/silvatechf/python-cybersec-poo)
- [UF2176 EC03 Practice](https://github.com/silvatechf/UF2176_EC03_Practica)

### Java fundamentals and object-oriented programming
- [DIO Java Basics](https://github.com/silvatechf/dio-trilha-java-basico)
- [DIO OOP Challenge](https://github.com/silvatechf/Dio_desafio_poo)
- [Control Flow Challenge](https://github.com/silvatechf/DesafioControleFluxo)
- [Bank Account Challenge](https://github.com/silvatechf/iconta-banco-desafio)
- [Vehicle Exercise](https://github.com/silvatechf/Veiculo)
- [Invoice Exercise](https://github.com/silvatechf/NotaFiscal)
- [Travel System](https://github.com/silvatechf/sistema-viagem)
- [Football Championship](https://github.com/silvatechf/campeonato-futebol)
- [Veterinary Clinic](https://github.com/silvatechf/ClinicaVeterinaria)
- [Grade Matrix](https://github.com/silvatechf/MatrizNotas)
- [Java Design Patterns Lab](https://github.com/silvatechf/padroes-lab-projeto-java)
- [Spring Design Patterns Lab](https://github.com/silvatechf/padroes-lad-projeto-spring)
- [Santander Dev Week DIO API](https://github.com/silvatechf/santander-dev-week-dio-api)

### Web and guided platform exercises
- [DIO Open Source Lab](https://github.com/silvatechf/dio-lab-open-source)
- [Sudoku DIO Challenge](https://github.com/silvatechf/sudoku-dio-desafio)
- [Board DIO Challenge](https://github.com/silvatechf/board-desafio-dio)
- [Ecommerce Exercise](https://github.com/silvatechf/Ecommerce)
- [Music Theory App](https://github.com/silvatechf/AppTeoriaMusical)

## 5. Additional projects

Beyond the projects highlighted above, my GitHub profile includes smaller experiments, personal applications, and coursework across Python, Java, web development, and security.

I keep the main portfolio focused on projects that best represent my current direction. For the broader archive, visit the [complete repository list](https://github.com/silvatechf?tab=repositories).

