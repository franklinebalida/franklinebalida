# From Education Compliance to Cybersecurity GRC

## The short version

You already do the core job of a **GRC (Governance, Risk & Compliance)** professional.
The difference is the set of rules. Today you work to ACCET, BPPE and VA standards;
security GRC works to NIST, ISO 27001, SOC 2, and similar frameworks.

The work itself is the same:
- read a control framework
- turn it into policy
- collect evidence
- get through an audit
- fix the findings

You've done that loop for years and improved the result: **six findings down to
one** on your 2025 ACCET on-site visit. Very few people switching careers can
point to that kind of result.

**Recommended target:** GRC / security compliance, not SOC analyst or pentesting.
Given your management experience, aim for **mid-level GRC roles**, not entry-level
help desk. Your gap is technical security knowledge, not professional ability, and
that gap is closable in about 4–6 months.

---

## 1. Your skills mapped to GRC

| What you've done | What GRC calls it |
|---|---|
| Held compliance duties across 5 regulatory and funding bodies (ACCET, BPPE, VA/CSAAVE, ETPL, SAM.gov) | Multi-framework compliance management; control mapping across frameworks |
| Wrote the Analytic Self-Evaluation Report | Control self-assessment; audit readiness documentation |
| Led the ACCET on-site visit, 6 findings down to 1 | External audit management; findings remediation |
| Audit & corrective action | Plan of Action & Milestones (POA&M); remediation tracking |
| Turned accreditor requirements into strategy and policy | Policy development; governance |
| Advised executives on regulatory risk | Risk assessment and risk reporting to leadership |
| Negotiated the $150K Ed2go partnership and instructor contracts | Third-party / vendor risk management; contract review |
| VA approval end to end across 13+ programs | Authorization / certification packages (similar to a federal ATO) |
| Wrote ACCET approval packages for new programs | Compliance review of new initiatives ("security by design" review) |
| SAM.gov registration | Federal contracting familiarity (relevant to CMMC and FedRAMP) |
| Consulting: got a client off a state enrollment hold | Regulatory remediation consulting |
| Reusable compliance frameworks for clients | GRC program design; control libraries |
| KPI dashboards, outcome measurement | Compliance metrics and reporting |
| Directed 3 departments, supervised faculty | Program leadership; security awareness program ownership |
| Built curriculum and faculty development | Security awareness training design |
| Conference presenter | Communicating risk to non-technical audiences |

**Sector advantage:** higher education has real security-compliance duties:
- **FERPA** protects student records.
- Schools that take federal student aid (Title IV) must follow the FTC's **GLBA Safeguards Rule**, which requires a written information security program.
- **PCI DSS** applies wherever a school takes card payments.

Few security people understand how schools actually run. You do.

---

## 2. Your gaps (what to learn)

| Gap | Why it matters | How to close it |
|---|---|---|
| Security fundamentals | You need to understand the controls you assess | Roadmap Phases 1–2, Security+ |
| Security frameworks | These are the rules you'll work to | See the GRC track below |
| Technical vocabulary | So engineers take your findings seriously | Security+, plus working in a home lab |
| GRC tooling | Shows up in job postings | Free demos and trials; read vendor docs |
| Security-specific experience on your resume | Recruiters filter on it | Portfolio projects (section 5) and your consulting work |

---

## 3. Your GRC track (replaces roadmap Phases 3–6)

Do a **light** version of [Phase 1](../roadmap/01-foundations.md). Focus on
networking concepts and basic Linux; you don't need deep scripting. Then do
[Phase 2](../roadmap/02-security-core.md) fully. After that:

**Months 3–4: Frameworks**
- **NIST Cybersecurity Framework (CSF) 2.0**: learn its six functions (Govern, Identify, Protect, Detect, Respond, Recover). Start here.
- **NIST SP 800-53**: the federal control catalog. Skim the families and read AC (Access Control) and IR (Incident Response) closely.
- **ISO/IEC 27001**: how an information security management system (ISMS) works, and the Annex A controls.
- **SOC 2**: the five Trust Services Criteria. Most SaaS companies hire GRC staff mainly to pass SOC 2.
- **Risk:** NIST SP 800-30 (risk assessments), risk registers, and scoring likelihood × impact.
- **NIST SP 800-171 / CMMC**: see the San Diego note below.

**Months 4–6: Applied GRC work**
- Third-party risk: security questionnaires (the SIG, CAIQ), reviewing a vendor's SOC 2 report
- Evidence collection and continuous compliance
- Policy writing: acceptable use, access control, incident response, data classification
- Tool familiarity: Vanta, Drata, AuditBoard, ServiceNow GRC, OneTrust

