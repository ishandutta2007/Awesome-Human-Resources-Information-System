# Awesome-Human-Resources-Information-System

# Top HRIS Tools Ecosystem
**Curated List of SaaS Products & Open-Source GitHub Projects**
*Focused on Human Resource Information Systems, Employee Records, Payroll, Leave & Attendance, Onboarding, Benefits & People Operations*
**Last updated: August 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **HRIS (Human Resource Information Systems)**. These tools serve as the system of record for employee data and typically cover core HR, onboarding, time-off, attendance, payroll (or payroll integrations), benefits administration, performance, and employee self-service.

**Examples** include Workday, BambooHR, HiBob, Rippling, Gusto, Deel, Remote, Factorial, Personio, and Paylocity (the category leaders and widely adopted platforms).

**Open-source emphasis**: Core HRIS functionality has several mature open-source options. The section below prioritizes actively maintained, self-hostable platforms that organizations can run without per-employee licensing fees while retaining full control over sensitive employee data.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites / GitHub repos.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms
- **[Workday](https://www.workday.com/)**  
  Enterprise-grade HCM and financials platform covering HR, payroll, talent, learning, and planning for large global organizations.
- **[BambooHR](https://www.bamboohr.com/)**  
  Popular mid-market and SMB HRIS known for clean UX, employee records, onboarding, time-off, and reporting.
- **[HiBob](https://www.hibob.com/)**  
  Modern people platform focused on culture, employee experience, and scalable HR operations for growing companies.
- **[Rippling](https://www.rippling.com/)**  
  Unified platform combining HR, payroll, IT (device & app management), and spend — strong for companies wanting one system of record across people and technology.
- **[Gusto](https://gusto.com/)**  
  US-focused payroll, benefits, and HR platform popular with small businesses for ease of use and compliance support.
- **[Deel](https://www.deel.com/)**  
  Global payroll, EOR, contractor management, and HR platform designed for distributed and international teams.
- **[Remote](https://remote.com/)**  
  Global employment and HR platform specializing in compliant international hiring, payroll, and benefits.
- **[Factorial](https://factorialhr.com/)**  
  All-in-one HR platform popular in Europe and growing markets, covering core HR, time tracking, and people processes.
- **[Personio](https://www.personio.com/)**  
  European HRIS and payroll platform focused on SMBs and mid-market companies with strong compliance features.
- **[Paylocity](https://www.paylocity.com/)**  
  US-based HCM platform offering payroll, HR, benefits, and talent management with strong analytics.
- **[SAP SuccessFactors](https://www.sap.com/products/hcm.html)**, **[UKG](https://www.ukg.com/)**, **[Oracle Cloud HCM](https://www.oracle.com/human-capital-management/)**  
  Additional enterprise HCM suites frequently evaluated alongside Workday.

## Open-Source GitHub Projects
- **[Frappe HR](https://github.com/frappe/hrms)** (and ERPNext HR modules)  
  Modern, actively developed open-source HR and Payroll software built on the Frappe framework. Covers employee lifecycle, leave & attendance, shifts, expense claims, recruitment, performance, payroll, taxation, and analytics. One of the strongest full-featured open HRIS options, especially when paired with ERPNext.
- **[OrangeHRM](https://github.com/orangehrm/orangehrm)** (Starter / Community Edition)  
  Long-standing open-source HR management system with modules for employee management, leave, time, recruitment, performance, and more. Widely recognized and battle-tested for core HRIS needs.
- **[Odoo HR](https://github.com/odoo/odoo)** (Community Edition + OCA HR addons)  
  Human resources modules within the Odoo open-source ERP suite. Includes employees, time off, recruitment, appraisals, expenses, and related features. Highly extensible via the Odoo Community Association (OCA) HR repositories.
- **[IceHrm](https://icehrm.com/)**  
  Modern open-source HR management platform with a clean interface, employee self-service, leave, attendance, and related modules. Actively maintained and suitable for SMBs seeking a contemporary self-hosted option.
- **[Sentrifugo](https://sourceforge.net/projects/sentrifugo/)**  
  Open-source HRMS focused on appraisals, employee self-service, and core HR processes.
- **[TimeTrex Community](https://www.timetrex.com/)**  
  Open-source time and attendance / workforce management system that can serve as a strong component of an HRIS stack, with payroll capabilities in higher editions.
- **Open HRMS and Odoo-based dedicated HR builds**  
  Community distributions and modules that package Odoo HR functionality into more focused HRIS deployments.
- **Supporting open tools** for leave management, employee portals, and document workflows that integrate with the platforms above.

### Additional Strong Open-Source Options
- Custom employee portals and self-service frontends built on open frameworks.
- Open-source ATS / recruiting tools (e.g., OpenCATS) that complement core HRIS systems.
- Payroll calculation engines and tax libraries for specific jurisdictions (often paired with Frappe HR or Odoo).
- Integration connectors for SSO, accounting, and benefits providers.
- Lightweight Django or other framework-based leave and attendance applications for very small teams.

**Frameworks for building custom systems**: Organizations already running **ERPNext** or the Frappe stack typically adopt **Frappe HR**. Those wanting a standalone classic HRIS often start with **OrangeHRM**. Teams invested in the Odoo ecosystem use **Odoo HR + OCA modules**. Payroll remains the biggest gap in pure open-source for many countries — most deployments integrate a local payroll provider or use paid modules for full compliance.

## How to Contribute
1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer
- This is a **community-curated** list — not exhaustive and not an endorsement.
- HRIS platforms should be evaluated for core employee data management, leave/attendance accuracy, payroll compliance (especially multi-country), reporting, employee self-service experience, integrations, data residency/security, and total cost of ownership (including self-hosting effort).
- Open-source HRIS solutions give full data ownership and eliminate per-employee fees but require technical resources for deployment, security hardening, backups, upgrades, and often a separate payroll solution for full statutory compliance.
---
**Made for People Ops leaders, HR teams, and organizations that want control over employee data without perpetual per-seat lock-in.**
Let's make core HR, employee records, and people operations more open, private, and affordable.
