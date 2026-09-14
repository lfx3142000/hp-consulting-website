# SEO/AEO Operating Rhythm — Advantage Health Physics

Last updated: 2026-09-14

## Purpose
Use this file as the first source of truth for recurring SEO/AEO work. The site is a traffic- and demand-validation MVP. Prioritize organic search visibility, answer-engine usefulness, regulatory accuracy, and demand signals from inquiries, submitted questions, downloads, and email signups. Do not build operational infrastructure or make service promises before demand justifies it.

## Guardrails
- Do not promise immediate response, emergency response, guaranteed consultation, guaranteed service, or fixed turnaround times.
- Preferred CTA language: **Submit a Project Inquiry**, **Request a Quote**, **Submit a Radiation Safety Question**, **Download the Free Resource**, or equivalent non-guaranteed language.
- Verify regulatory claims against current official NRC, eCFR, DOT, DOE, and applicable Agreement State sources before publishing or refreshing regulated content.
- For New England RAM licensing, treat CT, ME, MA, NH, RI, and VT as Agreement States for agreement material, subject to NRC-retained jurisdiction.
- Correct material regulatory inaccuracies before creating additional AEO pages.
- For rulemakings, distinguish proposed/final-phase work from a published final rule; do not describe scheduled future publication as current law.

## Recurring sequence
1. Regulatory accuracy audit of high-traffic, recently published, regulation-specific, and prominent recent blog content.
2. Live-site QA: navigation, CTA language, broken/redirecting internal links, duplicates, titles/headings, related-resource links, and observable indexability.
3. Analytics review when authenticated data are available: impressions, clicks, CTR, average position, indexed/coverage issues, top queries, top landing pages, high-impression/low-CTR pages, and rankings in positions 8–20.
4. Compare actual demand with `content-plan/content-calendar.md`; update priorities rather than blindly extending the queue.
5. Execute clear repo work: draft/correct content, internal-link recommendations, calendar/task notes, and manual WordPress instructions.
6. Record what changed and the next highest-value action.

## Current priority queue — 2026-09-14

### P0 — Regulatory corrections
1. **DOE Removed ALARA in January 2026** blog post (2026-07-29)
   - The live article still states that DOE removed ALARA effective January 9, 2026.
   - Current DOE public guidance still states that occupational doses under 10 CFR 835 are required to be ALARA.
   - Do not retain the DOE-removal claim unless a primary DOE rule/order showing that change can be produced.
   - Preferred remediation: retitle/reframe around the NRC's 2026 radiation-protection rulemaking, add a visible correction note, remove unsupported DOE-history claims, and consolidate with overlapping July 29 content where practical.

2. **NRC radiation-protection rulemaking — final-phase refresh**
   - Docket NRC-2025-1140's comment period closed after the August 31, 2026 deadline.
   - NRC's current EO 14300 tracker now lists **Reforming and Modernizing the NRC's Radiation Protection Framework** in **Final** phase with scheduled publication on **2027-02-17**.
   - “Final phase” does not mean a final rule has already been published or is currently effective.
   - Remove stale “comment now” language and stale “final rule expected November 2026” forecasts. Preferred dated language: “As of September 14, 2026, NRC lists the rulemaking in Final phase with final-rule publication scheduled for February 17, 2027. Current regulations remain in effect until a final rule is published and becomes effective.”

3. **Reducing Barriers to Medical Use Licensing — timeline refresh**
   - Live medical-use content says a final rule is expected in November 2026.
   - NRC's current EO 14300 tracker lists NRC-2025-1237 in Final phase with scheduled publication on **2027-03-31**.
   - Update affected medical-use pages and keep existing Part 35 requirements clearly distinguished from future changes.

4. **Package Receipt Survey Requirements** (`/package-receipt-survey-requirements-for-radioactive-material/`)
   - Correct the page so 10 CFR 20.1906 monitoring triggers are described accurately.
   - Do not state that every incoming RAM package requires visual inspection + surface dose + 1-meter dose + wipe survey.
   - Contamination monitoring and radiation-level monitoring have different triggers under 20.1906(b), and degraded packages trigger both.
   - Do not use simplified fixed contamination values as universal NRC notification criteria where 20.1906(d) incorporates the applicable Part 71/transport limits and package conditions.

5. **Agreement State wording**
   - `/radiation-safety-consulting-new-england/` is still live with obsolete wording identifying only Massachusetts as an Agreement State and CT/RI/NH/VT/ME as NRC-regulated states.
   - `/radiation-safety-officer-qualifications-nrc-and-agreement-state-requirements/` is still live saying only Massachusetts and Connecticut are Agreement States in New England.
   - Preferred copy: “All six New England states — Connecticut, Maine, Massachusetts, New Hampshire, Rhode Island, and Vermont — are NRC Agreement States for agreement material. NRC retains authority over reactors, federal agencies, and certain other facilities/materials.”

6. **Other live regulatory citation cleanup**
   - `/radiation-safety-program-development/` overstates 10 CFR 20.1101 by presenting written ALARA goals and investigation levels as universal requirements of that section. Reword to distinguish regulatory requirements from program practices/guidance.
   - `/rso-consulting/` says periodic-review reports are provided to management “as required by 10 CFR 35.24(b).” Remove that citation from the review-report claim; 35.24(b) governs RSO appointment/responsibility, not a general periodic-report-to-management requirement.

### P1 — Validation-MVP live-site cleanup
7. Remove or soften remaining service promises that conflict with MVP guardrails.
   - `/services/`, `/services-2/`, and `/radiation-safety-consulting-new-england/` still advertise a **free initial consultation**.
   - Older March content also contains “schedule a free consultation” language. Use a site-wide WordPress search for that phrase and replace with inquiry/request wording where appropriate.
   - The Contact page is currently aligned with validation-safe wording and should be preserved.

8. Consolidate duplicate/overlapping intent.
   - `/services/` and `/services-2/` remain live and target substantially overlapping service-hub intent. Prefer one canonical hub, merge unique useful content, redirect the duplicate if possible, and normalize internal links.
   - The July NRC/ALARA posts overlap substantially. Keep one authoritative 2026 rulemaking explainer plus genuinely differentiated supporting content; correct or consolidate the unsupported DOE-history article.

### P2 — Planning hygiene
9. Reconcile `TASKS.md` status tables with later completion notes for the lead tracker and Bing Webmaster Tools.
10. Maintain corrected content-calendar state/jurisdiction titles and table structure.
11. Add a dated note when major regulatory posts are refreshed so future audits can distinguish stale cache from current publication state.

### P3 — Analytics-driven growth
12. Do not lock Priority 31+ until authenticated Search Console/Jetpack/Bing data can be reviewed. When available, prioritize:
   - queries/pages with substantial impressions and weak CTR;
   - positions 8–20 where on-page refresh/internal links can move rankings;
   - clusters producing inquiries, question submissions, downloads, or signups.
13. If analytics remain unavailable after P0/P1 work is cleared, the provisional next AEO topic is **sealed-source leak-test requirements and records**, followed by survey-meter calibration and radioactive-material inventory/recordkeeping.

## Manual WordPress rule
Repository changes are not proof of WordPress publication. Each run must list exact live-site edits still needed and must not claim they are published unless verified on the public site.
