# 🤖 AI Security Lab

![Track](https://img.shields.io/badge/track-AI%20for%20Security-purple)
![Bootcamp](https://img.shields.io/badge/DIO-AWS%20Cybersecurity-blue)
![Status](https://img.shields.io/badge/status-in%20progress-yellow)
![License](https://img.shields.io/badge/license-MIT-lightgrey)

My study lab for the **foundations of Artificial Intelligence applied to cybersecurity**:
machine learning concepts, generative AI and LLMs, AI agents, AI-driven detection and the security of AI systems itself.

It is the theory companion of [**python-security-lab**](https://github.com/LeoneDutra/python-security-lab)
(where the code lives) and part of my preparation for a postgraduate program in
**AI for Security Engineering** (FIAP, starting March 2027).
The entry point is the **DIO AWS Cybersecurity Bootcamp** (Linux, networking, pentest, AWS IAM, GuardDuty, KMS and an AI vulnerability agent).

## 🗺️ Roadmap

| Phase | Topic | Weeks | Deliverable | Status |
|---|---|---|---|---|
| B | DIO AWS Cybersecurity Bootcamp | W01–W10 | Project challenges + certificate | 🟡 In progress |
| A1 | AI fundamentals | W01–W02 | [Notes](notas/A1-fundamentos.md) + glossary | 🟡 In progress |
| A2 | Machine learning concepts | W03–W05 | [Notes](notas/A2-machine-learning.md) | ⏳ |
| A3 | Neural networks and deep learning | W06–W07 | [Notes](notas/A3-deep-learning.md) | ⏳ |
| A4 | Generative AI and LLMs (prompting, RAG) | W08–W10 | [Notes](notas/A4-ia-generativa-llms.md) + prompt library | ⏳ |
| A5 | AI agents and AI for security operations | W11–W12 | [Notes](notas/A5-agentes-e-seguranca.md) | ⏳ |
| A6 | Security of AI (OWASP LLM Top 10, MITRE ATLAS) | W13 | [Notes](notas/A6-seguranca-da-ia.md) + threat model | ⏳ |

**Timeline:** 30 Nov 2026 → 06 Mar 2027 · ~6–7 h/week, alongside the Python lab.

## 🚀 Featured projects

| Project | Source | Skills | Status |
|---|---|---|---|
| Attack simulation in an isolated lab | DIO Bootcamp | Linux, networking, OSINT, pentest | ⏳ |
| AWS security solution (IAM, GuardDuty, KMS) | DIO Bootcamp | AWS, detection, data protection | ⏳ |
| AI agent that finds and helps fix vulnerabilities | DIO Bootcamp | LLM, agents, AWS | ⏳ |
| Security prompt library | AI Lab | Prompt engineering, evaluation | ⏳ |
| Threat model of the AI agent | AI Lab | OWASP LLM Top 10, MITRE ATLAS | ⏳ |

## 📁 Structure

| Folder / file | Content |
|---|---|
| [`glossario.md`](glossario.md) | AI glossary written in my own words (Feynman technique) |
| [`notas/`](notas/) | One summary per phase |
| [`bootcamp-dio/`](bootcamp-dio/) | Bootcamp project challenges, one folder each |
| [`prompts/`](prompts/) | Tested prompts for security tasks |
| [`projetos/`](projetos/) | AI projects and the agent threat model |

> 🇧🇷 Study notes are written in Portuguese, my native language; READMEs are in English.

## 🧭 Method

- **Feynman test:** a concept is only "learned" when I can explain it in three plain sentences with a security example.
- **Weekly loop:** study → write notes → commit → Friday self-assessment (0–4 scale) and retrospective.
- **Theory first, code next:** each phase here precedes the matching phase in `python-security-lab`.

## 🔐 Lab rules

- No secrets in the repository: credentials live in `.env`, which is git-ignored.
- Offensive techniques (pentest, exploitation) are practised only in my own isolated lab or authorised platforms.
- Examples use synthetic or sanitised data — never real logs or personal information.

## 📚 Main references

[Elements of AI](https://www.elementsofai.com/) ·
[Google ML Crash Course](https://developers.google.com/machine-learning/crash-course) ·
[3Blue1Brown — Neural Networks](https://www.3blue1brown.com/topics/neural-networks) ·
[OWASP Top 10 for LLM](https://genai.owasp.org/llm-top-10/) ·
[MITRE ATLAS](https://atlas.mitre.org/) ·
[AWS Skill Builder](https://skillbuilder.aws/)

## 📄 License

[MIT](LICENSE)
