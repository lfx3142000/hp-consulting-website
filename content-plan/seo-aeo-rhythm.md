# SEO/AEO Operating Rhythm — Advantage Health Physics

Last updated: 2026-08-17

## Purpose
Use this file as the first source of truth for recurring SEO/AEO work. The site is a traffic- and demand-validation MVP. Prioritize organic search visibility, answer-engine usefulness, regulatory accuracy, and demand signals from inquiries, submitted questions, downloads, and email signups. Do not build operational infrastructure or make service promises before demand justifies it.

## Guardrails
- Do not promise immediate response, emergency response, guaranteed consultation, guaranteed service, or fixed turnaround times.
- Preferred CTA language: **Submit a Project Inquiry**, **Request a Quote**, **Submit a Radiation Safety Question**, **Download the Free Resource**, or equivalent non-guaranteed language.
- Verify regulatory claims against current official NRC, eCFR, DOT, DOE, and applicable Agreement State sources before publishing or refreshing regulated content.
- For New England RAM licensing, treat all six states — CT, ME, MA, NH, RI, and VT — as Agreement States for agreement material, subject to NRC-retained jurisdiction.
- Correct material regulatory inaccuracies before creating additional AEO pages.

## Recurring sequence
1. Regulatory accuracy audit of high-traffic, recently published, and regulation-specific pages, including prominent recent blog posts.
2. Live-site QA: navigation, CTA language, broken/redirecting internal links, duplicates, titles/headings, related-resource links, and observable indexability.
3. Analytics review when authenticated data are available: impressions, clicks, CTR, average position, indexed/coverage issues, top queries, top landing pages, high-impression/low-CTR pages, and rankings in positions 8–20.
4. Compare actual demand with `content-plan/content-calendar.md`; update priorities rather than blindly extending the queue.
5. Execute clear repo work: draft/correct content, internal-link recommendations, calendar/task notes, and manual WordPress instructions.
6. Record what changed and the next highest-value action.

## Current priority queue — 2026-08-17

### P0 — Regulatory corrections
1. **DOE Removed ALARA in January 2026** blog post (2026-07-29)
   - Do not state that DOE removed ALARA in January 2026 unless a primary DOE rule/order showing that change can be produced.
   - Current DOE public guidance still states that occupational doses under 10 CFR 835 are required to be ALARA and that DOE O 458.1 contains current ALARA requirements for protection of the public and environment.
   - Preferred remediation: retitle/reframe the article around the NRC's July 2026 proposed radiation-protection rule and distinguish the NRC proposal from current DOE requirements. Add a visible correction note if the original claim was materially wrong.
   - Official sources checked 2026-08-17: DOE Occupational Radiation Protection Program (10 CFR 835); DOE Policies, Standards, Guidance, and Statutes; NRC July 15, 2026 proposed rule / August 10 public meeting materials.

2. **Package Receipt Survey Requirements** (`/package-receipt-survey-requirements-for-radioactive-material/`)
   - Correct the page so 10 CFR 20.1906 monitoring triggers are described accurately.
   - Do not state that every incoming RAM package requires visual inspection + surface dose + 1-meter dose + wipe survey.
   - Do not use the current fixed 22,000/2,200 dpm per 100 cm² notification thresholds. The rule directs licensees to the applicable limits in 10 CFR 71.87(i)/transport contamination requirements; current DOT Table 9 in 49 CFR 173.443 uses 240 dpm/cm² for beta/gamma and low-toxicity alpha emitters and 24 dpm/cm² for other alpha emitters, with the specified measurement method.
   - State notification requirements by reference to the applicable 10 CFR 71.87(i) and 71.47 limits, including transport-specific/exclusive-use distinctions.

3. **RSO Qualifications** (`/radiation-safety-officer-qualifications-nrc-and-agreement-state-requirements/`)
   - Replace the outdated sentence saying only Massachusetts and Connecticut are Agreement States in New England.
   - Use: “All six New England states — Connecticut, Maine, Massachusetts, New Hampshire, Rhode Island, and Vermont — are NRC Agreement States for agreement material. NRC retains authority over reactors, fuel-cycle facilities, federal agencies and certain other areas/materials.”

### P1 — Validation-MVP live-site cleanup
4. Remove or soften service promises that conflict with MVP guardrails:
   - Homepage: replace **Schedule a Free Consultation** with **Submit a Project Inquiry** or **Request a Quote**.
   - Contact page: remove “We offer a free initial consultation,” “We typically respond to all inquiries within one business day,” “Quick response,” and similar guaranteed language.
   - RSO Consulting: remove/soften immediate/priority incident-response promises and avoid implying guaranteed continuous availability before that service is operationally supported.
   - Radiation Safety Audits: remove “Most audits are completed within two to three weeks of engagement.”
   - Prefer inquiry-based CTA wording on Training and Surveys rather than “Schedule …” language.

5. Homepage licensing link is not broken: `/radiation-license-consultant/` resolves to a live licensing page. However, the site also has `/radioactive-material-license-consulting/`; decide whether both pages intentionally target distinct search intent. If not, consolidate/canonicalize to reduce topic cannibalization.

### P2 — Planning hygiene
6. Correct outdated content-calendar titles for Maine, New Hampshire, and Vermont so they no longer say NRC regulates RAM in those states.
7. Repair malformed table cells in priorities 22–25 in `content-plan/content-calendar.md`.
8. Reconcile Phase 2/3 task-table statuses with later completion notes in `TASKS.md` (Bing setup and lead tracker are recorded as completed later in the file).

### P3 — Analytics-driven growth
9. Do not lock Priority 31+ until authenticated Search Console/Jetpack/Bing data can be reviewed. When available, prioritize:
   - queries/pages with substantial impressions and weak CTR;
   - positions 8–20 where on-page refresh/internal links can move rankings;
   - clusters producing inquiries, question submissions, downloads, or signups.
10. If analytics remain unavailable after accuracy/QA work is cleared, the provisional next AEO topic is **sealed-source leak-test requirements and records**, followed by survey-meter calibration and radioactive-material inventory/recordkeeping.

## Manual WordPress rule
Repository changes are not proof of WordPress publication. Each run must list exact live-site edits still needed and must not claim they are published unless verified on the public site.
