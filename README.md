# Auf

I build evidence-driven software products end to end — from the research behind a formula to the shipped, deployed product a real person uses.

The throughline across everything below: dig into the actual data or process a product needs to serve, disclose what's rigorous versus what's a calibrated estimate, and match the architecture to the real constraint instead of defaulting to whatever's trendiest. Based in Malaysia, building under the [Aufthority](https://www.aufthority.com) label.

**Core strengths:** product development · data governance & evidence auditing · process/compliance design · applied research & population-calibrated analysis · access-control & schema design

---

## What I build

Three areas, one method.

### Health & clinical tools
Screening and tracking apps calibrated to Malaysian/Southeast Asian population data instead of defaulting to Western norms.

- **[CerminDiri](https://github.com/aufthority/cermindiri)** — metabolic & cardiovascular risk screener: FINDRISC, INTERHEART NL-IHRS, Framingham (BMI version), Asia-Pacific BMI cutoffs
- **[MyTDEE](https://mytdee.aufthority.com)** — calorie calculator built on a Malaysian-derived BMR equation (Ismail et al., 1998) instead of Western defaults
- **[MakanLah](https://github.com/aufthority/makanlah)** — photo-first meal diary for dietitian review; no calorie counting, on-device storage only
- **[NeuroHabit](https://github.com/aufthority/neurohabitbeta)** — habit tracker where every habit is individually weighted against a literature review, not just brainstormed

### Education & institutional tooling
Process and compliance systems built for real institutions with real constraints — no dedicated dev support, real regulatory requirements.

- **[Kompas Semester](https://github.com/aufthority/kompassemester)** — course companion with a proper Postgres schema and Row-Level Security, built after trending coursework results against final exam performance surfaced a measured mastery gap
- **[KPJU-SOP CPD Tracker](https://github.com/aufthority/kpju_cpd_tracker)** — live compliance dashboard mapping a CPD programme's full approval-to-close-out lifecycle, revenue tracking included
- **[KPJU CPD Bot](https://github.com/aufthority/kpju-sopcpd-bot)** — Telegram FAQ/deadline bot backed entirely by a Google Sheet; zero database, zero redeploy to update content

---

## How I approach it

- **Evidence-tiered, not just built.** Every formula, threshold, and habit weighting is labeled *Measured / Proxy / Design-calibration* and disclosed in the product itself — not asserted.
- **Gaps disclosed, not hidden.** Where no population-specific dataset exists, the product says so rather than quietly substituting a Western default and presenting it as equivalent.
- **Architecture matched to the actual constraint.** Zero-backend, single-file static apps by default; a real Postgres backend with Row-Level Security only when the product genuinely needs persistent multi-user data — a deliberate choice per project, not a default.
- **Built for the people who'll actually use it.** Bilingual (EN/BM) across the health tool suite. PDPA-aware consent flows where personal data is collected. Culturally specific content where it matters — prayer and dhikr as literature-backed habit categories, not generic wellness copy with a translation layer.

---

## Evidence & data governance

A consolidated ledger tracking the evidence tier — measured, proxy, or design-calibration — behind every formula and threshold across the tool suite: [aufthority/evidence-ledger](https://github.com/aufthority/evidence-ledger)

## Tech

`HTML` `CSS` `JavaScript` `PostgreSQL` `Supabase` `Row-Level Security` `Vercel` `Firebase` `PWA / Service Workers` `Chart.js` `Google Sheets API / CSV pipelines`

---

## Elsewhere

[aufthority.com](https://www.aufthority.com) · [@aufthority](https://threads.com/aufthority)
