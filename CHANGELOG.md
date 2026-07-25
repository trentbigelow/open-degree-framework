# Changelog

All notable changes to the Open Degree Framework are documented here.

The ODF follows [Semantic Versioning](https://semver.org/): `MAJOR.MINOR.PATCH`

| Change Type | Version Bump | Example |
|---|---|---|
| Breaking change to competency standards | MAJOR | Removing a core foundation domain |
| New feature, backward compatible | MINOR | Adding a new assessment option or elective |
| Corrections, clarifications | PATCH | Fixing a broken course link, correcting a score |

Learner credentials reference the framework version active at the time of their completion. Completed credentials are not invalidated by subsequent framework changes.

---

## [Unreleased]

Changes in progress but not yet released. Will be tagged as `1.0.0` when ready for stable release (target: Q3 2026).

---

## [0.1.0-draft] — March 2026

### Added

**Core Framework**
- `FRAMEWORK.md` — Full ODF specification v0.1.0-draft including:
  - Framework philosophy and design principles
  - Degree structure and credit hour equivalence
  - Three-tier verification system (Tier 1: standardized exams, Tier 2: platform-verified courses, Tier 3: portfolio/PLA)
  - Prior Learning Assessment (PLA) rules, decision standards, and limits (max 60% Tier 3)
  - Six Core Foundation domains with competency standards, suggested courses, and assessment options:
    - 5.1 Quantitative Reasoning & Data Literacy
    - 5.2 Written Communication & Argumentation
    - 5.3 Critical Thinking & Logic
    - 5.4 Ethics, Society & Technology
    - 5.5 Systems Thinking & Complexity
    - 5.6 Economic & Financial Literacy
  - Specialization track structure and requirements
  - Capstone project requirements, accepted types, peer review process, and rubric
  - Comprehensive Learner Record (CLR) specification and badge structure
  - Governance and appeals process
  - Semantic versioning policy

**Business + AI Product Track**
- `tracks/business-ai-product/track_spec.md` — First specialization track spec Draft v0.1 including:
  - Track overview, audience, and outcomes
  - Eight required specialization domains with full competency standards, suggested courses, and assessment options:
    - Domain 1: Product Strategy & Roadmapping
    - Domain 2: AI/ML Product Design & Evaluation
    - Domain 3: Business Strategy & Competitive Analysis
    - Domain 4: Financial Analysis & Business Modeling
    - Domain 5: Data Analysis for Product Decisions
    - Domain 6: User Research & Product Discovery
    - Domain 7: Stakeholder Management & Cross-Functional Leadership
    - Domain 8: Go-to-Market Strategy & Product Launch
  - Four elective options (learner selects 2):
    - Elective A: Entrepreneurship & Venture Building
    - Elective B: B2B Sales & Revenue Operations
    - Elective C: Technical Architecture for Product Managers
    - Elective D: Growth & Retention Strategy
  - Track completion checklist

**Supporting Documentation**
- `README.md` — Project overview, track table, learner/employer/contributor onboarding
- `student-zero/trent_bigelow_degree_plan.md` — Student Zero live degree plan with PLA log
- `employers/employer_guide.md` — Employer guide for reading and verifying ODF credentials
- `templates/my_degree_plan_template.md` — Learner degree plan template
- `templates/clr_template.md` — CLR assembly template with submission checklist
- `community/peer_reviewer_guide.md` — Peer reviewer onboarding and process guide
- `CONTRIBUTING.md` — Contributor guide including track proposal process, course update process, and style guide
- `MAINTAINERS.md` — Current maintainer list and governance rules
- `tools/README.md` — Tooling roadmap and interim manual CLR process
- `LICENSE.md` — Creative Commons Attribution 4.0 International (CC BY 4.0)

**Planned track stubs** (not yet drafted, contributions welcome):
- `tracks/computer-science/track_spec.md`
- `tracks/data-science/track_spec.md`
- `tracks/design-ux/track_spec.md`
- `tracks/healthcare-admin/track_spec.md`
- `tracks/education/track_spec.md`

### Notes

This is the initial public release of the Open Degree Framework. Everything in `0.1.0-draft` is open for community review and subject to change before stable `1.0.0` release (target: Q3 2026).

Feedback via GitHub issues is welcome on any aspect of the framework.

---

## Version History Summary

| Version | Date | Status | Key Changes |
|---|---|---|---|
| 0.1.0-draft | March 2026 | Current | Initial framework release; Business + AI Product track; all supporting docs |
| 1.0.0 | Q3 2026 (target) | Planned | Stable release; tooling available; peer reviewer community active |

---

*Open Degree Framework — CHANGELOG.md*
*github.com/trentbigelow/open-degree-framework*
*CC BY 4.0*
