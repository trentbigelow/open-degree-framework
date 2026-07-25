# Contributing to the Open Degree Framework

> The ODF is CC BY 4.0 — open source by design. Your contributions make it better for every learner who comes after you.

---

## What We Need Most

| Contribution Type | Priority | How to Start |
|---|---|---|
| New specialization tracks | 🔴 High | Open an issue with label `new-track` |
| Course updates (links, new options) | 🔴 High | Open a PR with changes |
| Peer reviewers for capstones | 🔴 High | See [Becoming a Peer Reviewer](#becoming-a-peer-reviewer) |
| CLR/Open Badge generation tooling | 🟡 Medium | Open an issue with label `tooling` |
| Employer FAQ and outreach resources | 🟡 Medium | Open a PR or issue |
| Translations of the framework spec | 🟡 Medium | Open an issue with label `translation` |
| Typos, broken links, clarifications | 🟢 Always welcome | Open a PR |

---

## Table of Contents

1. [Ground Rules](#1-ground-rules)
2. [How to Propose a New Track](#2-how-to-propose-a-new-track)
3. [How to Update Course Recommendations](#3-how-to-update-course-recommendations)
4. [How to Propose a Framework Change](#4-how-to-propose-a-framework-change)
5. [Becoming a Peer Reviewer](#5-becoming-a-peer-reviewer)
6. [Style Guide](#6-style-guide)
7. [PR Review Process](#7-pr-review-process)

---

## 1. Ground Rules

**Be specific.** Vague proposals don't move. If you want to change something, show exactly what you'd change and why. Bring evidence, not just opinion.

**Be charitable.** This is a volunteer-maintained community project. Assume good faith. Critique ideas, not people.

**Be patient.** Maintainers review on their own time. Two-week response time is normal. If a PR hasn't been reviewed in 30 days, ping in the issue thread.

**Be accurate.** Don't suggest courses you haven't evaluated. Don't claim employer acceptance without sources. The framework's value depends on its trustworthiness.

**Represent yourself accurately.** If you're submitting a new track, identify your relevant expertise. If you're flagging a course as outdated, say how you know.

---

## 2. How to Propose a New Track

Specialization tracks are the highest-value contribution to the framework. A track defines a complete field of study for a specific audience.

### Step 1 — Open an Issue

Open a GitHub issue with the label `new-track`. Include:

- **Track name** — the field you want to define
- **Target audience** — who is this for? Be specific. "Everyone" is not an audience.
- **Draft competency list** — 8–12 competency domains you believe define this field
- **Why these domains** — brief rationale for the selection and scope
- **Your qualifications** — relevant professional experience, credentials, or domain expertise
- **Maintenance commitment** — tracks require ongoing course updates; confirm you'll maintain it

### Step 2 — Gather Feedback

The issue will remain open for community comment. Expect:
- Questions about domain selection
- Suggestions for alternative framing
- Requests to add or remove domains
- Questions about your maintenance capacity

Engage with comments in the issue thread. A track proposal that doesn't respond to feedback stalls.

### Step 3 — Get Approval to Draft

Two maintainer approvals are required before drafting begins. Approval means:
- The target audience is real and underserved
- The competency list is defensible
- The proposer has demonstrated domain knowledge
- There is a credible maintenance plan

### Step 4 — Draft the Track Spec

Use the `tracks/business-ai-product/track_spec.md` as the template. Every track spec must include:

1. Track overview — who it's for and what it prepares them to do
2. Competency map — all required + elective domains
3. For each domain: competency standard, "what competent looks like" examples, suggested courses (3+), assessment options (Tier 1/2/3), PLA examples
4. Track completion checklist
5. Document information block (version, date, maintainer, license)

### Step 5 — Submit as a PR

Submit the draft spec as a pull request to `/tracks/[track-slug]/track_spec.md`.

### Step 6 — Community Review

30-day community review period. Expect feedback on:
- Competency definitions — are they specific enough?
- Course recommendations — are they good, accessible, and current?
- Assessment options — are all tiers covered?
- PLA examples — are they reasonable?

### Step 7 — Merge

Merged on 2 maintainer approvals with no blocking objections.

---

## 3. How to Update Course Recommendations

The online course landscape changes fast. Courses go away. Better ones appear. Prices change. This is high-value, ongoing maintenance work.

**To update a course recommendation:**

1. Open a PR directly — no issue needed for routine updates
2. In the PR description, explain:
   - Which course you're adding/updating/removing
   - Why (course discontinued, better alternative found, price changed, etc.)
   - How you evaluated the replacement (did you take it? review the syllabus?)
3. One maintainer approval required for course updates

**Standards for suggesting a new course:**
- Must be from a named institution or credible creator
- Must include graded assessments (not video-only)
- Must offer a verifiable certificate
- Cost must be accurate at time of submission
- Hours must be a reasonable estimate (not the platform's inflated marketing figure)

---

## 4. How to Propose a Framework Change

Changes to competency standards, verification requirements, or assessment tiers require more process — they affect every existing learner.

### Minor Changes (Tier PATCH — corrections, clarifications)
- Open a PR with the change
- One maintainer approval required
- Examples: fixing a broken link, clarifying ambiguous wording, correcting a score requirement

### Moderate Changes (Tier MINOR — new options, backward-compatible)
- Open a GitHub issue with label `framework-change`
- 14-day comment period
- 2 maintainer approvals required
- Examples: adding a new assessment option, adding an accepted platform

### Major Changes (Tier MAJOR — breaking changes to competency standards)
- Open a GitHub issue with label `framework-change` and `major`
- 30-day community comment period
- 2 maintainer approvals required
- No blocking objections from active community members
- Examples: removing a core foundation domain, changing a tier definition, changing PLA percentage limits

---

## 5. Becoming a Peer Reviewer

Peer reviewers evaluate capstone projects submitted by ODF learners. This is meaningful work — your assessment contributes directly to a learner's credential.

**Eligibility:**
- 5+ years of relevant professional experience in the ODF track you'll review (or demonstrated academic expertise)
- Willingness to review 1–3 capstones per quarter on a volunteer basis
- Ability to provide structured, rubric-based feedback within 30 days of assignment

**How to apply:**
1. Open a GitHub issue with the label `volunteer-reviewer`
2. Include your professional background, the track(s) you can review, and 2–3 sentences on why you're qualified
3. A maintainer will follow up to complete onboarding

**What peer reviewers receive:**
- Credit as a named reviewer in each learner's CLR (permanent, public)
- Listing in the community reviewer directory
- Recognition in the annual ODF report

For full reviewer process details, see [`community/peer_reviewer_guide.md`](community/peer_reviewer_guide.md).

---

## 6. Style Guide

ODF documentation should feel like good product writing — clear, direct, concrete, and respectful of the reader's time.

**Do:**
- Use tables for structured comparisons, course lists, and options
- Use specific examples — name the course, the platform, the cost
- Write "what competent looks like" in concrete, observable terms
- Say what you mean in the first sentence, not the third
- Use numbered steps for processes with order-dependency

**Don't:**
- Use vague competency language ("understands the principles of...")
- List courses without hours and cost information
- Write multi-paragraph introductions before getting to the content
- Use jargon without defining it
- Add sections that exist for completeness rather than content

**Formatting:**
- Headers: Title Case for H2, Sentence case for H3 and below
- Tables: use for anything with 3+ rows of structured data
- Code blocks: use for any literal input/output (badge fields, CLI commands)
- Emphasis: **bold** for key terms on first use; avoid overuse
- Links: use relative paths within the repo (`../FRAMEWORK.md`); descriptive link text, not "click here"

---

## 7. PR Review Process

| Change Type | Approvals Needed | Comment Period |
|---|---|---|
| Typo, broken link, formatting | 1 maintainer | None |
| Course update | 1 maintainer | None |
| New elective or assessment option | 1 maintainer | None |
| New track spec | 2 maintainers | 30 days |
| Minor framework change | 2 maintainers | 14 days |
| Major framework change | 2 maintainers + no blocks | 30 days |

**What maintainers look for in a PR:**
- Does it match the style guide?
- Is the content accurate and specific?
- Are course recommendations verifiable?
- Does it maintain backward compatibility (for minor changes)?
- Does it follow the correct process for its change type?

**After you submit:**
- Expect initial response within 14 days
- If changes are requested, address them in the PR (don't open a new one)
- If a PR is inactive for 60 days with no response from the author, it may be closed

---

*Open Degree Framework — CONTRIBUTING.md*
*github.com/trentbigelow/open-degree-framework*
*CC BY 4.0 — Fork it. Build on it. Open source it back.*
