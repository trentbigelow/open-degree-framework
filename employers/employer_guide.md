# Employer Guide — How to Read and Evaluate an ODF Credential
### Open Degree Framework | Version 0.1.0-draft | March 2026

> **For hiring teams, recruiters, and hiring managers** who want to understand what an ODF credential shows, how it compares to a traditional degree, and how to verify one in seconds.

---

## Table of Contents

1. [What an ODF Credential Is](#1-what-an-odf-credential-is)
2. [What It Is Not](#2-what-it-is-not)
3. [What the Credential Contains](#3-what-the-credential-contains)
4. [How to Verify It](#4-how-to-verify-it)
5. [What It Tells You vs. a Traditional Degree](#5-what-it-tells-you-vs-a-traditional-degree)
6. [Using the Credential in an Interview](#6-using-the-credential-in-an-interview)
7. [Frequently Asked Questions](#7-frequently-asked-questions)
8. [Contact](#8-contact)

---

## 1. What an ODF Credential Is

An ODF (Open Degree Framework) credential is a verifiable, competency-based learning record built on the same open standards used by major universities, employers, and the US military.

It consists of:

- **A Comprehensive Learner Record (CLR)** — the full portfolio, assembled from all individual credentials
- **Per-competency Open Badges** — one cryptographically signed badge per competency domain completed
- **A Capstone credential** — a signed badge for a peer-reviewed, publicly accessible integrative project
- **A Learner Narrative** — a self-authored statement contextualizing the full record

Every competency was verified through one of three tiers:

| Tier | What It Is | Example |
|---|---|---|
| **Tier 1** | Standardized external exam — independently proctored | CLEP, DSST, AP, AWS certification |
| **Tier 2** | Platform-verified course completion with graded assessments | Verified Coursera or edX certificate |
| **Tier 3** | Portfolio and prior learning documentation with written reflection | Prior college transcript, professional work product, or shipped product |

Every badge is cryptographically signed and links directly to the original evidence. Nothing is self-reported without documentation.

---

## 2. What It Is Not

It is important to be clear about what an ODF credential does not claim to be.

| It Is NOT | Why This Matters |
|---|---|
| An accredited degree | No accreditation is claimed or implied. Candidates represent it accurately as an "ODF Verified Credential." |
| A shortcut | The competency standards are equivalent to or stricter than a traditional undergraduate curriculum in the relevant domain. |
| A fabrication | Every credential is cryptographically signed and links to third-party-verifiable evidence. |
| Locked to a platform | The credential follows open standards and lives in the learner's digital wallet — not on ODF servers. |
| A guarantee of job performance | Like any credential, it is evidence — not a prediction. Use it as one input, not the only input. |

If a candidate represents an ODF credential as equivalent to an accredited degree, that is a misrepresentation and should be treated as a disqualifying integrity issue.

---

## 3. What the Credential Contains

### The Comprehensive Learner Record (CLR)

The CLR is a structured portfolio containing:

1. **Learner identification** — name, date of issue, framework version
2. **Core Foundation competencies** — 6 domains required of all ODF graduates
3. **Specialization competencies** — domain-specific competencies for the chosen track (e.g., Business + AI Product)
4. **Elective competencies** — chosen from a defined list within the track
5. **Capstone project** — public URL, peer reviewer names and dates, rubric scores
6. **Learner narrative** — 500-word self-authored context statement

### What Each Open Badge Contains

Every individual competency badge includes:

```
Badge Name:        [Competency Domain]
Issuer:            Open Degree Foundation
Earner:            [Learner Name]
Issued:            [Date]
Criteria:          [Link to FRAMEWORK.md competency standard]
Evidence:          [Direct link to certificate, transcript, or portfolio artifact]
Assessment Tier:   [1 / 2 / 3]
Framework Version: [0.1.0]
Cryptographic Proof: [W3C VC signature]
Verify at:         odf.github.io/verify/[badge-hash]
```

Every evidence link in a Tier 3 badge is accompanied by a 300–500 word written reflection explaining how the evidence maps to the specific competency standard. Reviewers can evaluate whether the claim is reasonable.

### The Capstone Project

The capstone is a required, public, peer-reviewed integrative project. It must:

- Be publicly accessible at a URL
- Draw on at least 3 competency domains
- Represent a minimum of 20 hours of documented effort
- Be evaluated by 2 independent ODF community reviewers
- Include a written reflection on what was learned and how it connects to the framework

The capstone credential includes the reviewers' names and their rubric scores. It is the closest analog to a thesis or senior project in a traditional program.

---

## 4. How to Verify It

### Step 1 — Request the CLR

Ask the candidate to share their Comprehensive Learner Record. It may be shared as:
- A URL to their credential wallet
- A PDF export of the CLR
- A GitHub link to their degree plan file (for public learners)

### Step 2 — Verify Any Badge

Every badge has a unique hash. To verify:

```
Go to: odf.github.io/verify/[badge-hash]
```

Verification confirms:
- The credential is authentic (not modified or fabricated)
- The issuer is the Open Degree Foundation
- The earner name matches the credential holder
- The issue date is accurate
- All linked evidence is live and accessible

This takes approximately 30 seconds per badge.

### Step 3 — Spot-Check the Evidence

For Tier 1 and Tier 2 badges: the evidence link goes directly to the issuing platform (CLEP score report, Coursera certificate page, etc.). These can be verified independently.

For Tier 3 badges: the evidence link goes to the original artifact (document, GitHub repo, published article, etc.) along with the learner's written reflection. Review the reflection to evaluate whether the mapping to the competency is reasonable.

### Step 4 — Review the Capstone

The capstone is public by requirement. Read it. Review the rubric scores. The competency domains it covers are identified — evaluate whether the project demonstrates them.

### Verification Standards

| Credential Component | Verification Method | Time Required |
|---|---|---|
| Badge authenticity | odf.github.io/verify/ | 30 seconds |
| Tier 1 evidence | Exam score report URL | 1 minute |
| Tier 2 evidence | Course certificate URL | 30 seconds |
| Tier 3 evidence | Artifact URL + reflection review | 3–5 minutes |
| Capstone | Public URL + rubric scores | 10–15 minutes |

---

## 5. What It Tells You vs. a Traditional Degree

### The Traditional Degree

A bachelor's degree from an accredited institution tells an employer:

- The institution the candidate attended
- The major they declared
- That they completed enough courses to graduate
- (Sometimes) their GPA

It does not tell you:
- What they actually learned
- How current their knowledge is
- Whether they can apply what they studied
- What specific skills they have beyond the major

### The ODF Credential

An ODF credential tells an employer:

- Every specific competency domain the candidate has demonstrated
- The exact standard each competency was measured against (linked)
- How each competency was verified — and at what tier
- Direct links to the original evidence
- What the candidate built for their capstone — and how two independent reviewers scored it
- A self-authored narrative giving context for the full record

### Side-by-Side Comparison

| What You Want to Know | Traditional Degree | ODF Credential |
|---|---|---|
| Can they write clearly? | Maybe (major-dependent) | Yes — Written Communication is a required Core Foundation with documented evidence |
| Do they understand data? | Maybe (major-dependent) | Yes — Quantitative Reasoning and Data Analysis are both tracked with evidence |
| Have they built something real? | Unknown | Yes — capstone project is public, peer-reviewed, and linked |
| Is their knowledge current? | Unknown | Yes — courses completed are dated; framework version is tracked |
| Can I verify any of this? | Rarely (transcript only) | Yes — every badge is cryptographically signed and evidence is linked |
| What did they specifically learn in their specialty? | Inferred from major name | Explicitly documented per-competency with evidence |

---

## 6. Using the Credential in an Interview

The ODF credential gives you specific, concrete material for an interview that a traditional degree typically cannot provide.

### Suggested Questions by Competency Area

**Product Strategy (Domain 1)**
- "Your CLR shows a portfolio roadmap artifact — can you walk me through the prioritization decisions you made and why?"
- "What was the hardest stakeholder tradeoff you navigated in that project?"

**AI/ML Product Design (Domain 2)**
- "Your capstone involves an AI feature. How did you design for the failure mode where the model gets it wrong?"
- "What would you do differently if you were rebuilding that feature today?"

**Financial Analysis (Domain 4)**
- "You claimed the financial modeling competency through P&L ownership. What was the most important assumption in your model and how did you validate it?"

**Capstone**
- "I read your capstone. The reviewers gave you a 3 on 'Competency integration' and a 4 on 'Rigor.' How do you account for that difference?"
- "What would a version 2 of this project look like?"

### What the Credential Is Not

The credential is evidence of demonstrated learning — it is not a guarantee of job performance. Use it as one strong signal among others. The best interviews combine credential review with structured problem-solving, work sample exercises, and reference checks.

---

## 7. Frequently Asked Questions

**Is this legal?**
Yes. There is no law requiring employees to have accredited degrees (unless the role requires a professional license — medicine, law, licensed engineering, etc.). There is no law preventing a person from creating or using a competency-based learning record. Candidates represent ODF credentials accurately as "ODF Verified Credentials" — not as accredited degrees.

**Can I trust the evidence links?**
The links point directly to the issuing platforms (Coursera, CLEP, etc.) or to original public artifacts. The cryptographic signature on each badge ensures that the evidence was linked at issuance and has not been modified since. If a Tier 3 artifact is redacted (common for professional work products), the reflection should explain what was redacted and why.

**What if an evidence link goes dead?**
Evidence link maintenance is the learner's responsibility. A dead link to a course certificate should be flagged as a concern and the candidate asked to provide an updated URL or alternative documentation. A pattern of dead links without explanation is a yellow flag.

**Who are the peer reviewers for the capstone?**
ODF peer reviewers are community members with 5+ years of relevant professional experience in the domain. Reviewer credentials are listed alongside capstone scores in the CLR. You can research the reviewers independently. Over time, the community will develop a track record that contextualizes reviewer standards.

**What if I disagree with how a Tier 3 claim was assessed?**
Tier 3 claims are self-assessed and documented — the learner is making a case, not having someone else vouch for them. Your job as an interviewer is to probe the claim. The reflection and evidence are the starting point, not the verdict.

**Is this the same as a college degree for purposes of degree verification services?**
No. Standard degree verification services (National Student Clearinghouse, etc.) verify accredited institution completion. An ODF credential will not appear there. If your company's ATS or background check requires an accredited degree, that is a separate policy question your team should evaluate. An increasing number of employers — including Apple, Google, IBM, Stripe, and hundreds of others — have removed degree requirements for significant roles.

**What about candidates who claim an ODF credential but it can't be verified?**
Treat it the same way you would treat any unverifiable credential: request documentation, run the verification steps in Section 4, and if the credential cannot be verified, do not credit it. Fabricating an ODF credential is no different than fabricating any other credential — it is a disqualifying integrity issue.

---

## 8. Contact

For questions about the ODF framework, verification issues, or employer partnerships:

- **GitHub Issues:** Open an issue at `github.com/trentbigelow/open-degree-framework`
- **Label your issue:** `employer-inquiry`

For verification disputes or concerns about a specific credential:

- **Label your issue:** `verification-dispute`
- **Include:** The candidate name, the badge hash(es) in question, and what you observed

---

*Open Degree Framework — employers/employer_guide.md*
*github.com/trentbigelow/open-degree-framework*
*Version 0.1.0-draft | March 2026 | CC BY 4.0*
