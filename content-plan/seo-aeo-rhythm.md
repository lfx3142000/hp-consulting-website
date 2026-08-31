# SEO/AEO Operating Rhythm — Advantage Health Physics

Last updated: 2026-08-31

## Purpose
Use this file as the first source of truth for recurring SEO/AEO work. The site is a traffic- and demand-validation MVP. Prioritize organic search visibility, answer-engine usefulness, regulatory accuracy, and demand signals from inquiries, submitted questions, downloads, and email signups. Do not build operational infrastructure or make service promises before demand justifies it.

## Guardrails
- Do not promise immediate response, emergency response, guaranteed consultation, guaranteed service, or fixed turnaround times.
- Preferred CTA language: **Submit a Project Inquiry**, **Request a Quote**, **Submit a Radiation Safety Question**, **Download the Free Resource**, or equivalent non-guaranteed language.
- Verify regulatory claims against current official NRC, eCFR, DOT, DOE, and applicable Agreement State sources before publishing or refreshing regulated content.
- For New England RAM licensing, treat all six states — CT, ME, MA, NH, RI, and VT — as Agreement States for agreement material, subject to NRC-retained jurisdiction.
- Correct material regulatory inaccuracies before creating additional AEO pages.
- For active rulemakings, distinguish a requested/possible deadline extension from a formally effective deadline change. Use the current NRC/Regulations.gov docket status as controlling.

## Recurring sequence
1. Regulatory accuracy audit of high-traffic, recently published, and regulation-specific pages, including prominent recent blog posts.
2. Live-site QA: navigation, CTA language, broken/redirecting internal links, duplicates, titles/headings, related-resource links, and observable indexability.
3. Analytics review when authenticated data are available: impressions, clicks, CTR, average position, indexed/coverage issues, top queries, top landing pages, high-impression/low-CTR pages, and rankings in positions 8–20.
4. Compare actual demand with `content-plan/content-calendar.md`; update priorities rather than blindly extending the queue.
5. Execute clear repo work: draft/correct content, internal-link recommendations, calendar/task notes, and manual WordPress instructions.
6. Record what changed and the next highest-value action.

## Current priority queue — 2026-08-31

### P0 — Regulatory corrections and current-rulemaking accuracy
1. **DOE Removed ALARA in January 2026** blog post (2026-07-29)
   - Do not state that DOE removed ALARA in January 2026 unless a primary DOE rule/order showing that change can be produced.
   - Current DOE public guidance still states that occupational doses under 10 CFR 835 are required to be ALARA.
   - Preferred remediation: retitle/reframe the article around the NRC's July 2026 proposed radiation-protection rule and distinguish the NRC proposal from current DOE requirements. Add a visible correction note.

2. **NRC radiation-protection rulemaking deadline status**
   - As of 2026-08-31, NRC's public comment page still lists August 31, 2026 as the deadline for Docket NRC-2025-1140.
   - NRC's Commission Correspondence page shows an August 21, 2026 letter from Chairman Ho K. Nieh requesting a 60-day extension.
   - Do **not** state that the deadline has been extended unless NRC/Regulations.gov formally updates the docket.
   - Add a dated status note to the strongest NRC rulemaking article and refresh all comment-deadline language after the docket closes or changes.

3. **Package Receipt Survey Requirements** (`/package-receipt-survey-requirements-for-radioactive-material/`)
   - Correct the page so 10 CFR 20.1906 monitoring triggers are described accurately.
   - Do not state that every incoming RAM package requires visual inspection + surface dose + 1-meter dose + wipe survey.
   - Do not use the current fixed 22,000/2,200 dpm per 100 cm² notification thresholds as universal notification criteria.
   - State notification requirements by reference to the applicable 10 CFR 71.87(i), 10 CFR 71.47, and transport-specific conditions.

4. **Agreement State wording**
   - `radiation-safety-consulting-new-england`: currently describes CT, RI, NH, VT, and ME as NRC-regulated states. Correct it.
   - `radiation-safety-officer-qualifications-nrc-and-agreement-state-requirements`: verify and correct the previously identified stale sentence.
   - Use: “All six New England states — Connecticut, Maine, Massachusetts, New Hampshire, Rhode Island, and Vermont — are NRC Agreement States for agreement material. NRC retains authority over reactors, federal agencies and certain other areas/materials.”

### P1 — Validation-MVP live-site cleanup
5. Remove or soften remaining service promises that conflict with MVP guardrails:
   - Homepage header: replace **Schedule a Free Consultation** with **Submit a Project Inquiry** or **Request a Quote**.
   - `/services/`: replace free-consultation wording.
   - `/services-2/`: replace free-consultation wording.
   - `/radiation-safety-consulting-new-england/`: replace “Get a Free Consultation” and similar wording.
   - Contact page should be rechecked against the freshest live version because public crawls are inconsistent; if one-business-day/free-consultation language remains, remove it.

6. Consolidate duplicate/overlapping commercial and news intent:
   - `/services/` and `/services-2/` both target the same service-hub intent. Prefer one canonical service hub, consolidate unique content, redirect the duplicate if possible, and normalize internal links.
   - Three July 29 NRC/ALARA posts substantially overlap. Keep one authoritative current-rulemaking page, one genuinely differentiated graded-approach comparison if useful, and correct/consolidate the DOE-history post.

### P2 — Planning hygiene
7. Reconcile `TASKS.md` status tables with later completion notes:
   - Task 2.9 lead tracker is marked Pending in the table but later recorded completed.
   - Task 3.4 Bing Webmaster Tools is marked Pending in the table but later recorded completed via Search Console import.
8. Maintain corrected content-calendar titles and table structure; do not reintroduce obsolete NRC-regulates-ME/NH/VT wording.

### P3 — Analytics-driven growth
9. Do not lock Priority 31+ until authenticated Search Console/Jetpack/Bing data can be reviewed. When available, prioritize:
   - queries/pages with substantial impressions and weak CTR;
   - positions 8–20 where on-page refresh/internal links can move rankings;
   - clusters producing inquiries, question submissions, downloads, or signups.
10. If analytics remain unavailable after accuracy/QA work is cleared, the provisional next AEO topic is **sealed-source leak-test requirements and records**, followed by survey-meter calibration and radioactive-material inventory/recordkeeping.

## Manual WordPress rule
Repository changes are not proof of WordPress publication. Each run must list exact live-site edits still needed and must not claim they are published unless verified on the public site.
