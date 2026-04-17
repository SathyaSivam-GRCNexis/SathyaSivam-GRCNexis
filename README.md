# Hi, I'm Sathya

I build practical GRC and privacy programs for mid-market SaaS companies — the kind that have outgrown a compliance checklist but aren't yet at enterprise scale. The repos pinned below are a working portfolio: documentation, templates, and worked examples I'd actually hand to a team on day one of a program build.

<!-- TODO: replace with your LinkedIn URL -->
**LinkedIn:** coming soon

---

## What this portfolio is

Ten documentation-heavy GRC repos, each a self-contained toolkit. They share a common worked example — **Northwind SaaS**, a fictional Series B B2B SaaS (180 employees, $14M ARR, AWS multi-region, SOC 2 Type II, pursuing ISO 27001) — so the pieces compose into a coherent picture of how a real program looks end-to-end.

Design principles across all ten:

- **Practitioner voice, not vendor voice.** Written how a working GRC lead would actually talk, not how a compliance brochure reads.
- **Opinionated.** Where there's a choice, I make one and explain why.
- **Honest about what doesn't work.** Every repo's worked example includes what went wrong, what had to be retired, and what's still imperfect.
- **Cross-referenced.** Frameworks (ISO 27001, SOC 2, NIST CSF, GDPR, ISO 22301, etc.) are mapped where alignment is real, not aspirational.
- **Licensed CC-BY-4.0.** Adapt, reuse, ship.

## The portfolio

### Foundation
| Repo | What it is |
|---|---|
| [grc-erm-framework](https://github.com/SathyaSivam-GRCNexis/grc-erm-framework) | Enterprise risk management: methodology, scoring model, register, treatment workflow, appetite. ISO 31000 + ISO 27005. |
| [grc-control-mapping-matrix](https://github.com/SathyaSivam-GRCNexis/grc-control-mapping-matrix) | Cross-framework control mapping: ISO 27001:2022 ↔ NIST CSF 2.0 ↔ SOC 2 TSC ↔ CIS v8, with relationship-strength annotations. |

### Compliance programs
| Repo | What it is |
|---|---|
| [grc-iso27001-toolkit](https://github.com/SathyaSivam-GRCNexis/grc-iso27001-toolkit) | ISO/IEC 27001:2022 ISMS: scope doc, full SoA (all 93 Annex A controls), gap assessment, implementation plan, internal audit program, management review. |
| [grc-infosec-policy-framework](https://github.com/SathyaSivam-GRCNexis/grc-infosec-policy-framework) | Ten information security policies mapped to ISO 27001:2022 and SOC 2 — written to be adapted and actually followed. |
| [grc-audit-readiness-playbook](https://github.com/SathyaSivam-GRCNexis/grc-audit-readiness-playbook) | 12-week audit-readiness playbook for SOC 2 / ISO 27001: evidence mapping, RACI, common findings, walkthrough prep. |

### Operational
| Repo | What it is |
|---|---|
| [grc-incident-response-toolkit](https://github.com/SathyaSivam-GRCNexis/grc-incident-response-toolkit) | IR policy, playbooks (ransomware, phishing, data exposure, insider threat, cloud compromise, DDoS), severity matrix, comms templates, tabletop guide. NIST 800-61, ISO 27035, SOC 2. |
| [grc-bcp-dr-framework](https://github.com/SathyaSivam-GRCNexis/grc-bcp-dr-framework) | BCP/DR: BIA, DR plans, crisis management, runbooks, test plan. ISO 22301, NIST 800-34, SOC 2 A1. |
| [grc-tprm-toolkit](https://github.com/SathyaSivam-GRCNexis/grc-tprm-toolkit) | Third-party risk: policy, tiering, questionnaires (short / full / AI), onboarding and offboarding checklists, contract security addendum. |

### Analysis & reporting
| Repo | What it is |
|---|---|
| [grc-saas-risk-scenarios](https://github.com/SathyaSivam-GRCNexis/grc-saas-risk-scenarios) | 12 realistic SaaS risk scenarios with likelihood/impact scoring, response narratives, and control mapping. ISO 27005, NIST 800-30, FAIR. |
| [grc-grc-metrics-kpi](https://github.com/SathyaSivam-GRCNexis/grc-grc-metrics-kpi) | 40+ metrics across 10 domains with formulas, targets, data sources, and board-report and monthly-review templates. |

---

## How to read the portfolio

Different audiences will want different entry points.

- **Hiring manager / peer GRC lead:** start with [grc-erm-framework](https://github.com/SathyaSivam-GRCNexis/grc-erm-framework) and [grc-grc-metrics-kpi](https://github.com/SathyaSivam-GRCNexis/grc-grc-metrics-kpi). They best show thinking depth across the GRC cycle, from risk identification through measurement.
- **Auditor or assessor:** [grc-iso27001-toolkit](https://github.com/SathyaSivam-GRCNexis/grc-iso27001-toolkit) and [grc-audit-readiness-playbook](https://github.com/SathyaSivam-GRCNexis/grc-audit-readiness-playbook) are written in the voice you'd actually want to see from a client.
- **Operator (CISO / engineering lead):** [grc-incident-response-toolkit](https://github.com/SathyaSivam-GRCNexis/grc-incident-response-toolkit), [grc-bcp-dr-framework](https://github.com/SathyaSivam-GRCNexis/grc-bcp-dr-framework), and [grc-tprm-toolkit](https://github.com/SathyaSivam-GRCNexis/grc-tprm-toolkit) are the "what do I actually hand my team" repos.
- **Risk practitioner:** [grc-saas-risk-scenarios](https://github.com/SathyaSivam-GRCNexis/grc-saas-risk-scenarios) and [grc-control-mapping-matrix](https://github.com/SathyaSivam-GRCNexis/grc-control-mapping-matrix) are the most analytically dense.

## About me

I care about GRC work that actually improves security and reduces risk — not frameworks as performance. Most of what exists publicly in the GRC space is either vendor marketing or framework recitation. I've tried to write toolkits I'd want to receive from someone handing off a program.

The portfolio is a work in progress. A set of technical GRC repos (automation, IaC compliance scanning, evidence-collection pipelines, policy-as-code) is in planning and will be added over the coming months.

## Get in touch

- **GitHub issues:** open one on any repo if something's unclear, wrong, or you'd like to see something added.
- **LinkedIn:** <!-- TODO: replace with your LinkedIn URL -->
- **Email:** open to GRC / privacy / security roles and consulting conversations.
