# SEO/AEO Review — 2026-09-07

## Executive summary
Accuracy remediation remains higher priority than new content. The August 31 comment period for NRC-2025-1140 has passed; current NRC pages no longer list the docket among open documents for comment, while NRC Agreement State communications still show August 31 as the due date. Treat the rule as **proposed with comments closed and final action pending** unless a later controlling NRC/Federal Register source says otherwise.

The live website still prominently surfaces the unsupported July 29 article claiming DOE removed ALARA in January 2026. Current DOE public guidance continues to state that occupational doses under 10 CFR 835 are required to be ALARA. The homepage also still exposes a “Schedule a Free Consultation” header CTA, both `/services/` and `/services-2/` remain live with overlapping commercial intent and free-consultation language, and the New England consulting page still contains obsolete Agreement State language.

## Regulatory accuracy findings

### P0 — DOE/ALARA article
Live URL: `/2026/07/29/doe-removed-alara-in-january-2026-now-the-nrc-is-following-heres-why-its-happening/`

Observed claim: DOE removed ALARA effective January 9, 2026.

Primary-source check: DOE's current Occupational Radiation Protection Program page states that doses governed by 10 CFR 835 are required to be ALARA. No controlling DOE rule/order was found supporting the article's January 9 removal claim.

**Manual WordPress action:**
- Remove or retitle the article so it does not state that DOE removed ALARA.
- Add a visible correction note near the top.
- Reframe around the NRC's 2026 proposed radiation-protection rule and the broader policy debate.
- Consolidate overlapping material with the July 29 NRC/graded-approach posts if practical.

Suggested correction note:
> **Correction (September 2026):** An earlier version of this article stated that DOE removed ALARA requirements in January 2026. Current DOE guidance continues to state that occupational doses regulated under 10 CFR Part 835 are required to be ALARA. The NRC's 2026 action discussed below is a proposed rule, not a final change to current radiation-protection requirements.

### P0 — NRC-2025-1140 post-deadline refresh
The proposed rule was published July 15, 2026 with an August 31, 2026 comment deadline. NRC received requests for an extension, but no controlling NRC/Federal Register source was found showing a formally effective extension. NRC's current Documents for Comment page no longer lists this docket as open, and Agreement State communications still list August 31 as the due date.

**Manual WordPress action:**
- Remove “comment before August 31” calls to action from all NRC-2025-1140 posts.
- Add a dated status box to the strongest rulemaking page.

Suggested status copy:
> **Status update — September 2026:** The NRC's public comment period for Docket NRC-2025-1140 closed on August 31, 2026. The rule remains proposed; current NRC regulations remain in effect unless and until a final rule is published and becomes effective.

### P0 — New England Agreement State wording
Live URL: `/radiation-safety-consulting-new-england/`

The page still states that Massachusetts is an Agreement State while Connecticut, Rhode Island, New Hampshire, Vermont, and Maine are NRC-regulated states. This is obsolete. NRC's current Agreement State list includes CT, ME, MA, NH, RI, and VT. NRC's Connecticut page states Connecticut became an Agreement State on September 30, 2025.

**Replace the stale paragraph with:**
> All six New England states — Connecticut, Maine, Massachusetts, New Hampshire, Rhode Island, and Vermont — are NRC Agreement States for agreement material. Each state regulates most byproduct, source, and limited quantities of special nuclear material within its agreement scope, while the NRC retains authority over nuclear reactors, federal agencies, and certain other facilities and materials.

## Live-site QA findings

### Homepage CTA
The homepage body now uses the preferred “Submit a Project Inquiry” language, but the header still exposes **Schedule a Free Consultation**.

**Action:** replace the header CTA with **Submit a Project Inquiry** or **Request a Quote** and point it to the existing inquiry page.

### Duplicate Services hubs
Both `/services/` and `/services-2/` are indexed/discoverable and target substantially the same commercial intent. Both also retain free-initial-consultation language.

**Action:**
1. Keep `/services/` as the preferred service hub unless WordPress structure requires otherwise.
2. Merge any unique useful copy from `/services-2/`.
3. Redirect or otherwise retire `/services-2/` where possible.
4. Normalize navigation and internal links to the canonical service hub.
5. Replace free-consultation language with project-inquiry wording.

Suggested CTA:
> **Ready to Discuss Your Radiation Safety Needs?** Submit a project inquiry or quote request. We review submissions to understand the scope and may follow up if the project appears to be a good fit.

### Contact and other older service pages
Public caching is inconsistent. Previously crawled versions of `/contact/` and the New England page contain free-consultation/response promises. Recheck directly in WordPress during the next publishing session and remove any remaining guaranteed-response or consultation language.

## Analytics
Authenticated Google Search Console, Bing Webmaster Tools, and WordPress/Jetpack performance data were not accessible in this run. Do not infer or fabricate impressions, clicks, CTR, average position, indexed-page counts, top queries, or conversions from public search results.

Public search does confirm that the homepage, both Services URLs, the New England consulting page, the July ALARA posts, and evergreen ALARA content are discoverable. This supports the duplicate/cannibalization review but is not a substitute for Search Console.

## Content prioritization
Do not publish Priority 31 while the P0 accuracy items above remain live.

After remediation:
1. Review authenticated analytics for high-impression/low-CTR pages and rankings 8–20.
2. Consolidate overlapping July 29 ALARA/rulemaking posts.
3. Consolidate Services hubs.
4. If analytics remain unavailable, proceed with **Sealed Source Leak Test Requirements and Records** as provisional Priority 31, then survey-meter calibration and radioactive-material inventory/recordkeeping.

## Primary sources checked
- NRC Documents for Comment — current page updated September 4, 2026.
- NRC Agreement State Action Items and Due Dates for 2026 — NRC-2025-1140 comments listed due August 31, 2026.
- NRC Recently Released Commission Documents — extension-related correspondence released September 3, 2026.
- NRC Agreement States list — current page includes CT, ME, MA, NH, RI, VT.
- NRC Connecticut Agreement State Information — Connecticut became an Agreement State September 30, 2025.
- DOE Occupational Radiation Protection Program (10 CFR 835) — current DOE guidance states doses are required to be ALARA.
