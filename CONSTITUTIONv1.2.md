# The MIR Constitution

*A public statement of principles*

**Version 1.2**
First published: December 21, 2025
Last modified: May 2, 2026

---

MIR (Memory Infrastructure Registry) is built on a simple idea:

**Participation history should be able to move with people -- without exposing who they are.**

This document explains the principles that guide how MIR is designed, operated, and protected over time.

---

## Our Purpose

*MIR exists to restore continuity to the internet.*

When people move between platforms, their history usually resets to zero. MIR provides a neutral way for platforms to learn whether a participant has existing history elsewhere, without revealing identity or personal details.

> MIR answers one question only:
> **Does this participant have history elsewhere?**

It does not answer who someone is, why they act, or what should be done about them.

---

## What MIR Is -- and Is Not

*MIR is a portable participation history layer.*

MIR is not:

- A trust score
- A credit score
- A fraud detection system
- An identity provider
- A profiling or surveillance tool
- A decision engine

**MIR provides context, not conclusions.**
Decisions always remain with the platforms that use it.

---

## Two Modes, One Architecture

MIR operates in two complementary modes:

### Marketplace mode

People carry their participation history across platforms. Linking is voluntary; users choose which platforms can access their history. Cross-platform tier requires partner diversity -- multiple partners contributing events for the same linked entity.

### Enterprise mode

Organizations record participation history for the entities they are responsible for: employees, contractors, AI agents, service accounts, and other internal systems. Recording is operationally mandatory because the organization carries the accountability for those entities. Subject-level data stays within the organization's scope.

Both modes share the same architecture: deterministic tier calculations, hashed external identifiers, claim-attribution rules, and the constitutional commitments below. The principles apply equally to both. What differs is who is doing the recording and on whose behalf.

Within enterprise mode, an exception applies: religious organizations, charities, and similar institutions where membership is voluntary may use a participation-optional configuration that preserves an individual's right to decline participation while remaining a member.

---

## Neutrality by Design

Neutrality is not a marketing position -- it is a design constraint.

MIR is intentionally:

- **Non-judgmental**
- **Non-authoritative**
- **Non-competitive**
- **Non-extractive**

MIR does not rate, rank, or label people.
It exists to preserve history without ownership.

---

## Privacy First, Always

*MIR is built to minimize data exposure.*

- MIR does not expose subject-level identity across organizational boundaries; partner-submitted external identifiers are SHA-256 hashed before storage
- MIR does not share subject-level personal details between platforms or between enterprise organizations; in enterprise mode, an organization's entity data stays within that organization's scope
- MIR does not record behavior outside of explicitly submitted participation events
- MIR does hold operational personal data: email addresses for account holders who log in to MIR (used for authentication and account notifications) and partner administrative contacts (used for billing and account management). These are governed by the Data Processing Agreement.

In marketplace mode, users choose whether to link their participation history across platforms.
**Voluntary linking is fundamental to how MIR works in marketplace mode. Enterprise mode operates under organizational accountability for the entities being recorded.**

---

## History, Not Judgment

*MIR history indicates presence of participation, not quality or character.*

History tiers (0, 1, 2, 3) describe how much history exists -- not whether someone is good, bad, trusted, or risky.

> Silence (no history) is not guilt.
> History is context, not destiny.

---

## Platform Autonomy

*MIR does not tell platforms what to do.*

Each platform decides:

- How to interpret MIR signals
- When to use them
- What actions, if any, to take

MIR provides shared context while respecting local rules, policies, and values.

---

## Growth With Care

*MIR is designed to grow slowly and deliberately.*

Correct use matters more than rapid adoption.
A small number of aligned partners is better than broad misuse.

**Trust compounds over time.**

---

## What MIR Will Never Do

*These are structural commitments, not aspirations.*

MIR will never:

