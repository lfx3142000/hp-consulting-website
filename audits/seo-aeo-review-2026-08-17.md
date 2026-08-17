# SEO/AEO Review — 2026-08-17

## Executive summary
The accuracy/QA backlog is still not cleared, so this run does not recommend publishing Priority 31 yet. Two previously identified regulatory inaccuracies remain live, and a newly identified high-severity issue affects a prominent July 29 blog post: the claim that DOE removed ALARA in January 2026 is not supported by current official DOE sources and conflicts with DOE's current public statements that 10 CFR 835 occupational doses must be ALARA and DOE O 458.1 retains ALARA requirements. The NRC's July 15, 2026 ALARA-removal action is a proposed rule, with comments due August 31, 2026.

Authenticated Search Console, Bing Webmaster Tools, and Jetpack metrics were not accessible, so no impressions, clicks, CTR, rankings, conversions, or coverage statistics are reported.

## 1. Regulatory accuracy audit

### P0-A — July 29 DOE/ALARA article needs correction or reframing
Live title: **DOE Removed ALARA in January 2026. Now the NRC Is Following. Here’s Why It’s Happening.**

The homepage currently summarizes this article by saying DOE quietly removed ALARA in January 2026. Current official DOE pages checked August 17, 2026 say the opposite for the major DOE radiation-protection frameworks:

- DOE's Occupational Radiation Protection Program states that doses under 10 CFR 835 are required to be ALARA and must not exceed dose limits.
- DOE's current Policies, Standards, Guidance, and Statutes page describes the ALARA Handbook as guidance for complying with current ALARA requirements in DOE O 458.1, paragraph 4.d.
- DOE's Radiation Protection of the Public and Environment page continues to identify DOE O 458.1 as the governing public/environmental radiation-protection order.

The NRC did publish a proposed rule on July 15, 2026 to reform its radiation-protection framework, including removal of ALARA as a standalone NRC regulatory requirement and replacement with a graded approach. The public-comment deadline is August 31, 2026. That NRC proposal should not be presented as evidence that DOE already removed ALARA unless a specific primary DOE action can be cited.

Recommended WordPress remediation:
1. Add a correction note at the top of the July 29 DOE article.
2. Retitle/reframe the article so it does not state DOE removed ALARA in January 2026 unless a primary DOE rule/order is located.
3. Suggested safer title: **NRC Proposed Removing ALARA in July 2026 — What Changed and What Has Not**.
4. Suggested correction note: **Correction (August 17, 2026): An earlier version of this article stated that DOE removed ALARA in January 2026. Current DOE guidance continues to describe ALARA requirements under 10 CFR 835 and DOE O 458.1. The NRC action discussed here is a July 2026 proposed rule and is not yet a final rule.**
5. Review the July 21 and July 29 ALARA articles together to avoid overlapping search intent and contradictory statements.

Official sources checked 2026-08-17:
- DOE Occupational Radiation Protection Program (10 CFR 835): https://www.energy.gov/ehss/occupational-radiation-protection-program-10-cfr-835
- DOE Policies, Standards, Guidance, and Statutes: https://www.energy.gov/ehss/policies-standards-guidance-and-statutes
- DOE Radiation Protection of the Public and Environment: https://www.energy.gov/ehss/radiation-protection-public-and-environment
- NRC 2026 Federal Register notices / July 15 proposed rule: https://www.nrc.gov/reading-rm/doc-collections/fedreg/notices/2026
- NRC radiation-protection-framework public meeting: https://www.nrc.gov/public-involve/public-meetings/pmns/20260627

### P0-B — Package Receipt Survey Requirements remains inaccurate live
The live page still says every applicable receipt survey includes visual inspection, surface and 1-meter dose measurements, and a removable-contamination wipe; it also still gives fixed 22,000/2,200 dpm per 100 cm² wipe action levels.

This remains inconsistent with the conditional monitoring triggers in 10 CFR 20.1906 and with the current transport contamination limits/method referenced through 10 CFR 71.87(i) and 49 CFR 173.443.

Use the replacement core copy already documented in `audits/seo-aeo-review-2026-08-10.md`.

### P0-C — RSO Qualifications Agreement State statement remains inaccurate live
The live page still says: “In New England, Massachusetts and Connecticut are Agreement States.”

