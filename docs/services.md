# Services

**English** · [中文](./services.zh-CN.md)

[← Back to README](../README.md)

---

## Engagement models

Two ways to engage, chosen based on project shape:

### 1. Fixed-price project

Best when scope is clear and deliverables are well-defined. One quote, milestone-based payments, formal acceptance.

### 2. Hourly engagement

Best when scope evolves or you want continuous iteration. Weekly/monthly billing with detailed time tracking.

---

## Typical service tiers

> All figures are **indicative starting points**. Every project is quoted individually based on complexity, urgency, and whether on-site / hardware integration is required.

### A. Light customization — UI re-skin + small feature additions

**Includes**: branding (logos, splash, theme), toolbar restructuring, hiding/reorganizing existing UI, small custom QML widgets.

- **Timeline**: 1-4 weeks
- **Starting from**: USD $1,500 - $4,500

### B. Mid-scope — new modules + protocol extensions

**Includes**: custom MAVLink messages, new mission planning modes, payload integration (gimbal, sensors), custom data link, multi-vehicle support.

- **Timeline**: 1-3 months
- **Starting from**: USD $7,000 - $20,000

### C. Full custom — industry solution + mobile

**Includes**: complete industry-specific GCS with Windows + Android, custom backend integration, AI inference overlay, specialized flight modes.

- **Timeline**: 3-6 months
- **Starting from**: USD $25,000 - $70,000+

### D. Qt 5 → Qt 6 migration

**Includes**: migrating your existing Qt 5 QGC fork to Qt 6.x — QML compatibility, build system update, dependency upgrades.

- **Timeline**: 3-8 weeks (depends on scale of existing changes)
- **Starting from**: USD $4,500 - $11,000

### E. Ongoing maintenance & retainer

**Includes**: long-term version maintenance, bug fixes, upstream-merge support, monthly on-demand work.

- **Format**: annual retainer or hours pool
- **Starting from**: USD $12,000 - $40,000 / year

### F. Hourly

For ambiguous-scope or rapid-iteration work.

- **Rate**: USD $60 - $120 / hour (depending on technical depth required)
- **Minimum block**: 40 hours

---

## Engagement process

```
1. Initial inquiry          (1-3 days)
   ↓
2. Technical proposal + quote (3-7 days)
   ↓
3. Contract + 30%-50% upfront
   ↓
4. Milestone deliveries     (2-4 milestones)
   ↓
5. Acceptance + final payment
   ↓
6. Warranty period          (30 days default)
```

### Details

**1. Initial inquiry** — email or DM with project background. I'll respond within 1-3 days with initial feasibility feedback and clarifying questions.

**2. Technical proposal** — free 1-2 page document covering deliverables, technical approach, milestones, and quote.

**3. Contract & upfront** — formal contract specifying deliverables, acceptance criteria, payment schedule. 30%-50% upfront.

**4. Milestone deliveries** — each milestone yields a runnable build plus a brief progress note. Acceptance releases that milestone's payment.

**5. Acceptance & final payment** — full delivery passes acceptance, final payment released.

**6. Warranty** — **30-day bug-fix warranty** by default, scoped to delivered features. New requirements go through change-management.

---

## What's included / not included

### Included by default

- Source code (license model decided per project)
- Build scripts and README
- Documentation for non-trivial changes
- One remote handover/walkthrough session
- 30-day bug warranty

### Not included by default (add-on)

- On-site deployment and training (quoted as travel + hours)
- Mass-production support, factory test plans
- Certifications (CE / FCC / CCC / etc.)
- Flight controller firmware development (PX4 / APM) — separate engagement if needed
- Backend server hosting and operations

---

## IP and confidentiality

- **Client-specific custom work**: copyright transferred to client upon delivery. I retain the right to use redacted/anonymized references for portfolio purposes.
- **Generic tools/libraries**: copyright retained, licensed to client under permissive open-source (MIT / Apache 2.0).
- **NDA**: standard NDAs accepted for confidential projects.
- **Upstream license**: QGroundControl upstream is Apache 2.0; derivative work must comply.

---

## When **not** to hire me

To save us both time, here's when I'll suggest you look elsewhere:

- Budget under **USD $1,500** — not cost-effective for either side
- "Pay after we see results" — I require partial upfront
- "Build me something like DJI" — typically signals undefined requirements; I'll suggest scoping first
- On-site / co-location required — remote-first only
- Defense / classified work — only via established authorized channels

---

## Contact

See the [main README](../README.md#contact).

When reaching out, please include:
- One-line project description
- Flight controller platform (PX4 / ArduPilot / custom)
- Rough budget and timeline expectations
