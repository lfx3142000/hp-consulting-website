# SEO/AEO audit — 2026-11-23

Source of truth: `content-plan/seo-aeo-rhythm.md`. Regulatory remediation remains ahead of Priority 31. This is a repository audit only; **no WordPress pages were edited**.

## 1. Regulatory verification (official sources and live content)

- **P0 DOE/ALARA:** DOE's Occupational Radiation Protection Program still explicitly says 10 CFR 835 doses must be ALARA. The previously documented “DOE removed ALARA January 2026” claim must be corrected with the prepared `page-drafts/doe-alara-correction-2026-11-02.md`, including headline, excerpt, homepage promotion and visible correction notice. Official: https://www.energy.gov/ehss/occupational-radiation-protection-program-10-cfr-835
- **P0 package receipt, freshly crawled November 23:** `/package-receipt-survey-requirements-for-radioactive-material/` still asserts all incoming packages need a survey, lists a universal visual inspection + surface/1m measurement + wipe, and treats Yellow-II/III as the wipe trigger; its 22,000/2,200 dpm/100 cm² notification claims remain. These statements do not correctly reflect the separate triggers in 10 CFR 20.1906(b) and the referenced transport limits. Apply the October 26 correction draft after final line-by-line verification. https://www.ecfr.gov/current/title-10/section-20.1906 ; https://www.ecfr.gov/current/title-49/section-173.443
- **P0 Agreement States:** The live New England consulting page still labels CT, RI, NH, VT and ME as NRC-regulated; the reciprocity page still labels NH and VT non-Agreement States. NRC lists all six New England states as Agreement States. Correct those and older jurisdiction explainer/RSO qualifications/37-state FAQ using `page-drafts/radioactive-material-license-reciprocity-correction-2026-10-26.md` and authoritative state pages. https://www.nrc.gov/agreement-states
- **Rulemaking:** NRC's public tracker (retrieved November 23; indexed crawl older) lists NRC-2025-1140 as Final phase with projected publication February 17, 2027 and NRC-2025-1237 with projected March 31, 2027. These are not effective final regulations. Reverify tracker immediately before editing live dates. The tracker lists Part 150 for 1140; do not resolve the previously noted Part 53/150 Federal Register heading discrepancy without examining actual amendatory text. https://www.nrc.gov/about-nrc/governing-laws/advance-act/wholesale-revision-regs
- **Citation cleanup:** Correct unsupported claims attributed to 10 CFR 20.1101 (written ALARA goals/investigation levels universally required) and 10 CFR 35.24(b) (periodic management reports). Confirm exact paragraph text before publication.

## 2. Live-site QA (targeted)

- `/services/` and `/services-2/` remain discoverable and both offer free initial consultations; consolidate to `/services/`, redirect the duplicate if available, and normalize links.
- The New England consulting page still offers free consultation and misstates state jurisdictions.
- The homepage uses “Submit a Project Inquiry” in its body, but its older consultation header and DOE article promotion need a manual WordPress check.
- On the package-receipt page, Related Resources appear as unlinked text in the public text crawl; confirm in WordPress editor and add contextual links.
- Sitemap XML, robots.txt and canonical tags were attempted but not accessible through the public inspection tool; complete crawl, metadata audit, and indexing status remain unverified. Do not label them broken without independent validation.

## 3. Analytics and prioritization

Authenticated Google Search Console, Bing Webmaster Tools and WordPress/Jetpack analytics were not accessible. Impressions, clicks, CTR, average position, index coverage, crawl issues, top queries, landing pages, high-impression/low-CTR pages and rankings 8–20 are **unknown**, not zero. No demand-based reprioritization is justified. Continue holding Priority 31; sealed-source leak-test requirements/records remains provisional only after remediation.

## 4. Manual WordPress publication order

1. Apply November 2 DOE/ALARA correction, add dated notice, fix homepage promotion and excerpt.
2. Apply October 26 package-receipt and reciprocity correction drafts after comparing against current official regulations and relevant state requirements.
3. Correct all six-state jurisdiction pages, outdated state counts, and NRC-versus-Agreement-State explainer.
4. Update rulemaking articles' stale comment deadlines and forecasts; verify the actual affected CFR parts in Federal Register amendatory instructions.
5. Correct 20.1101 and 35.24(b) attributions; remove unsupported service/response promises.
6. Consolidate Services duplicate, repair Related Resources links, and test live redirects, sitemap, canonicals, and internal links.
7. Request indexing review and evaluate authenticated search and inquiry metrics before publishing Priority 31.

## Change log

- Added this audit on November 23. No live WordPress changes or authenticated analytics claims.
