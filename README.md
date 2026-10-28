# Fernando Silva

**Junior Python Backend Developer | Application Security (AppSec)**  
Barcelona, Spain · Open to junior opportunities in Spain

I build Python projects focused on backend engineering and practical application security. My current work explores API design, authentication and authorization, security testing, static analysis, and automation in development workflows.

I am looking for a junior software engineering opportunity where I can contribute, learn from experienced engineers, and continue growing towards Application Security Engineering.

[LinkedIn](https://www.linkedin.com/in/fernando-silva-83b155a4/) · [All repositories](https://github.com/silvatechf?tab=repositories)

---

## Featured projects

### [AppSec Scanner](https://github.com/silvatechf/AppSec-Scanner)
A Python static-analysis learning project that uses the AST to identify selected vulnerability patterns and records structured audit events.

- Detects selected SQL injection and path-traversal patterns.
- Supports limited automated remediation for a narrowly defined case.
- Includes a small self-authored benchmark and a CI security gate.
- Integrates with a local Loki/Grafana observability stack.

**Limitations:** its benchmark contains only 10 author-created cases. Reported results describe that test corpus and do not establish performance on real-world or production code. This tool is not a replacement for a mature SAST product or a professional security review.

### [Authorization Gateway](https://github.com/silvatechf/authorization-gateway)
A FastAPI and PyJWT project exploring centralized authorization for a multi-tenant API.

- Demonstrates token verification, roles, scopes, ownership checks, and tenant isolation.
- Uses explicit policy evaluation and a fail-closed approach.
- Includes automated tests for authorization boundaries and denied requests.

**Scope:** an educational portfolio project, not a production-ready identity or authorization platform.

### [Secure Data Vault — Threat Intelligence Lab](https://github.com/silvatechf/Secure-Data-Vault-Threat-Intelligence-Lab)
A hands-on security lab for studying secure software engineering, API security, cryptography, and defensive analysis.

See the repository documentation for current functionality, setup instructions, and lab limitations.

### [CyberReport-Pro](https://github.com/silvatechf/CyberReport-Pro)
A Python CLI project that converts structured security findings into PDF reports, with study-oriented mappings to Spanish security and data-protection frameworks.

- Separates input loading, mapping, and report rendering.
- Includes automated tests and development-quality checks.
- Generates Spanish-language reports for the intended audience.

**Limitations:** regulatory mappings are educational references and should be independently verified; generated reports are not legal advice.

---

## Technical focus

- **Programming:** Python
- **Backend:** FastAPI, REST APIs, JWT-based authentication and authorization
- **Application security:** secure coding fundamentals, authorization testing, static analysis, input handling, and threat modelling
- **Quality:** pytest, automated tests, linting, and static checks
- **Tools and delivery:** Git, GitHub Actions, Docker
- **Observability:** structured audit events, Loki, and Grafana in portfolio projects

This list describes technologies used in the projects above; it does not imply professional production experience with every tool.

## Current learning goals

- Strengthen Python backend fundamentals and API design.
- Improve application-security testing and threat modelling for web applications.
- Integrate repeatable security checks into development workflows.
- Make projects easier to install, test, understand, and review.

## Engineering principles

- Prefer explicit, testable security rules over implicit assumptions.
- Test denial and failure paths as deliberately as successful requests.
- Document limitations and distinguish measured results from assumptions.
- Test only systems and environments I own or am authorized to assess.

---

## Contact

For professional opportunities and technical discussions, connect with me on [LinkedIn](https://www.linkedin.com/in/fernando-silva-83b155a4/).
