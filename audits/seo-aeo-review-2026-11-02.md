# SEO/AEO review — 2026-11-02
**Source of truth:** `content-plan/seo-aeo-rhythm.md`. **Site:** https://advantagehealthphysics.wordpress.com/  
**Decision:** Correct existing regulated content before Priority 31. **Repository changes are not WordPress publications.**

## 1. Regulatory audit — official sources first

**P0 — DOE/ALARA still live.** Homepage and July 29 article continue claiming DOE removed ALARA on January 9, 2026, and invite comments by August 31, 2026. DOE's current 10 CFR 835 program page still explicitly requires ALARA. NRC's July 15, 2026 action under NRC-2025-1140 was a **proposed rule**. Prepared a complete correction draft: `page-drafts/doe-alara-correction-2026-11-02.md`. Remove the unsupported claim from title, excerpt and homepage; add a dated visible correction. Sources: https://www.energy.gov/ehss/occupational-radiation-protection-program-10-cfr-835 ; https://www.govinfo.gov/content/pkg/FR-2026-07-15/pdf/FR-2026-07-15.pdf

**New cross-article accuracy check:** The July 15, 2026 Federal Register proposed-rule heading identifies Parts **19, 20, 34, 35, 40, 50, 53, 61, 71 and 72**. The site's July ALARA articles instead list **Part 150** and omit **Part 53**. Check the actual amendatory text and fix the claimed affected-part list; do not simply copy the old list into revised articles.

**P0 — Reciprocity/jurisdiction unchanged.** The New England reciprocity page still labels NH and VT non-Agreement States, and says NRC Operations Center notice or automatic emergency notice suffices. All six New England states (CT, ME, MA, NH, RI, VT) are Agreement States for covered materials. NRC reciprocity under 10 CFR 150.20 ordinarily requires NRC Form 241 and applicable fee submitted to the relevant NRC regional office at least three days before first work of the calendar year; an unusual-circumstance timing waiver requires NRC authorization, not merely emergency self-notice. Use the complete 2026-10-26 correction draft. Also correct New England consulting, RSO Qualifications, March NRC-vs.-Agreement-State explainer, and the licensing FAQ saying only 37 states. Sources: https://www.nrc.gov/agreement-states ; https://www.nrc.gov/agreement-states/connecticut ; https://www.law.cornell.edu/cfr/text/10/150.20

**P0 — Package receipt unchanged.** Live article still presents a universal survey package and 22,000/2,200 dpm/100 cm² notification criteria. 10 CFR 20.1906(b) has distinct labeled-package contamination and dose-rate triggers and requires both monitoring types for known RAM packages with degraded integrity; 20.1906(d) points to 71.87(i) and 71.47 for immediate notification. Use the 2026-10-26 package-receipt correction draft; verify license and Agreement State conditions. Sources: https://www.law.cornell.edu/cfr/text/10/20.1906 ; https://www.govinfo.gov/content/pkg/CFR-2025-title10-vol1/pdf/CFR-2025-title10-vol1-sec20-1906.pdf

**Other P0/P1:** NRC rulemaking posts still say the August 31 comment deadline is upcoming and predict a November 2026 final rule. The previously indexed NRC tracker scheduled radiation protection for February 17, 2027 and medical licensing for March 31, 2027, but the tracker returned a 403 on this run, so **those future dates were not freshly reverified**. Verify before publishing; no effective final rule was established from the sources checked. Program Development incorrectly treats written ALARA goals/investigation levels as universal 20.1101 requirements. RSO Consulting misattributes periodic reports to 35.24(b).

## 2. Live-site QA — checked 2026-11-02
- Tested six prominent homepage links (consultation, inquiry, Services, license consultant, New England, DOE post): all resolved. **Not a complete crawl.**
- Header still says **Schedule a Free Consultation**; main CTA correctly says **Submit a Project Inquiry**. Contact and request-a-quote pages use non-guaranteed language.
- `/services/` and `/services-2/` remain overlapping, live service hubs with free-consultation promises. Prefer `/services/`; merge unique material, redirect other after testing.
- `/radiation-license-consultant/` still has a broken opening paragraph, inline CTA fragment, and unfinished worksheet placeholder; FAQ still says 37 Agreement States.
- Reciprocity and package receipt Related Resources appear as plain text rather than clickable links in the public page representation. RSO Consulting has duplicate FAQ blocks and a visibly split question-link label.
- A few pages display repeated title/H1 text; check WordPress title block vs page body to avoid redundant headings.
- Sitemap XML, robots.txt, raw canonical metadata, complete broken-link crawl and indexing coverage were **not accessible** through the public fetcher; unverified rather than broken.

## 3. Analytics
Authenticated Google Search Console, Bing Webmaster Tools, and WordPress/Jetpack performance data **unavailable**. No impressions, clicks, CTR, average position, indexing totals, crawl errors, top queries, landing pages or conversions are claimed. Search-demand reprioritization is not possible. Hold Priority 31; sealed-source leak-test requirements/records remains provisional after corrections.

## 4. Manual WordPress publishing sequence
1. Replace DOE/ALARA article using the new correction draft, correct title/excerpt, remove homepage promotion, and verify the live change.
2. Publish the existing reciprocity and package receipt correction drafts; fix all six-state jurisdiction references.
3. Refresh rulemaking status only after rechecking the NRC docket and Federal Register, and correct the affected-part list.
4. Fix 20.1101 and 35.24(b) citations, 37-state FAQ, licensing page formatting/placeholder, and duplicate RSO FAQs.
5. Replace consultation/priority-response/fixed-turnaround promises; consolidate duplicate Services and ALARA posts.
6. Turn Related Resources into actual links, check redirects and canonicals, validate sitemap and indexability, then request reindexing.
7. Obtain authenticated analytics, prioritize high-impression/low-CTR pages and positions 8–20, then decide Priority 31.

**No WordPress changes were made by this review.**
