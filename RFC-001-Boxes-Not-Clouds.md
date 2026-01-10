# RFC 0001: Boxes Not Clouds
## A Specification for Legible Cyberinfrastructure

Status: Proposed
Category: Informational / Normative Guidance
Author: [Maintainer or Working Group]
Created: 2026-01-05
Last-Updated: 2026-01-05
Supersedes: None

---

## Abstract

This document specifies normative principles for the design, representation, and governance of cyberinfrastructure. It requires that services be described as bounded, inspectable systems (“boxes”) rather than mythic or anthropomorphic abstractions (“clouds”). The goal is legibility, accountability, portability, and democratic contestability.

---

## 1. Terminology

The key words **MUST**, **MUST NOT**, **SHOULD**, **SHOULD NOT**, and **MAY** are to be interpreted as described in RFC 2119.

- **Service**: Any hosted computational offering accessed remotely.
- **Provider**: The entity operating or controlling a service.
- **User**: Any individual or institution relying on a service.
- **Critical Infrastructure**: Systems materially affecting rights, safety, or life chances.
- **Legibility**: The ability for non-specialists to understand system structure, limits, and governance at a human-readable level.

---

## 2. Grounded Descriptions

Providers **MUST** describe services as engineered systems, including:
- Hardware and software layers
- Operators and control boundaries
- Explicit constraints and limits

Providers **MUST NOT** represent services as sentient, boundless, or autonomous beyond documented capabilities.

Capability claims **MUST** reference measurable specifications (e.g., SLAs, error bounds, quotas).

---

## 3. Concrete Accountability

Providers **MUST** disclose physical, legal, and operational realities in layered formats:
- A concise summary (location, ownership, jurisdiction)
- Expandable technical documentation

Providers **MUST** publish end-to-end data flow mappings and update them quarterly or upon material change.

---

## 4. Contracts, Not Vibes

User interfaces, marketing, and onboarding **MUST NOT** contradict formal contractual terms or technical limits.

Claims of security, privacy, or anonymity **MUST** be supported by auditable guarantees or **MUST NOT** be used.

---

## 5. Failure Disclosure

Providers **MUST** report outages, breaches, and model failures with:
- Cause
- Scope
- Impact
- Remediation

For critical infrastructure, postmortems **SHOULD** be public by default.

---

## 6. Legible Architectures

Providers **MUST** expose, at a human-readable level:
- Storage components
- Compute components
- Models or decision engines
- Key dependencies

Dark patterns that conceal data sharing, updates, or monetization **MUST NOT** be used.

---

## 7. Data Dignity

Secondary use of data **MUST NOT** occur without informed, revocable consent.

Claims of anonymization **MUST** acknowledge re-identification risk and mitigations.

---

## 8. Honest Intelligence Claims

Systems marketed as “AI” or “autonomous” **MUST** disclose:
- Capabilities and limits
- Training and update regimes
- Known failure modes

Anthropomorphic interfaces **SHOULD NOT** be used in infrastructure contexts unless clearly labeled.

---

## 9. Portability

Providers **MUST** offer export of data and configurations in open, documented formats.

Services that prevent practical exit constitute enclosures and **MUST NOT** present themselves as neutral infrastructure.

---

## 10. Observability and Contestation

Systems affecting credit, employment, health, housing, education, or law **MUST** permit inspection, explanation, and contestation.

Black-box systems without recourse violate democratic norms.

---

## 11. Metaphor Constraints

Metaphors **MAY** be used only when they clarify ownership, limits, and risk.

Metaphors that obscure control or responsibility **MUST NOT** be used.

---

## 12. Governance

Legibility **REQUIRES** institutional enforcement beyond individual consent, including:
- Independent auditors
- Standards bodies
- Worker councils
- Civil society
- Regulators

---

## 13. Revision Policy

This specification **MAY** be revised based on:
- Architectural change
- Empirical evidence
- Stakeholder feedback

All revisions **MUST** be logged publicly.

---

## 14. Security Considerations

Opacity, anthropomorphism, and forced captivity increase systemic risk by inducing over-trust and inhibiting exit. Compliance with this specification reduces these risks.

---

## 15. IANA Considerations

This document has no IANA considerations.

---

## 16. Pledge (Non-Normative)

We describe systems in terms that survive audit, regulation, and negotiation. If poetry fails under specificity, we revise the poetry or the product.

---

## 17. References (Informative)

See repository SOURCES.md.
