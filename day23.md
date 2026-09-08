# Day 23 — Customer & MVP Blueprint: NIRIKSHAK AI

## Overview
Day 23 focused on converting the startup validation work for NIRIKSHAK AI into a concrete customer profile and MVP plan, comparing government Legal Metrology buyers with a faster-moving B2B compliance-SaaS segment.

## Ideal Customer Profile
### Primary ICP — Government
- State Legal Metrology Directorate / district office
- 20–300 field inspectors per state
- Triggers: new mandate, audit failure, digitization push
- Sales cycle: 12–24 months
- Pay-readiness: low-moderate; pilot proof required

### Secondary ICP — B2B
- Mid-size FMCG, cosmetics, or D2C brand/importer
- ₹5–200 Cr revenue; 1–5 person compliance team
- Triggers: recall scare, delisting, SKU launch, LMPC renewal
- Sales cycle: 2–8 weeks
- Pay-readiness: moderate-high

## Buyer Personas
### Inspector Raghunath — Government
A Legal Metrology Inspector with 8–15 years of service. Needs include reducing inspection time and maintaining defensible digital evidence.

### Priya — Compliance Lead
A Quality/Compliance Manager at an FMCG/D2C company. Needs include a self-serve pass/fail check for SKU labels in minutes and reducing compliance risk.

## Top Customer Pain Points
1. Manual label review is slow and inconsistent.
2. No standardized digital evidence trail for enforcement actions.
3. Increasing regulatory complexity can outpace manual capacity.
4. Findings can be difficult to defend without an audit trail.
5. Inspectors lack a mobile/field-friendly compliance tool.
6. Large SKU catalogs create risk of missed label errors.
7. SMEs lack an affordable self-check tool before print runs.
8. Cross-jurisdiction label variations are difficult to track manually.
9. New-SKU launches can be delayed by manual compliance sign-off.
10. No general-purpose cross-brand label checker.

## Customer Journey
### Government
Awareness → Hackathon demo / GeM listing / word-of-mouth
Consideration → Informal demo + legal-defensibility review
Purchase → MoU pilot → tender/GeM order
Retention → Statewide rollout if pilot succeeds

### B2B
Awareness → Search / LinkedIn / referrals / compliance content
Consideration → Free trial on 1–2 SKUs
Purchase → Standard SaaS purchase order
Retention → Expansion across SKU lines + annual renewal

## Buying Triggers & Objections
Buying triggers: new regulatory deadline, high-profile penalty/recall, GeM Startup Runway / innovation challenge, new SKU launch, delisting threat, or LMPC renewal.

Key objections include manual processes seeming sufficient, legal defensibility of AI findings, government infrastructure/data security, annual procurement budgets, and B2B QMS integration.

## MVP Recommendation
### Build First
- Photo upload/capture
- OCR field extraction
- LMPC rule-check engine
- Pass/fail with confidence score and plain-language reason
- Lightweight case/evidence log
- PDF-exportable evidence with photo, OCR output, rule match, and timestamp

### Do Not Build Yet
- Full multi-agent inspection workflow
- Statewide dashboards
- Government IT integrations
- FSSAI/BIS/export-market rule engines

## MoSCoW Prioritization
**Must Have:** Photo capture/upload, OCR extraction, LMPC rule checking, pass/fail + reason, exportable evidence log.

**Should Have:** Batch upload, confidence scoring, basic user accounts.

**Could Have:** Mobile app, Hindi/regional-language OCR, analytics dashboard.

**Won't Have Yet:** Government IT integrations, FSSAI/BIS/export rule engines, multi-agent workflow automation.

## Pricing Hypothesis
- Government pilot: ₹15–40L per 6–12 month pilot
- B2B self-serve: ₹15,000–60,000/year per brand, tiered by SKU volume

These are discovery-stage hypotheses, not fixed prices.

## Top 5 Risks
1. Government sales cycle may exhaust runway before the first contract.
2. No paying customers or LOIs exist yet.
3. Solo-founder bandwidth may become a constraint.
4. Government pilots may have data-access or hosting restrictions.
5. Incumbent QA vendors could enter the niche.

## 30-Day MVP Plan
- Week 1: Interview 5–8 inspectors + 5–8 compliance leads.
- Week 2: Scope the MVP to label photo → pass/fail + reason.
- Week 3: Build a clickable MVP and seek pilot/trial commitments.
- Week 4: Test against real labels, measure accuracy, and choose government, B2B, or both.

## Founder Action Sheet
Contact 10–15 inspectors/compliance leads, draft a discovery script, convert the SIH prototype into a single-workflow demo, identify pilot targets, register on relevant startup/procurement programs, build a labeled test dataset, prepare pricing one-pagers, set a Day 30 go/no-go checkpoint, and identify a government-sales/regulatory advisor or co-founder candidate.

## Scores
- Customer Clarity: 55/100
- Problem Severity: 70/100
- PMF Potential: 50/100
- MVP Readiness: 60/100

## Final Verdict
**PROMISING BUT UNVALIDATED**

The problem is considered real and technically addressable, and the proposed MVP is considered buildable in 30 days. However, there are currently no customer interviews, LOIs, or pilots. The next milestone is confirming willingness to pilot or pay through customer discovery.

## Key Learning
An MVP should focus on the smallest workflow that proves customer value rather than every technically possible feature. For NIRIKSHAK AI, the recommended first workflow is: capture a label → extract information with OCR → check it against LMPC rules → return a clear pass/fail result with evidence.
