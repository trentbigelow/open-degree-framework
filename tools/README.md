# Tools — CLR and Open Badge Generation
### Open Degree Framework | Status: 🔜 Coming Q3 2026

> This directory will contain tooling for generating, signing, and verifying ODF Comprehensive Learner Records (CLRs) and Open Badges.

---

## Status

**Automated tooling is not yet available.**

Target release: Q3 2026, alongside the `1.0.0` stable framework release.

---

## What Will Be Here

| Tool | Description | Status |
|---|---|---|
| CLR generator | Assembles a CLR from a filled degree plan and evidence log | 🔜 Planned |
| Open Badge issuer | Issues cryptographically signed Open Badges 3.0 per competency | 🔜 Planned |
| Badge verifier | Verifies an ODF badge hash against the issuing key | 🔜 Planned |
| Credential wallet export | Exports the full CLR as a W3C Verifiable Credential for digital wallets | 🔜 Planned |

---

## In the Meantime

Until tooling is available, CLR assembly is manual. Use the template and submission process:

1. **Assemble your CLR** using [`/templates/clr_template.md`](../templates/clr_template.md)
2. **Submit for badge issuance** by opening a GitHub issue with label `clr-submission`
3. **Maintainers will verify** your evidence and issue badges manually
4. **Your signed CLR** will be delivered via the issue thread

---

## Want to Build This?

This is a high-priority contribution opportunity. If you have experience with:
- Open Badges 3.0 (1EdTech standard)
- W3C Verifiable Credentials and DIDs
- CLR 2.0 (1EdTech/AACRAO standard)
- Cryptographic signing (Ed25519, JWS)

...we want to hear from you. Open a GitHub issue with the label `tooling` and describe what you'd build and how.

**Starting resources:**
- [Open Badges 3.0 Specification](https://www.imsglobal.org/spec/ob/v3p0/)
- [W3C Verifiable Credentials Data Model](https://www.w3.org/TR/vc-data-model/)
- [CLR 2.0 Specification](https://www.imsglobal.org/spec/clr/v2p0/)
- [Credential Engine CTDL](https://credentialengine.org/credential-transparency/ctdl/)

---

*Open Degree Framework — tools/README.md*
*github.com/trentbigelow/open-degree-framework*
*CC BY 4.0*
