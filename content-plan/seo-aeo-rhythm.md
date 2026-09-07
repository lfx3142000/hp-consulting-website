# SEO/AEO Operating Rhythm — Advantage Health Physics

Last updated: 2026-09-07

## Purpose
Use this file as the first source of truth for recurring SEO/AEO work. The site is a traffic- and demand-validation MVP. Prioritize organic search visibility, answer-engine usefulness, regulatory accuracy, and demand signals from inquiries, submitted questions, downloads, and email signups. Do not build operational infrastructure or make service promises before demand justifies it.

## Guardrails
- Do not promise immediate response, emergency response, guaranteed consultation, guaranteed service, or fixed turnaround times.
- Preferred CTA language: **Submit a Project Inquiry**, **Request a Quote**, **Submit a Radiation Safety Question**, **Download the Free Resource**, or equivalent non-guaranteed language.
- Verify regulatory claims against current official NRC, eCFR, DOT, DOE, and applicable Agreement State sources before publishing or refreshing regulated content.
- For New England RAM licensing, treat CT, ME, MA, NH, RI, and VT as Agreement States for agreement material, subject to NRC-retained jurisdiction.
- Correct material regulatory inaccuracies before creating additional AEO pages.
- For rulemakings, clearly distinguish proposed rules from final rules and closed comment periods from active comment periods.

## Recurring sequence
1. Regulatory accuracy audit of high-traffic, recently published, regulation-specific, and prominent recent blog content.
2. Live-site QA: navigation, CTA language, broken/redirecting internal links, duplicates, titles/headings, related-resource links, and observable indexability.
3. Analytics review when authenticated data are available: impressions, clicks, CTR, average position, indexed/coverage issues, top queries, top landing pages, high-impression/low-CTR pages, and rankings in positions 8–20.
4. Compare actual demand with `content-plan/content-calendar.md`; update priorities rather than blindly extending the queue.
5. Execute clear repo work: draft/correct content, internal-link recommendations, calendar/task notes, and manual WordPress instructions.
6. Record what changed and the next highest-value action.

## Current priority queue — 2026-09-07

### P0 — Regulatory corrections
1. **DOE Removed ALARA in January 2026** blog post (2026-07-29)
   - The live article still states that DOE removed ALARA effective January 9, 2026.
   - Current DOE public guidance still states that occupational doses under 10 CFR 835 are required to be ALARA.
   - Do not retain the DOE-removal claim unless a primary DOE rule/order showing that change can be produced.
   - Preferred remediation: retitle/reframe around the NRC's 2026 proposed radiation-protection rule, add a visible correction note, remove unsupported DOE-history claims, and consolidate with overlapping July 29 rulemaking content where practical.

2. **NRC radiation-protection rulemaking — post-comment-period refresh**
   - Docket NRC-2025-1140 had an August 31, 2026 comment deadline.
   - NRC's current Documents for Comment page no longer lists the docket as open, while NRC Agreement State communications still show August 31 as the due date.
   - Earlier requests sought extensions, but no controlling NRC/Federal Register source was found showing that the deadline was formally extended.
   - Remove stale 'comment now' language from all related posts and replace it with dated post-comment-period language: the rule remains proposed, comments have closed, and the final rule is still pending.
   - Do not describe proposed changes as current requirements.

3. **Package Receipt Survey Requirements** (`/package-receipt-survey-requirements-for-radioactive-material/`)
   - Correct the page so 10 CFR 20.1906 monitoring triggers are described accurately.
   - Do not state that every incoming RAM package requires visual inspection + surface dose + 1-meter dose + wipe survey.
   - Do not use fixed contamination values as universal NRC notification criteria where the regulation instead incorporates applicable Part 71/transport limits and package conditions.
   - Reverify the live page during each crawl because public caching can be inconsistent.

4. **Agreement State wording**
   - `/radiation-safety-consulting-new-england/` was last observed describing only Massachusetts as an Agreement State and CT/RI/NH/VT/ME as NRC-regulated states. Correct if still live.
   - `/radiation-safety-officer-qualifications-nrc-and-agreement-state-requirements/` previously contained stale wording and should be rechecked.
   - Preferred copy: “All six New England states — Connecticut, Maine, Massachusetts, New Hampshire, Rhode Island, and Vermont — are NRC Agreement States for agreement material. NRC retains authority over reactors, federal agencies, and certain other facilities/materials.”

### P1 — Validation-MVP live-site cleanup
5. Remove or soften remaining service promises that conflict with MVP guardrails.
   - Homepage currently still exposes **Schedule a Free Consultation** in the header even though the main body uses **Submit a Project Inquiry**.
   - Recheck `/contact/`, `/services/`, `/services-2/`, and `/radiation-safety-consulting-new-england/` for free-consultation, guaranteed-response, or turnaround language and replace with inquiry/request wording.

6. Consolidate duplicate/overlapping intent.
   - `/services/` and `/services-2/` target substantially overlapping service-hub intent. Prefer one canonical hub, merge unique useful content, redirect the duplicate if possible, and normalize internal links.
   - The July 29 NRC/ALARA posts overlap substantially. Keep one authoritative 2026 rulemaking explainer plus genuinely differentiated supporting content; correct or consolidate the unsupported DOE-history article.

### P2 — Planning hygiene
7. Reconcile `TASKS.md` status tables with later completion notes for the lead tracker and Bing Webmaster Tools.
8. Maintain corrected content-calendar state/jurisdiction titles and table structure.
9. Add a dated note when major regulatory posts are refreshed so future audits can distinguish stale cache from current publication state.

### P3 — Analytics-driven growth
10. Do not lock Priority 31+ until authenticated Search Console/Jetpack/Bing data can be reviewed. When available, prioritize:
   - queries/pages with substantial impressions and weak CTR;
   - positions 8–20 where on-page refresh/internal links can move rankings;
   - clusters producing inquiries, question submissions, downloads, or signups.
11. If analytics remain unavailable after P0/P1 work is cleared, the provisional next AEO topic is **sealed-source leak-test requirements and records**, followed by survey-meter calibration and radioactive-material inventory/recordkeeping.

## Manual WordPress rule
Repository changes are not proof of WordPress publication. Each run must list exact live-site edits still needed and must not claim they are published unless verified on the public site.
