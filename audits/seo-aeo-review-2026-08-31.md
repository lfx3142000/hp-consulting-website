# SEO/AEO Review — 2026-08-31

## Executive summary
Accuracy remediation remains higher priority than Priority 31 content creation. The live site still surfaces the unsupported claim that DOE removed ALARA in January 2026, the package-receipt page still overstates 10 CFR 20.1906 monitoring requirements and uses incorrect fixed contamination notification thresholds, and the New England consulting page still describes five current Agreement States as NRC-regulated states. The homepage and duplicate Services page also retain validation-MVP-inconsistent free-consultation language.

A time-sensitive content opportunity exists today: NRC still officially lists August 31, 2026 as the comment deadline for Docket NRC-2025-1140. NRC Chairman Ho K. Nieh sent an August 21 letter requesting a 60-day extension, but NRC's public comment page still showed August 31 as the close date as of August 28. Do not state that the deadline was extended unless NRC/Regulations.gov formally updates the docket.

## P0 regulatory corrections

### 1. DOE / ALARA article
Live URL: `/2026/07/29/doe-removed-alara-in-january-2026-now-the-nrc-is-following-heres-why-its-happening/`

Current live claim says DOE removed ALARA effective January 9, 2026. Current DOE public materials still state that occupational doses governed by 10 CFR 835 are required to be ALARA, and DOE's current Occupational Radiation Protection Program page continues to describe ALARA as a requirement.

Recommended action:
- Retitle and reframe around the NRC's July 2026 proposed radiation-protection rule.
- Add a visible correction note explaining that the earlier DOE statement could not be substantiated and that current DOE materials continue to require ALARA under 10 CFR 835.
- Remove any implication that DOE already completed an equivalent ALARA repeal.

Suggested correction note:
> Correction (August 31, 2026): An earlier version of this article stated that DOE removed ALARA requirements in January 2026. Current DOE materials continue to state that occupational doses governed by 10 CFR 835 are required to be ALARA. The NRC action discussed here is a July 2026 proposed rule and has not yet become final.

Primary sources:
- DOE Occupational Radiation Protection Program (10 CFR 835): https://www.energy.gov/ehss/occupational-radiation-protection-program-10-cfr-835
- NRC Documents for Comment: https://www.nrc.gov/public-involve/doc-comment
- NRC wholesale revision page: https://www.nrc.gov/about-nrc/governing-laws/advance-act/wholesale-revision-regs

### 2. Package Receipt Survey Requirements
Live URL: `/package-receipt-survey-requirements-for-radioactive-material/`

The live page still states that receipt monitoring must include visual inspection, surface and 1-meter dose-rate measurements, and wipe testing, and still gives 22,000 dpm/100 cm2 beta-gamma and 2,200 dpm/100 cm2 alpha as notification thresholds.

Recommended action:
- Rebuild the requirements section around the actual triggers in 10 CFR 20.1906.
- Distinguish contamination monitoring, radiation-level monitoring, and damaged-package monitoring rather than treating them as a universal survey bundle.
- Avoid fixed notification numbers divorced from the applicable 10 CFR 71.87(i), 10 CFR 71.47, and DOT transportation conditions.
- If numerical transport contamination limits are shown, identify the applicable units, averaging area, material category, and transport condition.

### 3. New England Agreement State wording
Live URL: `/radiation-safety-consulting-new-england/`

The live page still says Massachusetts is an Agreement State but calls Connecticut, Rhode Island, New Hampshire, Vermont, and Maine NRC-regulated states. NRC's current Agreement State list includes all six New England states: CT, ME, MA, NH, RI, and VT.

Suggested replacement:
> All six New England states — Connecticut, Maine, Massachusetts, New Hampshire, Rhode Island, and Vermont — are NRC Agreement States for agreement material. Each state administers its own radioactive-material licensing program within the authority transferred by NRC, while NRC retains jurisdiction over reactors, federal agencies, and certain other facilities and materials.

Primary source: https://www.nrc.gov/agreement-states

Also verify the RSO Qualifications page for the same stale statement.

## Same-day NRC rulemaking opportunity
NRC's current public-comment page lists Docket NRC-2025-1140, Reforming and Modernizing the NRC's Radiation Protection Framework, with an August 31, 2026 deadline. NRC's Commission Correspondence page also shows an August 21 letter from Chairman Ho K. Nieh requesting a 60-day extension of the comment period.

Recommended same-day update to the strongest NRC rulemaking article:
- Add a dated note: `As of August 31, 2026, NRC's public comment page still lists August 31 as the deadline. NRC Chairman Ho K. Nieh has requested a 60-day extension, but licensees should not rely on an extension unless the NRC formally changes the docket deadline.`
- Link to the NRC comment page and docket.
- After the deadline, refresh all 'comment now' CTAs immediately based on the docket's actual status.

This is a strong AEO opportunity because searchers may specifically ask whether the comment period was extended.

## Live-site QA

### Validation-MVP CTA inconsistencies
Still observable:
- Homepage header: `Schedule a Free Consultation` while the body correctly uses `Submit a Project Inquiry`.
- `/services/`: `We offer a free initial consultation`.
- `/services-2/`: `Contact Advantage Health Physics for a free initial consultation.`
- `/radiation-safety-consulting-new-england/`: `Get a Free Consultation` / `We offer a free initial consultation.`

Recommended replacement across all locations: `Submit a Project Inquiry` or `Request a Quote`.

### Duplicate Services pages
Both `/services/` and `/services-2/` are live and target substantially the same commercial intent. Choose `/services/` as the likely canonical service hub, consolidate any unique copy from `/services-2/`, redirect `/services-2/` if WordPress plan/tools allow, and ensure navigation/internal links point only to the canonical page.

### Content cannibalization
Three July 29 posts substantially overlap on NRC ALARA/radiation-protection-rulemaking intent. Keep one primary 'NRC proposed rule' explainer, keep the graded-approach comparison only if it is clearly differentiated, and correct or consolidate the DOE-history article rather than allowing three pages to compete for the same query family.

## Analytics
Authenticated Google Search Console, Bing Webmaster Tools, and Jetpack/WordPress statistics were not accessible during this run. Do not infer impressions, clicks, CTR, average position, coverage, or conversion metrics from public search results.

Repository planning inconsistency remains: TASKS.md still marks the lead tracker and Bing Webmaster Tools as pending in the phase tables even though later completion notes say both were completed. This should be reconciled during a planning-hygiene edit.

## Priority order after this run
1. Correct/reframe the DOE/ALARA article and add the visible correction note.
2. Add an August 31 deadline-status note to the main NRC rulemaking article; do not claim the requested extension is effective unless formally published.
3. Correct Package Receipt Survey Requirements.
4. Correct Agreement State wording on New England consulting and RSO Qualifications pages.
5. Replace remaining free-consultation/scheduling CTAs with inquiry-based wording.
6. Consolidate `/services-2/` into `/services/` and review July 29 ALARA post cannibalization.
7. Reconcile TASKS.md phase-table statuses with later completion notes.
8. Review authenticated analytics before locking Priority 31.
9. If analytics remain unavailable after remediation, proceed with Sealed Source Leak Test Requirements and Records.
