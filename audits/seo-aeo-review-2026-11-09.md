# SEO/AEO audit — 2026-11-09

Source of truth: `content-plan/seo-aeo-rhythm.md` (last updated November 2). **No WordPress publication performed.** Regulatory remediation remains ahead of Priority 31.

## Regulatory audit — current primary-source checks
1. **P0 DOE/ALARA:** Homepage continues to promote “DOE Removed ALARA in January 2026” (public crawl November 9). DOE's Occupational Radiation Protection Program page, crawled November 8, explicitly says 10 CFR 835 doses must be ALARA. The November 2 correction draft `page-drafts/doe-alara-correction-2026-11-02.md` remains ready for manual publishing. Remove unsupported headline, teaser and excerpt; add visible correction. Sources: https://www.energy.gov/ehss/occupational-radiation-protection-program-10-cfr-835 ; https://advantagehealthphysics.wordpress.com/
2. **P0 Reciprocity:** `/radioactive-material-license-reciprocity-in-new-england/` still calls NH and VT non-Agreement States. NRC's current list identifies all six New England states as Agreement States; Connecticut's transition took effect September 30, 2025. Use `page-drafts/radioactive-material-license-reciprocity-correction-2026-10-26.md`. Source: https://www.nrc.gov/agreement-states ; https://www.nrc.gov/agreement-states/connecticut
3. **P0 Package receipt:** `/package-receipt-survey-requirements-for-radioactive-material/` still universalizes surface/1-m dose measurements and wipe testing, and states 22,000/2,200 dpm per 100 cm² as universal notification levels. Apply `page-drafts/package-receipt-survey-correction-2026-10-26.md` after checking 10 CFR 20.1906 and applicable 10 CFR 71.87(i)/71.47 and DOT 49 CFR 173.443. Source: https://www.ecfr.gov/current/title-10/section-20.1906
4. **P0 State pages:** `/radiation-safety-consulting-new-england/` still describes CT/RI/NH/VT/ME as NRC-regulated. Correct to six Agreement States, while preserving NRC-retained jurisdiction.
5. **Rulemaking:** NRC's public tracker search result (crawled within the past month) still shows NRC-2025-1140 in “Final” phase with planned publication February 17, 2027. This is a **planned date**, not an effective final rule. The tracker returned 403 on direct retrieval today; recheck the official docket before changing time-sensitive copy. **New discrepancy to verify:** the tracker table lists Parts 19,20,34,35,40,50,61,71,72,150, while the November 2 DOE draft says the July 15 Federal Register heading lists Part 53 instead of 150. Do not silently “correct” one from the other: check the proposed rule's actual amendatory instructions and identify whether the tracker is listing a different scope. Source: https://www.nrc.gov/about-nrc/governing-laws/advance-act/wholesale-revision-regs
6. Previously documented 10 CFR 20.1101 and 35.24(b) citation overstatements remain on the remediation queue; no new publication claimed.

## Live SEO and QA
- Homepage public crawl (November 9) shows **Schedule a Free Consultation** in header, despite **Submit a Project Inquiry** in main content.
- `/services/` and `/services-2/` are both publicly accessible and both advertise free initial consultations. Retain `/services/` as hub; merge unique content and redirect the duplicate if WordPress plan permits.
- Three July 29 ALARA/rulemaking posts remain clustered on homepage; risk of overlapping search intent.
- On reciprocity and package receipt pages, “Related Resources” appear as plain text rather than clickable links in the public text crawl.
- Homepage navigation and these targeted pages resolve. **No complete crawl**; sitemap XML and robots.txt endpoints were inaccessible through the available public retrieval tool; canonical metadata and full broken-link status are unverified.
- New: the site's current public homepage crawl date is November 9, confirming the unsupported DOE teaser and header CTA remain present this week.

## Analytics and prioritization
Authenticated GSC, Bing Webmaster Tools and WordPress/Jetpack data unavailable. **No verified impressions, clicks, CTR, positions, indexing coverage, crawl errors, queries, landing pages or conversion metrics.** Therefore no demand-driven reprioritization. Priority 31 (sealed-source leak test requirements and records) stays on hold until P0 corrections are live.

## Manual WordPress steps (in order)
1. Replace July 29 DOE article using November 2 draft, visible correction, title/excerpt/social snippet and homepage promotion.
2. Replace reciprocity and package receipt articles using October 26 drafts, confirm every regulatory threshold against primary rules.
3. Correct all six-state jurisdiction copy in regional, RSO, licensing and FAQ pages.
4. Update stale NRC rulemaking timelines **only after** checking current official docket and resolving Part 53 vs Part 150 source discrepancy.
5. Replace free-consultation promises; consolidate Services hubs and ALARA duplicates; make Related Resources real hyperlinks.
6. Test live URLs, redirects, sitemap, canonical/indexability, then request reindexing.
7. Export GSC/Bing/Jetpack metrics for CTR and position 8–20 opportunities; only then select Priority 31.

## Status
This audit is a repository document only. No WordPress pages were edited.