# SEO/AEO audit — 2026-11-16

Source of truth: `content-plan/seo-aeo-rhythm.md`. Regulatory corrections remain ahead of Priority 31. No WordPress publication was performed.

## Regulatory audit (official sources checked November 16)
- **P0 DOE/ALARA:** DOE's 10 CFR 835 page continues to state occupational doses must be ALARA. Do not publish the unsupported "DOE removed ALARA January 2026" claim. The November 2 replacement draft is ready; correct title, excerpt, homepage promotion, and include visible correction. https://www.energy.gov/ehss/occupational-radiation-protection-program-10-cfr-835
- **P0 Agreement States:** NRC lists CT, ME, MA, NH, RI, VT as Agreement States. Connecticut became the 40th on September 30, 2025. Apply October 26 reciprocity draft and correct New England consulting, RSO Qualifications, licensing count, and older NRC-vs-state explainer. https://www.nrc.gov/agreement-states ; https://www.nrc.gov/agreement-states/connecticut
- **P0 Package receipt:** The current live page's universalized survey approach must be corrected using `page-drafts/package-receipt-survey-correction-2026-10-26.md`. 10 CFR 20.1906 separates removable contamination and radiation-level monitoring triggers and has special requirements for degraded packages. Do not describe 22,000/2,200 dpm per 100 cm² as universally applicable notification criteria. https://www.nrc.gov/facilities-safety/radiation-protection/health-physics-questions-and-answers---question-228 ; https://www.ecfr.gov/current/title-10/section-20.1906
- **Rulemaking:** Prior tracker schedules for NRC-2025-1140 (February 17, 2027) and NRC-2025-1237 (March 31, 2027) are provisional; do not treat a Final phase or scheduled publication as an effective rule. Verify official tracker/docket before changing date-specific text. The Part 53 vs Part 150 discrepancy remains unresolved.
- **Additional:** Recheck 10 CFR 20.1101 and 35.24(b) misattributions before editing existing pages.

## Live QA (targeted, not comprehensive)
- Public homepage continues to present non-guaranteed **Submit a Project Inquiry** in main content; older header **Schedule a Free Consultation** requires manual verification and cleanup.
- Both `/services/` and `/services-2/` are still publicly discoverable and each advertises a free initial consultation, contrary to MVP guardrails. Prefer `/services/` as primary hub; merge unique material and redirect duplicate if supported.
- Contact page currently uses non-guaranteed inquiry wording; preserve.
- Existing ALARA/rulemaking posts overlap in intent. Prefer one authoritative explainer with differentiated supporting articles.
- Full link crawl, XML sitemap consistency, robots directives, raw canonical tags, metadata completeness and authenticated index coverage remain unverified. Do not call unverified items broken.

## Analytics and content priorities
GSC, Bing Webmaster Tools, and WordPress/Jetpack authenticated reports were unavailable. No verified impressions, clicks, CTR, average position, indexing/crawl metrics, top queries, landing pages or conversion data. No demand-based reprioritization; Priority 31 remains on hold. Sealed-source leak-test requirements and records remains a provisional future topic.

## Manual WordPress queue
1. Publish corrected DOE/ALARA article from November 2 draft; fix headline, snippet, homepage and dated correction.
2. Publish October 26 reciprocity and package-receipt corrections after final rule-by-rule verification.
3. Correct all six-state and outdated 37-state claims; inspect older jurisdiction pages.
4. Update obsolete NRC rulemaking timelines only after fresh official docket review; resolve Part 53/150 issue.
5. Fix 20.1101 and 35.24(b) claims; replace free-consultation promises, consolidate duplicate Services and overlapping ALARA articles, repair Related Resources links.
6. After publishing, test live pages, redirects, sitemap, canonicals, and indexing; export authenticated GSC/Bing/Jetpack data.

**Repository edits are not proof of WordPress publication.**
