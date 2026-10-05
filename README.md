# Hi, I'm Rosemberth Preciga

**Software Engineer · QA Automation, backend & AI** · Bogotá, Colombia

Electronics engineering graduate from Universidad Nacional de Colombia (GPA 4.6/5.0). I build test automation frameworks with Playwright and Selenium, the APIs those tests validate and the CI pipelines that run them, and I use AI agents so that failing tests explain and repair themselves. Before engineering, I spent four years diagnosing Stripe API and webhook integrations for businesses in production. English C2.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-rosemberth--preciga-0A66C2?logo=linkedin&logoColor=white)](https://linkedin.com/in/rosemberth-preciga)
[![Email](https://img.shields.io/badge/Email-r.preciga.puentes%40gmail.com-D14836?logo=gmail&logoColor=white)](mailto:r.preciga.puentes@gmail.com)
[![YouTube](https://img.shields.io/badge/YouTube-%40estiberz-FF0000?logo=youtube&logoColor=white)](https://youtube.com/@estiberz)

## Featured work

### [gitea-ui-automation](https://github.com/rprecigapuentes/gitea-ui-automation) · end-to-end test automation

[![CI](https://github.com/rprecigapuentes/gitea-ui-automation/actions/workflows/ci.yml/badge.svg)](https://github.com/rprecigapuentes/gitea-ui-automation/actions/workflows/ci.yml)
[![CT-functional](https://github.com/rprecigapuentes/gitea-ui-automation/actions/workflows/ct-functional.yml/badge.svg)](https://github.com/rprecigapuentes/gitea-ui-automation/actions/workflows/ct-functional.yml)
[![Reports](https://img.shields.io/badge/test%20reports-GitHub%20Pages-2EAD33)](https://rprecigapuentes.github.io/gitea-ui-automation/)

- Four frameworks (Selenium + Vitest, Selenium + Cucumber, Playwright, Playwright-BDD) share one layered set of page objects through the Strategy pattern, in an npm workspaces monorepo built with spec-driven development (OpenSpec).
- Cross-browser regression cut from 17 min to under 6 min (2.9×) by running in parallel on Selenium Grid and per-browser Playwright projects.
- Accessibility (axe-core, WCAG) and performance suites in CI; an LLM classifies each failure and a Codex CLI agent with Playwright MCP proposes the repaired locator in under 4 minutes.

### [monster-hunter-guild-api](https://github.com/rprecigapuentes/monster-hunter-guild-api) · REST API, team of four

Layered TypeScript API with Express, Prisma and MySQL, five design patterns and a CI/CD pipeline with SonarQube and semantic release. My part: the Observer-based audit trail, the generic base service, and the Blue/Green deployment with Ansible and nginx in [mhg-deployments](https://github.com/rprecigapuentes/mhg-deployments).

### [trello-api-bdd](https://github.com/rprecigapuentes/trello-api-bdd) · API testing, team of four

BDD suite for the Trello REST API with Playwright, playwright-bdd and Zod: 61 automated cases that exposed 3 real defects. My part: the Organizations and Labels resources, contract validation and the GitLab CI pipeline on a self-hosted runner.

### [light-well](https://github.com/rprecigapuentes/light-well) · data analysis and AI

ESP32 wearable that measures light exposure. I built the data analysis (melanopic illuminance per CIE S 026, daily WELL v2 compliance) in Python and FastAPI, and an LLM assistant that answers questions about the measurements.

### [siespro-lora](https://github.com/rprecigapuentes/siespro-lora) · machine learning on IoT

Perimeter monitoring for schools over LoRa. I trained the Random Forest classifier that detects when a student leaves the perimeter from link quality (RSSI, SNR) and environmental data, and wrote the ESP32 firmware. Presented at TPI ExpoIdeas 2025.

**Earlier hardware and research work:** [camminator](https://github.com/rprecigapuentes/camminator) (YOLO, LiDAR, Whisper and a local LLM on a Raspberry Pi), [Agrometeorological-LoRa-System](https://github.com/rprecigapuentes/Agrometeorological-LoRa-System), [Van-de-Vusse-Digital-Twin](https://github.com/rprecigapuentes/Van-de-Vusse-Digital-Twin), [systemc-bus-arbitration](https://github.com/rprecigapuentes/systemc-bus-arbitration), [fpga-robot-ultrasonic](https://github.com/rprecigapuentes/fpga-robot-ultrasonic) and [tech-outreach](https://github.com/rprecigapuentes/tech-outreach), educational videos on AI and quantum computing with over 12,000 views.

## Now

**AI & Automation Engineer at AutomindAI.** A WhatsApp ordering agent (n8n, OpenAI, Whisper, PostgreSQL) whose orders reach the kitchen printer in about 30 seconds, servers provisioned with Ansible in a single run, and 386 automated regression checks.

## Tech stack

**Testing**

![Playwright](https://img.shields.io/badge/Playwright-2EAD33?style=for-the-badge&logo=playwright&logoColor=white)
![Selenium](https://img.shields.io/badge/Selenium-43B02A?style=for-the-badge&logo=selenium&logoColor=white)
![Cucumber](https://img.shields.io/badge/Cucumber-23D96C?style=for-the-badge&logo=cucumber&logoColor=white)
![Jest](https://img.shields.io/badge/Jest-C21325?style=for-the-badge&logo=jest&logoColor=white)
![Vitest](https://img.shields.io/badge/Vitest-6E9F18?style=for-the-badge&logo=vitest&logoColor=white)

**Backend & data**

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-5FA04E?style=for-the-badge&logo=nodedotjs&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=for-the-badge&logo=express&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=for-the-badge&logo=prisma&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)

**DevOps**

![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Ansible](https://img.shields.io/badge/Ansible-EE0000?style=for-the-badge&logo=ansible&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)
![GitLab CI](https://img.shields.io/badge/GitLab_CI-FC6D26?style=for-the-badge&logo=gitlab&logoColor=white)
![SonarQube](https://img.shields.io/badge/SonarQube-4E9BCD?style=for-the-badge&logo=sonarqube&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)

**AI**

![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=for-the-badge&logo=openai&logoColor=white)
![n8n](https://img.shields.io/badge/n8n-EA4B71?style=for-the-badge&logo=n8n&logoColor=white)
![Claude Code](https://img.shields.io/badge/Claude_Code-D97757?style=for-the-badge&logo=claude&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white)

**Ways of working:** Scrum, Kanban, Jira and Zephyr; layered architecture, design patterns, SOLID and the test pyramid; spec-driven development.

## Certifications

- CyberOps Associate · Cisco and Universidad Nacional (2026)
- Ethical Hacker · Cisco (2026)
- Multiplex Immunofluorescence and AI for Tissue Profiling · LNMA–UNAM and SIPAIM (2025)
- CCNA: Introduction to Networks · Cisco (2025)
- AI and Digital Twins Applied to Engineering · Universidad Nacional (2025)

## Honors

- Tuition waivers in several semesters for ranking among the program's top 15 GPAs, Universidad Nacional (2021–2024)
- 2nd place, XVII Circuit Tournament of Universidad Nacional, Analog I category (2023)
- Colombian Mathematics Olympiad: 1st place at school level and national finalist (2018–2019)
- Colombian Physics Olympiad: 1st place at school level and national finalist (2018–2019)

## Languages

Spanish (native) · English (C2, EF SET 72/100) · Italian (C1)
