# SEO/AEO Review — 2026-09-21

## Executive summary
P0 regulatory corrections remain live and should continue to block Priority 31 publication. Public live-site checks confirm that the unsupported DOE-removed-ALARA claim, package receipt survey overstatement, stale New England Agreement State wording, and duplicate Services hub are still publicly discoverable. The Contact page remains aligned with validation-safe wording.

## Regulatory accuracy audit

### P0 — DOE/ALARA article remains live
The homepage still promotes **“DOE Removed ALARA in January 2026. Now the NRC Is Following.”** Current DOE Occupational Radiation Protection Program guidance states that doses governed by 10 CFR 835 are required to be ALARA. Do not retain the DOE-removal assertion unless a primary DOE rule/order establishing that change is identified.

**Manual WordPress action:** retitle/reframe the article around the NRC 2026 radiation-protection rulemaking, add a visible correction note, remove the unsupported DOE-history claim, and consolidate overlapping July 29 ALARA/rulemaking content where practical.

### P0 — Package Receipt Survey Requirements remains materially overstated
The live page still says a receipt survey generally must include visual inspection, surface and 1-meter dose-rate measurements, and a wipe test, and presents 22,000/2,200 dpm per 100 cm² as notification thresholds. Rewrite around the actual 10 CFR 20.1906 triggers rather than presenting one universal survey package. Contamination monitoring, radiation-level monitoring, and damaged/degraded package provisions have different triggers; notification criteria should be tied to the applicable Part 71/transport limits and package condition.

### P0 — Agreement State wording remains stale
The live New England consulting page still calls CT, RI, NH, VT, and ME NRC-regulated states. The RSO Qualifications page still says only Massachusetts and Connecticut are Agreement States in New England. NRC's current Agreement State list includes all six New England states: Connecticut, Maine, Massachusetts, New Hampshire, Rhode Island, and Vermont. Connecticut became an Agreement State September 30, 2025.

**Preferred replacement:** “All six New England states — Connecticut, Maine, Massachusetts, New Hampshire, Rhode Island, and Vermont — are NRC Agreement States for agreement material. NRC retains authority over reactors, federal agencies, and certain other facilities/materials.”

### P0 — Other citation cleanup still visible
The Radiation Safety Program Development page still says 10 CFR 20.1101 requires written ALARA goals and investigation levels. Reword to distinguish the regulation's radiation-protection-program/ALARA/annual-review requirements from optional or guidance-based program practices.

### Rulemaking status
Continue treating NRC-2025-1140 and NRC-2025-1237 as rulemakings in process, not current law. NRC's EO 14300 wholesale-revision page explains that “Rule Phase” describes where a rule is in the process. Do not equate a Final phase designation or scheduled future publication date with an already-effective final rule. Refresh live posts if NRC changes the schedule.

## Live-site SEO/QA

### Duplicate service hub persists
Both `/services/` and `/services-2/` remain publicly discoverable and target substantially overlapping commercial intent. Prefer `/services/` as the canonical hub, merge any unique useful material, redirect/retire `/services-2/` where WordPress permits, and normalize internal links.

### Validation-MVP copy
`/services/`, `/services-2/`, and `/radiation-safety-consulting-new-england/` still advertise a free initial consultation. Older March posts also remain discoverable with “schedule a free consultation” language. Perform a site-wide WordPress search for `free consultation` and `schedule a free consultation`; replace with **Submit a Project Inquiry** or **Request a Quote** unless a consultation offer is intentionally being activated.

The Contact page remains correctly framed: it says inquiries may be reviewed/followed up and do not guarantee service or a response. Preserve that model.

### Internal linking opportunity
After the Agreement State corrections, link the New England consulting page and each state-specific consultant page to the authoritative `NRC vs. Agreement State` explainer and to the main RAM License Consulting page. The main RAM License Consulting page already correctly states that all six New England states are Agreement States, making it a good internal-link target.

## Analytics
Authenticated Google Search Console, Bing Webmaster Tools, and WordPress/Jetpack analytics were not accessible in this run. Do not infer or invent impressions, clicks, CTR, average position, indexed counts, coverage issues, top queries, landing-page performance, or conversion metrics from public search results.

## Priority decision
Do **not** publish Priority 31 yet. Current order:
1. Correct/reframe DOE/ALARA article and consolidate overlapping rulemaking content.
2. Correct Package Receipt Survey Requirements.
3. Correct New England and RSO Qualifications Agreement State wording.
4. Correct 20.1101/other citation overstatements and refresh rulemaking timelines where stale.
5. Remove remaining free-consultation language unless intentionally activated.
6. Consolidate `/services-2/` into `/services/` and normalize internal links.
7. Review authenticated analytics and use actual demand to select Priority 31.
8. If analytics remain unavailable after P0/P1 remediation, proceed with **Sealed Source Leak Test Requirements and Records**, then survey-meter calibration and RAM inventory/recordkeeping.

## Primary sources checked this run
- NRC Agreement States: https://www.nrc.gov/agreement-states
- NRC Connecticut Agreement State information: https://www.nrc.gov/agreement-states/connecticut
- NRC EO 14300 wholesale revision tracker: https://www.nrc.gov/about-nrc/governing-laws/advance-act/wholesale-revision-regs
- DOE Occupational Radiation Protection Program (10 CFR 835): https://www.energy.gov/ehss/occupational-radiation-protection-program-10-cfr-835

## Manual WordPress checklist
- [ ] Correct/reframe DOE/ALARA article and add visible correction note.
- [ ] Correct package-receipt survey page.
- [ ] Correct Agreement State wording on New England consulting page.
- [ ] Correct Agreement State wording on RSO Qualifications page.
- [ ] Correct 20.1101 overstatement on Program Development page.
- [ ] Refresh NRC rulemaking timelines/status text where stale.
- [ ] Search/replace remaining free-consultation promises with validation-safe CTA wording.
- [ ] Consolidate `/services-2/` into `/services/` and normalize internal links.
- [ ] After corrections, request reindexing of materially changed URLs in Search Console/Bing if available.