- **Interpret what continuity means.** The moment MIR implies "extensive = safe" or "none = risky," it becomes a classifier, not a recorder.
- **Provide recommended thresholds or decision rules.** If MIR ships "deny if tier < X" templates, it effectively decides outcomes. Platforms must make their own policies.
- **Aggregate claims into scores.** Any single-number summary becomes the identity. If there's one number that's easiest to use, that's what everyone will use. MIR refuses to provide it.
- **Become an enforcement oracle.** MIR will never participate in punishment ("block this user everywhere"). Platforms enforce; MIR remembers.
- **Use virtue language for tiers.** Terms like "trusted," "verified," "good standing," or "suspicious" turn tiers into character judgments. Tiers describe event counts, not moral status.
- **Record judgments as facts.** When a platform asserts "this user violated policy," MIR may record that the assertion exists -- but never that it's true. Claims are attributed, not endorsed.
- **Build profiles.** MIR has no bios, no badges, no place to present yourself. The moment users can perform identity, optimization pressure appears. MIR stays boring.
- **Feed performance management, compensation, hiring, or termination directly.** In enterprise mode, MIR records what entities have done. It does not generate recommendations about whether a person should be promoted, paid more, hired, or terminated. The behavioral record is operational evidence. It is not a performance signal.
- **Leak data across organizational boundaries.** In enterprise mode, an organization's entity data does not become visible to other organizations through MIR. Cross-organizational visibility exists only when entities are explicitly linked across organizational boundaries -- typically for humans and service agents that move across institutions.

> **The test:** If a partner asks "What should we do with Tier X?" the answer must always be: "That's your policy. MIR doesn't decide outcomes."

---

## An Explicit Boundary

*MIR is voluntary.*

> **If MIR were ever to become:**
>
> - Mandatory to participate online
> - A universal score
> - A hidden gatekeeper
> - A binding identity system
>
> **It would no longer align with its purpose.**

A neutral, opt-in history layer is ethical.
A coercive one is not.

---

## In Closing

**MIR does not try to fix people.
It fixes a missing layer of the internet.**

By providing continuity without surveillance and verifiable behavioral evidence without overreach, MIR helps platforms and organizations make better decisions -- while respecting the people, employees, contractors, and agents behind them.

---

## Origin

This constitution was first published on December 21, 2025, formalizing the answer to a question we asked ourselves:

*"What service is the internet missing the most?"*

The answer: a neutral, portable participation history layer that restores continuity without surveillance.

Version 1.2 (May 2, 2026) extends the constitutional commitments to enterprise mode, reflecting the operational shape of organizations recording the entities they are responsible for. Enterprise mode work began in January 2026; this update brings the document into alignment with that scope.

A versioned archive of this document is maintained at [github.com/MIR-2025/mir-constitution](https://github.com/MIR-2025/mir-constitution).

For the meaning of the name MIR, see [What MIR Means](https://mirregistry.org/mir).

---

## Maintained by

**MIRegistry, L.L.C.** -- Phoenix, Arizona, USA

**Website:**

- [mirregistry.org](https://mirregistry.org) -- marketplace and consumer site (individuals carrying their own participation history across platforms)
- [mirregistry.com](https://mirregistry.com) -- enterprise site (organizations recording participation history for the entities they are responsible for)

**Contact:**

- [hello@mirregistry.org](mailto:hello@mirregistry.org) -- marketplace and individual inquiries
- [partners@mirregistry.com](mailto:partners@mirregistry.com) -- enterprise and partner inquiries

---

## Version history

- **v1.2** (2026-05-02) -- Added "Two Modes, One Architecture" section. Corrected privacy language to distinguish subject-level PII (hashed) from operational PII (account-holder login emails, partner admin contacts, governed by DPA). Added two enterprise-specific commitments to "What MIR Will Never Do": no direct feed into HR / compensation / hiring / termination decisions, and no cross-organizational data leakage. Updated closing to acknowledge both platforms and organizations as consuming systems.
- **v1.1** (2026-01-19) -- Earlier revision.
- **v1.0** (2025-12-21) -- Original publication.