**The San Diego angle:** San Diego has a large defense industry. Defense
contractors must meet **CMMC** (based on NIST SP 800-171), and demand for
compliance people there is strong. You already have SAM.gov and federal-approval
experience, so this is worth targeting.

---

## 4. Certifications, in order

1. **ISC2 Certified in Cybersecurity (CC)** *(optional, cheap or free)*: a quick confidence builder while you study for Security+.
2. **CompTIA Security+**: the baseline that most job postings filter on. **This is your first priority.**
3. Then pick **one** based on the jobs you're getting:
   - **ISACA CISA**: the IT audit standard and a strong fit with your audit background. It requires 5 years of relevant experience, and some can be substituted. Check what counts on ISACA's site, since your compliance years may partially qualify.
   - **ISO 27001 Lead Implementer or Lead Auditor**: a short course. Popular with consultancies and companies that work internationally.
   - **ISC2 CGRC**: the governance, risk and compliance certification. Good for federal and CMMC work.
   - **CMMC Certified Professional (CCP)**: if you go for the defense-contractor market.

Longer term, **CISSP** or **CISM** are management-level certifications that fit
your leadership background. Both require verified security work experience, so
they'll come later.

---

## 5. Portfolio projects that combine your two fields

Keep these in a `portfolio/` folder in this repo. Each one is a work sample you
can show in interviews.

1. **GLBA Safeguards Rule written information security program (WISP) for a fictional career college.** Include a risk assessment, the list of required program elements, and assigned owners. This shows off your sector knowledge directly.
2. **NIST CSF 2.0 gap assessment** of that same fictional school: current profile, target profile, and a prioritized remediation roadmap. It's formatted like your ACCET self-study, so you already know the shape.
3. **Crosswalk mapping FERPA and GLBA requirements to NIST CSF controls.** Mapping requirements across frameworks is what you did with ACCET, BPPE and the VA.
4. **Vendor risk review:** write a security questionnaire for a fictional learning-management-system vendor, then review a sample SOC 2 report and write up the findings.
5. **Security awareness training module** for school staff (phishing, protecting student data). This uses your curriculum design skills.

---

## 6. Rewriting your resume bullets for security GRC roles

Keep every claim true. These reword what you actually did into the language
security recruiters search for.

- Served as institution-wide compliance lead across **five regulatory frameworks**; mapped overlapping requirements into unified policies and evidence processes.
- Managed an **external accreditation audit** end to end, from self-assessment report through on-site review, **reducing findings from 6 to 1** against the prior review.
- Ran **corrective-action (remediation) tracking** for audit findings through to closure.
- Assessed and communicated **regulatory risk** to executive leadership, informing decisions on program portfolio and funding eligibility.
- Negotiated and structured **third-party contracts** (including a $150K partnership), managing terms and obligations with external vendors.
- Built **reusable compliance frameworks and reporting tools** used across consulting clients.

Once you have Security+ and a portfolio project or two, add a **"Cybersecurity"**
section listing the certification, the frameworks you know, and links to your
portfolio.

**Keyword tip:** job-screening software looks for terms like *NIST CSF, risk
assessment, control testing, audit readiness, third-party risk, policy
development, SOC 2, ISO 27001*. Only list the ones you've actually studied or used.

---

## 7. Job titles to search for

- GRC Analyst / Senior GRC Analyst
- IT Compliance Analyst / Security Compliance Specialist
- Third-Party Risk Analyst / Vendor Risk Analyst
- IT Auditor (especially after CISA)
- Information Security Program Manager
- CMMC Compliance Specialist / Consultant
- Higher-ed roles: Information Security Compliance Officer, Data Privacy Officer, IT Risk Manager

---

## 8. Using your consulting business

Matulin Consulting already advises schools on compliance. Once you have
Security+ and have completed portfolio projects 1 and 3, you can credibly add
**GLBA Safeguards / FERPA security-compliance readiness** for postsecondary
schools as a service. Real client work in security GRC is the strongest resume
line you can get. Only offer it once you're genuinely ready to deliver it.

---

## Your next 90 days

- [ ] **Weeks 1–4:** light Phase 1 (networking and Linux concepts); read an overview of NIST CSF 2.0
- [ ] **Weeks 5–10:** Phase 2 and Security+ study; book the exam
- [ ] **Weeks 11–12:** pass Security+; start portfolio project 1 (the WISP)
- [ ] **Ongoing:** update your LinkedIn headline to something like *"Compliance & Accreditation Leader → Cybersecurity GRC"*, and join ISACA San Diego, ISC2 San Diego, and ISSA San Diego events to network
