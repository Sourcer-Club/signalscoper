# SourcerLens 🔍
**Search smarter. Understand deeper.**

A free tool for recruiters and talent acquisition professionals that helps you understand any role you're hiring for — and generate powerful Boolean search strings to find the right candidates on job boards.

🔗 **Live tool:** https://johnrambo-r.github.io/sourcerlens/

---

## The Problem It Solves

Most recruiters search by job title and a handful of obvious keywords. This works for common roles but fails for specialised ones — especially in tech, pharma, BFSI and manufacturing — where the best candidates often use practitioner language that doesn't appear in standard searches.

SourcerLens bridges that gap. It teaches you how a role's practitioners think and speak, then generates a Boolean string built around that persona — so you surface candidates who are genuinely doing the work, not just people who match a title.

---

## What's Inside

- **200 roles** across Technology, BFSI, Healthcare & Pharma, and Manufacturing & Engineering
- **Role overviews** written for recruiters with no prior domain knowledge
- **Persona keyword pills** — the non-obvious terms practitioners actually use
- **Boolean search strings** optimised for Naukri, with title anchors and persona keywords
- **Smart filters** for roles where specialisation matters — e.g. Backend Developer (Python / Java / Node.js), PLC Programmer (Siemens / Allen Bradley / Mitsubishi), CAD Engineer (CATIA / SolidWorks / NX)
- **Synonym search** — search "quant" and find Quantitative Analyst, search "SRE" and find Site Reliability Engineer
- **One-click copy** for the Boolean string

---

## How to Use It

1. Open https://johnrambo-r.github.io/sourcerlens/
2. Type the role you're hiring for in the search bar
3. Read the overview to understand the role
4. Review the persona keyword pills to understand how practitioners think
5. Select a filter if available (e.g. language, platform, specialisation)
6. Copy the Boolean string and paste it into your job board of choice

---

## Roles Covered

| Industry | Roles |
|---|---|
| Technology | 80 |
| BFSI | 40 |
| Healthcare & Pharma | 40 |
| Manufacturing & Engineering | 40 |
| **Total** | **200** |

**Technology** includes: Business Analyst, Data Scientist, Machine Learning Engineer, DevOps Engineer, Site Reliability Engineer, Cloud Architect, Frontend / Backend / Full Stack Developer, QA Engineer, Security Analyst, GenAI Engineer, Prompt Engineer, and many more.

**BFSI** includes: Credit Analyst, AML Analyst, KYC Analyst, Quantitative Analyst, Actuarial Analyst, Portfolio Manager, Compliance Officer, Payments Operations Analyst, and more.

**Healthcare & Pharma** includes: Clinical Research Associate, Pharmacovigilance Analyst, Regulatory Affairs Specialist, Biostatistician, Medical Writer, Formulation Scientist, HEOR Analyst, and more.

**Manufacturing & Engineering** includes: Production Engineer, CAD Engineer, PLC Programmer, Automation Engineer, Reliability Engineer, Six Sigma Black Belt, Welding Engineer, NDT Engineer, and more.

---

## Roadmap

- [ ] SAP / ERP module (ABAP, Basis, FICO, MM, SD, HANA, and more)
- [ ] Expand to 500 roles
- [ ] LinkedIn Boolean string variant
- [ ] Export Boolean strings to clipboard with platform formatting
- [ ] Community-suggested roles

---

## Feedback & Contributions

Found a role that's missing? Think a Boolean string could be better? Have a keyword we should add?

This tool is built for the TA community and improves with your input. Raise an issue on this repo or connect with us directly.

---

## Tech Stack

Plain HTML, CSS and JavaScript. No frameworks, no build process, no backend. Hosted on GitHub Pages.

Single file architecture — everything lives in `index.html`. Data will be separated into `data.js` as the role library grows.

---

## License

Free to use. Built for recruiters, by recruiters.
