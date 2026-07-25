# Comprehensive Learner Record (CLR) — Assembly Template
### Open Degree Framework | v0.1.0-draft | March 2026

> **What this template is for:**
> Use this template to manually assemble your CLR before submitting for badge issuance. Until automated tooling is available (see [`/tools/README.md`](../tools/README.md)), this document is the source of truth for your credential portfolio.
>
> When complete, submit via the GitHub issue queue with label `clr-submission` to initiate badge issuance and cryptographic signing.

---

## Learner Information

| Field | Value |
|---|---|
| **Learner Name** | [Full legal name] |
| **GitHub Handle** | @[handle] |
| **Email** | [Email for credential delivery] |
| **ODF Track** | [Track name] |
| **Framework Version** | ODF v0.1.0-draft |
| **Degree Plan File** | [Link to your degree plan file in this repo] |
| **Submission Date** | [Date] |

---

## Competency Badge Log

*Complete one row per competency domain. Every row must have a valid evidence URL before submission.*

### Core Foundations

| Competency | Tier | Completion Date | Evidence URL | Badge Hash (issued by ODF) |
|---|---|---|---|---|
| 5.1 Quantitative Reasoning & Data Literacy | — | — | — | — |
| 5.2 Written Communication & Argumentation | — | — | — | — |
| 5.3 Critical Thinking & Logic | — | — | — | — |
| 5.4 Ethics, Society & Technology | — | — | — | — |
| 5.5 Systems Thinking & Complexity | — | — | — | — |
| 5.6 Economic & Financial Literacy | — | — | — | — |

### Specialization Domains

| Competency | Tier | Completion Date | Evidence URL | Badge Hash (issued by ODF) |
|---|---|---|---|---|
| [Domain 1 name] | — | — | — | — |
| [Domain 2 name] | — | — | — | — |
| [Domain 3 name] | — | — | — | — |
| [Domain 4 name] | — | — | — | — |
| [Domain 5 name] | — | — | — | — |
| [Domain 6 name] | — | — | — | — |
| [Domain 7 name] | — | — | — | — |
| [Domain 8 name] | — | — | — | — |

### Elective Domains

| Competency | Tier | Completion Date | Evidence URL | Badge Hash (issued by ODF) |
|---|---|---|---|---|
| [Elective 1 name] | — | — | — | — |
| [Elective 2 name] | — | — | — | — |

---

## Capstone Credential

| Field | Value |
|---|---|
| **Capstone Title** | [Title of your capstone project] |
| **Capstone Type** | [Research / Product / Strategy / Technical / Portfolio Defense / Framework] |
| **Public URL** | [URL where capstone is publicly accessible] |
| **Domains Covered** | [List the competency domains your capstone draws on] |
| **Completion Date** | [Date submitted for peer review] |
| **Reviewer 1** | [GitHub handle] — reviewed [Date] |
| **Reviewer 2** | [GitHub handle] — reviewed [Date] |
| **Rubric Scores** | Competency Integration: [1–4] / Evidence of Learning: [1–4] / Public Accessibility: [1–4] / Written Reflection: [1–4] / Rigor: [1–4] |
| **Average Score** | [Average] (must be ≥ 3.0 with no dimension below 2) |
| **Badge Hash** | — (issued by ODF after verification) |

*Capstone rubric is defined in [FRAMEWORK.md §7](../FRAMEWORK.md#7-capstone-project).*

---

## Learner Narrative

*Write a 500-word statement contextualizing your full learning record. This becomes part of your CLR and is visible to any employer who reads your credential.*

**Guidance:**
- Describe your learning journey — where you started and where you are now
- Explain the choices you made: which track you chose and why, which electives and why, what your capstone demonstrates
- Contextualize your prior learning: what made your professional experience relevant evidence
- Be honest about gaps and how you addressed them
- End with where you're headed

---

[Your 500-word narrative here]

---

## Tier 3 PLA Evidence Checklist

*For each Tier 3 claim in your CLR, confirm the following before submitting.*

| Competency | Evidence Specific? | Evidence Dated? | Evidence Publicly Verifiable? | Reflection Written (300–500 words)? | Evidence URL Live? |
|---|---|---|---|---|---|
| [Competency name] | ☐ | ☐ | ☐ | ☐ | ☐ |
| [Competency name] | ☐ | ☐ | ☐ | ☐ | ☐ |

*All boxes must be checked before submission. Self-assertion without supporting documentation is not accepted.*

---

## CLR Submission Checklist

Complete all items before submitting your CLR for badge issuance.

**Completeness**
- [ ] All required Core Foundation competencies are logged with evidence URLs
- [ ] All required Specialization domain competencies are logged with evidence URLs
- [ ] Both elective competencies are logged with evidence URLs
- [ ] Capstone is publicly accessible at a working URL
- [ ] Capstone has been peer reviewed and passed (avg ≥ 3.0, no dimension below 2)
- [ ] Learner narrative is written (500 words minimum)

**Evidence Quality**
- [ ] All evidence URLs are live and publicly accessible
- [ ] All Tier 3 claims have written reflections (300–500 words each) in the degree plan
- [ ] No Tier 3 claims are self-assertion only (every claim has a checkable link or document)
- [ ] Tier 3 claims do not exceed 60% of total competencies
- [ ] At least 40% of competencies are Tier 1 or Tier 2

**Submission**
- [ ] Degree plan file is published in this repository (or linked from a public fork)
- [ ] CLR template is complete with all fields filled
- [ ] Submit GitHub issue with label `clr-submission`
- [ ] Include: learner name, GitHub handle, degree plan link, and CLR template link

---

## After Submission

After you submit your CLR:

1. **Verification review (up to 14 days):** Maintainers verify that evidence URLs are live, tier claims are appropriate, and the capstone has passed peer review.
2. **Badge issuance:** Upon verification, individual Open Badges are issued and badge hashes are added to your CLR table.
3. **CLR signing:** The full CLR is cryptographically signed under the ODF issuing key.
4. **Delivery:** Your signed CLR is delivered to you via the GitHub issue thread, in W3C Verifiable Credential format compatible with standard digital wallets.
5. **Verification URL:** Each badge is accessible at `odf.github.io/verify/[badge-hash]`.

---

## What Badge Recipients Receive

Each issued badge contains:

```
Badge Name:        [Competency Domain]
Issuer:            Open Degree Foundation
Earner:            [Your Full Name]
Issued:            [Date]
Criteria:          https://github.com/trentbigelow/open-degree-framework/blob/main/FRAMEWORK.md#[anchor]
Evidence:          [Your evidence URL]
Assessment Tier:   [1 / 2 / 3]
Framework Version: 0.1.0
Verify at:         odf.github.io/verify/[badge-hash]
```

The full CLR is issued as a W3C Verifiable Credential (JSON-LD) compatible with major digital wallet providers.

---

*Open Degree Framework — templates/clr_template.md*
*github.com/trentbigelow/open-degree-framework*
*Version 0.1.0-draft | March 2026 | CC BY 4.0*
