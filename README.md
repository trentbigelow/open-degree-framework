# 🎓 Open Degree Framework (ODF)

### A transparent, verifiable, self-directed alternative to the traditional undergraduate degree.

> **Built for the skills-based hiring era.**
> Designed by a dropout. Validated by a career. Open sourced for everyone.

[![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)
[![Version](https://img.shields.io/badge/version-0.1--draft-orange)]()
[![Student Zero](https://img.shields.io/badge/Student%20Zero-In%20Progress-blue)]()
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)]()

---

## The Problem

Forty-three million Americans started college and didn't finish.

Hundreds of millions more around the world have deep knowledge, real skills, and genuine capability — built through work, self-study, and lived experience — but no credential to show for it.

Meanwhile, the credential they're missing — a bachelor's degree — tells an employer almost nothing actionable:

- Which institution someone attended *(proxy for privilege, not capability)*
- Which courses they enrolled in *(not what they learned)*
- What grade they received *(17 years ago)*

**The degree isn't a measure of knowledge. It's a signal of completion. And completion is the wrong thing to optimize for.**

Employers know this. Apple, Google, IBM, Stripe, and hundreds of others have dropped degree requirements for significant portions of their roles. They're not lowering the bar — they're raising it from "which school did you attend" to "what can you actually do."

The problem is: **there's nothing transparent to replace it with.**

Until now.

---

## The Idea

What if your credential showed:

- Every competency you've mastered — specifically defined, not vaguely titled
- How each one was verified — standardized exam, proctored course, or documented portfolio
- Direct links to the evidence — certificates, transcripts, work products, published writing
- A cryptographic proof — so it can't be faked and can be verified in seconds

What if prior learning from *any source* counted — college courses, work experience, professional certifications, self-directed study — as long as the evidence was there?

What if the whole thing were **open source**, so anyone could use it, fork it, build their own track, and contribute back?

That's the Open Degree Framework.

---

## What It Is

The ODF is three things:

**1. A curriculum specification**
A structured set of competency domains — core foundations that every track shares, plus specialization tracks for specific fields. Each competency has a clear standard, suggested courses, and defined assessment options.

**2. A verification framework**
Three tiers of evidence — standardized exams (CLEP/DSST), platform-verified courses (Coursera/edX), and portfolio/prior learning documentation — that map real learning to real proof.

**3. A credentialing layer**
Built on open standards (W3C Verifiable Credentials, Open Badges 3.0, Comprehensive Learner Record 2.0) so every competency generates a cryptographically signed, employer-verifiable badge — and the full portfolio assembles into a Comprehensive Learner Record that travels with you anywhere.

---

## What It Is Not

- ❌ An accredited degree (no accreditation is claimed or implied)
- ❌ A shortcut (the rigor is equivalent to or greater than a traditional undergraduate program)
- ❌ A deception (candidates represent it as an ODF credential — transparent by design)
- ❌ Another MOOC platform (it's a framework, not a course provider)

---

## Repository Contents

```
/
├── README.md                          ← You are here
├── FRAMEWORK.md                       ← Full ODF specification
│   ├── Core Foundations (6 domains)
│   ├── Specialization Tracks
│   ├── Verification Tiers
│   └── Capstone Requirements
│
├── tracks/
│   └── business-ai-product/           ← First specialization track
│       └── track_spec.md
│
├── templates/
│   └── my_degree_plan_template.md     ← Fill this in to start
│
├── student-zero/
│   └── trent_bigelow_degree_plan.md   ← Live example, updated monthly
│
├── employers/
│   └── employer_guide.md              ← How to read and evaluate an ODF credential
│
├── tools/                             ← CLR/Open Badge generation (coming soon)
│   └── README.md
│
├── community/
│   └── peer_reviewer_guide.md         ← How to become a peer reviewer
│
├── CONTRIBUTING.md                    ← How to contribute
└── LICENSE                            ← CC BY 4.0
```

---

## Available Tracks

| Track | Status | Domains | Maintainer |
|---|---|---|---|
| **Business + AI Product** | 🟡 Draft v0.1 | 8 + 2 electives | @trentbigelow |
| Computer Science | 🔜 Planned | — | Contribute? |
| Design & UX | 🔜 Planned | — | Contribute? |
| Healthcare Administration | 🔜 Planned | — | Contribute? |
| Data Science | 🔜 Planned | — | Contribute? |
| Education | 🔜 Planned | — | Contribute? |

**Want to build a track?** Open an issue. We'll help you spec it.

---

## How It Works

### For Learners

```
1. Fork this repo
2. Copy templates/my_degree_plan_template.md
3. Map your prior learning to competency domains
4. Identify gaps → select courses to fill them
5. Complete assessments → log evidence with links
6. Submit capstone for peer review
7. Generate your Comprehensive Learner Record
8. Share it with employers
```

**Cost:** $500–$1,000 for most learners (primarily CLEP exams + verified course certificates)
**Time:** 6 months–2 years depending on prior learning credit
**Prior learning:** Up to 60% of competencies may be satisfied through Tier 3 evidence

### For Employers

Read [`employers/employer_guide.md`](employers/employer_guide.md) for a full walkthrough.

**Short version:** Every credential links to original evidence. Every badge is cryptographically signed. Verify any credential in seconds at `odf.github.io/verify/[hash]`. The interview is richer because there's something real to discuss.

### For Contributors

Read [`CONTRIBUTING.md`](CONTRIBUTING.md).

The most needed contributions right now:
- [ ] New specialization tracks (see table above)
- [ ] Tools for CLR/Open Badge generation
- [ ] Peer reviewer community and onboarding flow
- [ ] Employer FAQ and outreach resources
- [ ] Translations of the framework spec
- [ ] Course updates (online course landscape changes fast)

---

## The Verification Stack

ODF credentials are built on standards already being adopted by major universities and employers:

| Standard | What It Does | Maintained By |
|---|---|---|
| **W3C Verifiable Credentials** | Cryptographic proof layer | W3C (web standards body) |
| **Open Badges 3.0** | Per-competency signed badges | 1EdTech Consortium |
| **Comprehensive Learner Record (CLR 2.0)** | Full portfolio record | 1EdTech / AACRAO |
| **CTDL** | Credential metadata and searchability | Credential Engine |

An ODF credential can be verified by any employer using standard tooling. It can be stored in any W3C-compatible digital wallet. It travels with the learner — not locked to any platform.

---

## The Prior Learning Philosophy

Every person has learned from multiple sources. A framework that only counts formal courses ignores reality.

ODF accepts three tiers of evidence:

**Tier 1 — Standardized External Exam**
CLEP, DSST, AP, or equivalent proctored assessments. Same exams that earn college credit at 2,900+ accredited institutions. Cost: ~$90/exam.

**Tier 2 — Platform-Verified Course Completion**
Coursera, edX, Udacity, or equivalent verified certificates with identity verification and proctored assessments. Cost: $0–$100/certificate (financial aid available).

**Tier 3 — Portfolio & Prior Learning Documentation**
Prior college transcripts, professional work products, published writing, shipped products, peer-reviewed capstone projects. For experienced professionals, this often covers the majority of competencies.

> *A founded-and-exited startup satisfies the entrepreneurship competency with evidence no classroom exercise can match. A shipped AI product satisfies the AI product design competency better than any exam. Prior learning should be credited when the evidence is real.*

---

## Student Zero

This framework was built by someone using it.

**Trent Bigelow** is a Senior Lead Product Manager at BILL leading AI product strategy. He left USC in 2008 with 80 credits to found a VC-backed startup — which he scaled and exited. He has never finished his undergraduate degree.

He is completing the ODF's Business + AI Product track publicly — mapping 15+ years of professional experience against the competency framework, filling verified gaps with targeted coursework, and documenting every step.

**Not to get the credential. To prove the concept.**

If a hiring manager at any serious company would look at his Comprehensive Learner Record and say "this tells me more than a USC diploma would have" — then the framework works.

Follow the Student Zero journey: [`student-zero/trent_bigelow_degree_plan.md`](student-zero/trent_bigelow_degree_plan.md)

---

## Core Beliefs

These aren't marketing copy. They're the principles that constrain every design decision in this framework.

**1. Transparency beats credentialism.**
A detailed, verified list of competencies tells an employer more than a diploma from a brand-name institution. The name on the building is not the education.

**2. Prior learning has value.**
What you learned building a company is real. What you learned leading a team is real. What you learned through self-directed study is real. A framework that ignores this is broken.

**3. Evidence is the credential.**
Not completion. Not enrollment. Not tuition paid. The credential is the evidence that you know what you say you know — and the evidence should be checkable.

**4. Open source or it doesn't scale.**
No single organization should own the standard for how humans represent their learning. This framework is CC BY 4.0. Fork it, adapt it, improve it, and open source it back.

**5. The goal is more signal, not less accountability.**
This is not about making credentials easier to obtain. It's about making them more honest. The verification requirements are strict. The prior learning standards require real evidence. The capstone is evaluated by independent reviewers.

---

## Frequently Asked Questions

**Will employers accept this?**
Some will, some won't — yet. The framework is designed for the growing number of employers who have removed degree requirements and evaluate candidates on demonstrated skills. It is also designed to be legible to any employer willing to engage with what it actually shows. The employer guide gives hiring teams everything they need to evaluate it fairly.

**Is this legal?**
Yes. There is no law requiring you to have a degree unless your profession requires a licensed credential (medicine, law, engineering stamps, etc.). There is no law preventing you from creating or using a competency-based learning record. Candidates represent it accurately as an "ODF Verified Credential" — not a degree.

**How is this different from just listing courses on LinkedIn?**
Verification. Each credential is cryptographically signed, linked to original evidence, and independently checkable in seconds. A LinkedIn profile is self-reported. An ODF credential is verified.

**What about graduate school?**
Some graduate programs are beginning to accept non-traditional credentials. ODF is not designed as a graduate school pathway — it's designed for employment. That said, a strong ODF record with a compelling capstone may be compelling to forward-thinking programs, particularly in professional fields.

**Can I use my existing college credits?**
Yes. Prior college credits from any regionally accredited institution satisfy competencies at Tier 3. They are logged with your official transcript as evidence.

**Who governs the framework?**
Currently: the maintainers of this repository, operating under CC BY 4.0. Long-term: an independent Open Degree Foundation with a community governance model. If you want to help build that, open an issue.

**What if I think a competency standard is wrong?**
Open an issue and make the argument. This is a living framework. Pull requests for curriculum improvements are welcome and reviewed by maintainers.

---

## Roadmap

| Milestone | Status | Target |
|---|---|---|
| Framework spec v0.1 published | ✅ Done | Q1 2026 |
| Business + AI Product track published | ✅ Done | Q1 2026 |
| Student Zero degree plan published | ✅ Done | Q1 2026 |
| Employer guide published | ✅ Done | Q1 2026 |
| CLR/Open Badge generation tooling | 🔜 Planned | Q3 2026 |
| Peer reviewer community launch | 🔜 Planned | Q3 2026 |
| Second specialization track | 🔜 Planned | Q4 2026 |
| Student Zero credential issued | 🔜 Planned | Q1 2027 |
| First cohort of ODF graduates | 🔜 Planned | 2027 |
| Open Degree Foundation (org) | 🔜 Planned | 2027 |
| Employer adoption program | 🔜 Planned | 2027 |

---

## Get Started

**I want to complete an ODF credential:**
→ Read [`FRAMEWORK.md`](FRAMEWORK.md)
→ Copy [`templates/my_degree_plan_template.md`](templates/my_degree_plan_template.md)
→ Open an issue to introduce yourself

**I want to contribute a track or improvement:**
→ Read [`CONTRIBUTING.md`](CONTRIBUTING.md)
→ Open an issue with your proposal

**I'm an employer who wants to understand this:**
→ Read [`employers/employer_guide.md`](employers/employer_guide.md)
→ Email [contact] with questions or feedback

**I want to follow the Student Zero journey:**
→ [`student-zero/trent_bigelow_degree_plan.md`](student-zero/trent_bigelow_degree_plan.md)
→ [Blog / newsletter link]

---

## License

Released under [Creative Commons Attribution 4.0 International (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/).

**You are free to:**
- Share — copy and redistribute in any medium or format
- Adapt — remix, transform, and build upon for any purpose, including commercial

**Under one condition:**
- Attribution — credit the Open Degree Framework and link back to this repository

Fork it. Build your own track. Open source it back.

---

## A Final Note

The university system produced extraordinary things. It also became expensive, exclusionary, slow to adapt, and increasingly disconnected from the skills the world actually needs.

This isn't an attack on universities. It's an acknowledgment that they were never the only place learning happened — and that the credential layer built around them has become a barrier rather than a bridge.

Forty-three million people in the United States alone started college and stopped. Most of them kept learning. Most of them kept building. Most of them have real skills and no way to prove it that the hiring system will recognize.

This framework is for them.

And for the hiring managers who know that the best person for the job isn't always the one with the right stamp on their diploma — they just need something better to look at instead.

**That's what this is.**

---

*Open Degree Framework — github.com/[your-org]/open-degree-framework*
*Started: March 2026 | Maintained by the community | CC BY 4.0*

*"The credential is the evidence. The evidence should be checkable."*
