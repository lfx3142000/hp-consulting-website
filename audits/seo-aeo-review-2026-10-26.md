# SEO/AEO Review — 2026-10-26

**Operating source:** `content-plan/seo-aeo-rhythm.md` (read first). **Site:** https://advantagehealthphysics.wordpress.com/  
**Decision:** Regulatory remediation before Priority 31; repository drafts are **not** WordPress publications.

## 1. Regulatory accuracy — official-source checks first

### P0 — DOE/ALARA (unchanged live)
Homepage and July 29 post still claim DOE removed ALARA effective January 9, 2026; post also invites comments before August 31. DOE currently says doses governed by 10 CFR 835 must be ALARA. Do not repeat the removal assertion without a controlling DOE source. Remove homepage promotion until retitled/reframed; add a dated correction and separate DOE requirements from NRC's **proposed**, not effective, rulemaking.
- Live: https://advantagehealthphysics.wordpress.com/2026/07/29/doe-removed-alara-in-january-2026-now-the-nrc-is-following-heres-why-its-happening/
- Official: https://www.energy.gov/ehss/occupational-radiation-protection-program-10-cfr-835
- Official NRC tracker: https://www.nrc.gov/about-nrc/governing-laws/advance-act/wholesale-revision-regs

### P0 — Reciprocity and New England jurisdiction (unchanged live)
`/radioactive-material-license-reciprocity-in-new-england/` calls NH and VT non-Agreement States. `/radiation-safety-consulting-new-england/` calls CT, RI, NH, VT, ME NRC-regulated; RSO qualifications page names only MA and CT. **All six New England states (CT, ME, MA, NH, RI, VT) are Agreement States for covered materials**, subject to NRC-retained jurisdiction. Connecticut's agreement took effect September 30, 2025. Distinguish NRC 10 CFR 150.20 reciprocity from each receiving Agreement State's process. NRC Form 241 ordinarily must be filed at least **three calendar days** before first NRC-jurisdiction work in a calendar year; unusual-circumstance waiver is discretionary, not an automatic emergency exception; general license generally limited to **180 days/year** (offshore exception).
- Official: https://www.nrc.gov/agreement-states
- Official: https://www.nrc.gov/materials/faq-reciprocity
- Official: https://www.nrc.gov/agreement-states/connecticut
- Correction draft: `page-drafts/radioactive-material-license-reciprocity-correction-2026-10-26.md`

### P0 — Package receipt (unchanged live)
`/package-receipt-survey-requirements-for-radioactive-material/` treats visual check + surface and 1-m dose + wipe as universally mandatory and asserts fixed 22,000/2,200 dpm/100 cm² notification limits. Under **10 CFR 20.1906(b)**, labeled-package contamination monitoring has gas/special-form exceptions; radiation-level monitoring is triggered above Type A; packages known to contain RAM with degraded integrity require both. Required monitoring is generally within 3 hours of receipt during work hours or 3 hours after the next workday begins. Immediate notification is keyed to **10 CFR 71.87(i) and 71.47**, not those fixed page values. Written safe-opening procedures still apply.
- Official NRC interpretation: https://www.nrc.gov/facilities-safety/radiation-protection/health-physics-questions-and-answers---question-227
- Official NRC interpretation: https://www.nrc.gov/facilities-safety/radiation-protection/health-physics-questions-and-answers---question-229
- Regulation: https://www.ecfr.gov/current/title-10/chapter-I/part-20/subpart-J/section-20.1906
- Correction draft: `page-drafts/package-receipt-survey-correction-2026-10-26.md`

### New P1 regulatory issue — stale count of Agreement States
`/radiation-license-consultant/` FAQ still says **37 states** have NRC agreements. NRC and Connecticut officials identify Connecticut as the **40th** Agreement State, effective September 30, 2025. Prefer evergreen wording “many states, including all six New England states, are Agreement States; check the current NRC list” instead of a brittle number.
- Official: https://www.nrc.gov/about-nrc/news-releases/2025/updated-connecticut-becomes-40th-nrc-agreement-state

