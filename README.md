# Virtual Threat Modeling and Vulnerability Assessment

## Project overview
This is a learning-focused cybersecurity project for the Week 1 Cybersecurity Analyst Internship task. It demonstrates how to define a hypothetical virtual network, identify possible threats using STRIDE, record illustrative risks, and propose mitigations.

## Important scope note
This repository is a **desk-based simulated assessment**. No live system was scanned and no vulnerability scanner output is claimed. The vulnerabilities and risk ratings are illustrative examples for learning purposes. To turn this into a real assessment, document the authorized lab environment, tools, commands, dates, and actual findings.

## Scenario
A small organization uses:
- Employee laptops
- A web application
- An application server
- A database containing test/customer-like records
- An administrator account
- Internet and internal network connections

## Threat-model boundaries
Included: the hypothetical web app, application server, database, user/admin access, and data flows.
Excluded: real third-party systems, public IP targets, and any system without explicit authorization.

## STRIDE summary
- **Spoofing:** stolen or weak credentials could allow impersonation.
- **Tampering:** insufficient validation or permissions could allow unauthorized changes.
- **Repudiation:** inadequate logs could make actions difficult to trace.
- **Information disclosure:** overly broad database access or unencrypted traffic could expose data.
- **Denial of service:** excessive requests could reduce service availability.
- **Elevation of privilege:** misconfigured roles could grant excessive permissions.

## Illustrative risk method
Likelihood and impact are scored from 1 (low) to 5 (high). Risk score = likelihood × impact.
- 1–4: Low
- 5–9: Medium
- 10–16: High
- 17–25: Critical

Scores are illustrative, not measured scan results. See `risk_register.csv`.

## Files
- `threat_model.md` — boundaries, assets, flows, and STRIDE threats
- `risk_register.csv` — example risk register and scores
- `mitigation_plan.md` — prioritized remediation timeline
- `references.md` — framework and guidance links
- `report.docx` — report document for review/submission

## How to improve this project
1. Use only a deliberately vulnerable local lab or an environment for which you have written authorization.
2. Record actual tools, versions, commands, timestamps, and outputs.
3. Replace illustrative findings with evidence from the authorized lab.
4. Recalculate risks based on observed likelihood and impact.
5. Do not upload passwords, tokens, personal data, or confidential system details.