Current NRC information identifies Connecticut, Maine, Massachusetts, New Hampshire, Rhode Island, and Vermont as Agreement States. Replace the sentence using the copy already documented in the 2026-08-10 audit.

Official basis checked 2026-08-17:
- NRC Agreement States: https://ww2.nrc.gov/agreement-states
- NRC IMPEP contacts, updated March 23, 2026, list all six New England programs in the Agreement State structure.

## 2. Live-site QA

### Validation-MVP copy remains live
- Homepage still exposes **Schedule a Free Consultation** in the hero while the body correctly uses **Submit a Project Inquiry**.
- Contact page still says **free initial consultation**, promises a response **within one business day**, and repeats **Quick response**.

These conflict with the repository guardrails and should be changed before adding more conversion-oriented traffic.

### Homepage licensing link is live, not broken
The homepage `/radiation-license-consultant/` target resolves successfully. This is therefore not a broken-link problem. However, the site also has `/radioactive-material-license-consulting/`, and both target closely overlapping commercial licensing intent. Review them for deliberate differentiation, canonical strategy, or consolidation to reduce keyword/topic cannibalization.

### ALARA content cannibalization risk
Public search surfaces several closely overlapping 2026 ALARA pages, including:
- July 21: **NRC Proposes Elimination of ALARA: What Every NRC Licensee Must Know Before August 31**
- July 29: **NRC Proposes Removing ALARA From Radiation Protection Rules — What Licensees Need to Know**
- July 29: **ALARA vs. Graded Approach to Dose Management**
- July 29: **DOE Removed ALARA in January 2026...**
- March evergreen ALARA explainers

Recommendation: keep one primary current-rulemaking explainer, one genuinely differentiated comparison page, and evergreen ALARA guidance. Consolidate or canonicalize near-duplicates and cross-link them clearly. The August 31 comment deadline makes the accurate rulemaking explainer the timely primary page through the end of August.

## 3. Analytics status
Authenticated Google Search Console, Bing Webmaster Tools, and WordPress/Jetpack analytics were not accessible from available tools in this run. Therefore no impressions, clicks, CTR, average position, top-query, top-landing-page, crawl, conversion, or index-coverage metrics are reported.

Public search confirms that multiple newer AEO pages and the July rulemaking content are discoverable, but this cannot substitute for authenticated indexing and performance data.

## 4. Planning/repository work completed
- Updated `content-plan/seo-aeo-rhythm.md` on 2026-08-17 to add the DOE/ALARA claim as the highest regulatory-accuracy priority, add DOE to the required primary-source set, and clarify that the homepage licensing link resolves but may create topic cannibalization.
- Planning hygiene remains pending in `content-plan/content-calendar.md`: stale Maine/NH/VT titles and malformed Priority 22–25 table cells.
- `TASKS.md` still contains stale phase statuses inconsistent with later completion notes for Bing Webmaster Tools and the lead tracker.

## 5. Priority order after this run
1. Correct/reframe the July 29 **DOE Removed ALARA** article and add a visible correction note.
2. Correct the Package Receipt Survey page.
3. Correct the RSO Qualifications Agreement State paragraph.
4. Remove validation-MVP promises from Home and Contact, then review RSO Consulting/Audits/Training/Surveys for the same issue.
5. Rationalize overlapping ALARA rulemaking pages and the two commercial licensing pages to reduce cannibalization.
6. Clean up content-calendar titles/table formatting and stale `TASKS.md` statuses.
7. Review authenticated Search Console/Jetpack/Bing data when available; choose Priority 31 from actual demand.
8. If analytics remain unavailable after remediation, draft **Sealed Source Leak Test Requirements and Records** next.

## 6. Manual WordPress actions
Repository changes do not change the live WordPress site. The following remain manual:
- add correction/reframe July 29 DOE/ALARA article;
- replace Package Receipt Survey core regulatory copy;
- replace RSO Qualifications Agreement State paragraph;
- change homepage consultation hero CTA;
- remove Contact-page consultation/one-business-day promises;
- review overlapping ALARA posts and licensing pages for consolidation/canonicalization;
- after material corrections, request reindexing in Search Console where appropriate.