### Other P0/P1 outstanding
- NRC tracker currently lists NRC-2025-1140 in Final phase with **scheduled** publication 2027-02-17 and NRC-2025-1237 scheduled 2027-03-31. Neither is an effective final rule. Refresh stale November 2026 forecasts and August 31 comment invitations.
- `/radiation-safety-program-development/`: 10 CFR 20.1101 does not universally prescribe written ALARA goals/investigation levels as claimed; distinguish optional practices and license commitments.
- `/rso-consulting/`: 10 CFR 35.24(b) concerns management's written RSO appointment/responsibility, not a universal periodic report to management. Remove citation from that claim.
- Official: https://www.ecfr.gov/current/title-10/chapter-I/part-20/subpart-B/section-20.1101 ; https://www.ecfr.gov/current/title-10/chapter-I/part-35/subpart-B/section-35.24

## 2. Live-site QA
- Checked 11 prominent homepage links (header consultation, inquiry, Services, six service links, regional page, DOE post): all resolved to live pages in the public text crawl. **This is not a whole-site broken-link crawl.**
- Homepage header still says “Schedule a Free Consultation,” whereas main body says “Submit a Project Inquiry.” `/services/`, `/services-2/`, and New England page still promise free consultation. RSO page promises priority incident response; Audits page promises 2–3 weeks. Replace with validation-MVP inquiry language.
- `/services/` and `/services-2/` are both live and target overlapping service-hub intent. Consolidate into `/services/`, then redirect duplicate if WordPress permits; do not remove before preserving unique content.
- **New QA finding:** `/radiation-license-consultant/` has broken sentence flow around “Plan Your Next License Amendment,” a “Download ... (Coming Soon)” placeholder, and an inline CTA inserted into a sentence. Repair before promoting; also assess overlap with `/radioactive-material-license-consulting/`.
- **New internal-link finding:** “Related Resources” entries on the reciprocity and package-receipt pages appear as plain text, not clickable links in the public page representation. Rebuild actual WordPress hyperlinks to service hub, NRC-vs.-Agreement-State explainer, relevant checklist, and inquiry page.
- **Planning QA:** `content-plan/internal-linking-map.md` contains duplicated/corrupted introductory text and outdated `/submit-a-quote-project-inquiry/` references; the actual homepage inquiry link resolves to `/request-a-quote/`. Clean the map and verify all slugs against live pages before bulk edits.
- Sitemap XML, robots.txt, raw canonical tags and complete indexing could not be retrieved by the public fetcher; **unverified**, not proven broken. No authenticated WordPress publishing performed.

## 3. Analytics / demand prioritization
Authenticated Google Search Console, Bing Webmaster Tools and WordPress/Jetpack statistics were **not available**. No impressions, clicks, CTR, average position, indexing coverage, crawl errors, top queries, top landing pages or conversion counts are asserted. `analytics/search-console-notes.md` does not exist on default branch; content calendar August/September monthly review fields remain unpopulated. No defensible demand-based reprioritization possible. Hold Priority 31; provisional sealed-source leak-test requirements and records after P0/P1 clearance.

## 4. Manual WordPress publishing sequence
1. Unfeature/retitle DOE article, add visible correction, remove obsolete comment instructions.
2. Replace reciprocity page using draft, fix all six-state wording on regional, RSO qualifications, and older NRC-vs.-Agreement-State pages.
3. Replace package-receipt article using draft and verify license/state-specific nuances.
4. Update 2026 rulemaking statuses (clearly future **scheduled** dates).
5. Repair 37-state count, `/radiation-license-consultant/` formatting/placeholder, 20.1101 and 35.24(b) citations.
6. Remove free-consultation, priority-response, and fixed-turnaround promises.
7. Make Related Resources real hyperlinks; consolidate duplicate Services and ALARA content, test redirects.
8. Verify actual live text, sitemap, canonicals, link targets and indexing; then request reindexing for corrected URLs.
9. Export authenticated analytics and choose Priority 31 from search demand.

**Repository files prepared this run:** audit + two correction drafts + rhythm update. No WordPress publication implied.
