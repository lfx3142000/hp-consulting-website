# SEO/AEO Review — 2026-08-24

## Executive status
Do not publish Priority 31 yet. Public-site remediation remains higher value than adding another article.

## P0 — regulatory accuracy

### 1. DOE / NRC ALARA article remains live and prominently surfaced
Live post: `/2026/07/29/doe-removed-alara-in-january-2026-now-the-nrc-is-following-heres-why-its-happening/`

The post still states that DOE removed ALARA effective January 9, 2026. That claim should not remain without a primary DOE rule/order establishing the change. Current DOE materials continue to describe ALARA requirements under 10 CFR Part 835, while the NRC action is a **proposed** July 15, 2026 rulemaking rather than a final rule.

Manual WordPress remediation:
- Retitle/reframe around the NRC's 2026 proposed radiation-protection framework.
- Add a visible correction note explaining that the earlier DOE-removal statement was not substantiated by a primary DOE rule/order reviewed in this audit.
- Distinguish current DOE requirements from the NRC proposal.
- Keep the NRC comment deadline concrete: August 31, 2026, unless the agency extends it.

Primary sources checked:
- DOE 10 CFR Part 835 / occupational radiation protection materials: https://www.energy.gov/
- NRC proposed rule: 91 FR 43456, July 15, 2026.

### 2. Package receipt page requires correction
Live page: `/package-receipt-survey-requirements-for-radioactive-material/`

Use the actual trigger structure in 10 CFR 20.1906:
- contamination monitoring applies to labeled packages, except packages containing only gas or special-form material;
- radiation-level monitoring applies to labeled packages unless the quantity is <= Type A;
- both contamination and radiation monitoring apply when package integrity appears degraded;
- required monitoring must be performed within the timing specified in 10 CFR 20.1906(c);
- notification is triggered when removable contamination exceeds 10 CFR 71.87(i) limits or external radiation levels exceed 10 CFR 71.47.

Primary source: https://www.nrc.gov/reading-rm/doc-collections/cfr/part020/part020-1906.html

### 3. RSO Qualifications Agreement State sentence requires correction
Live page: `/radiation-safety-officer-qualifications-nrc-and-agreement-state-requirements/`

Use:
> All six New England states — Connecticut, Maine, Massachusetts, New Hampshire, Rhode Island, and Vermont — are NRC Agreement States for agreement material. NRC retains authority over reactors, fuel-cycle facilities, Federal agencies, and certain other areas/materials.

Primary source: https://www.nrc.gov/agreement-states
Connecticut became an Agreement State September 30, 2025: https://www.nrc.gov/agreement-states/connecticut

### 4. New England consulting page contains the same jurisdiction error
Live page: `/radiation-safety-consulting-new-england/`

The page currently describes Massachusetts as an Agreement State while calling Connecticut, Rhode Island, New Hampshire, Vermont, and Maine NRC-regulated states. That is outdated and materially misleading for licensing intent.

Action: replace the jurisdiction paragraph with the same six-state Agreement State language above, then verify each state-specific page.

## P1 — live-site validation/CTA QA

### Homepage
The public homepage still displays **Schedule a Free Consultation** near the hero even though the body correctly uses **Submit a Project Inquiry**.

Action: change the hero CTA to **Submit a Project Inquiry** or **Request a Quote**.

### Contact page
A fresh public crawl now shows the Contact page largely corrected: it uses project-inquiry language, says submissions do not guarantee service, and says a response is not guaranteed. Retain this version. An older cached copy still contains the free-consultation / one-business-day language, so verify the live page manually in WordPress and clear any stale cache if needed.

### Services pages
Two overlapping live service pages are publicly discoverable:
- `/services/`
- `/services-2/`

Both target broad radiation-safety consulting intent, and both still contain free-consultation language. This is a likely duplication/cannibalization issue.

Action:
- choose one canonical Services page;
- redirect or noindex/consolidate the duplicate if WordPress permits;
- update internal navigation to the canonical page only;
- replace free-consultation wording with project-inquiry or quote-request language.

### RSO consulting page
The current public page is substantially better aligned with MVP language than earlier versions: it now uses project-inquiry wording and explicitly says an inquiry does not guarantee service. Retain that pattern on other service pages.

## P2 — planning hygiene completed this run
`content-plan/content-calendar.md` was corrected to:
- remove obsolete titles saying NRC regulates RAM in Maine, New Hampshire, and Vermont;
- describe those pages as Agreement State requirements;
- repair malformed table cells in Priorities 22–25;
- record that authenticated analytics were unavailable for the July review and that Priority 31 remains on hold pending accuracy/QA remediation.

## Analytics
Authenticated Google Search Console, Bing Webmaster Tools, and WordPress/Jetpack metrics were not accessible in this run. Do not infer impressions, clicks, CTR, average position, top queries, landing pages, or conversion performance from public search results.

Public search confirms that the site and recent NRC/ALARA posts are discoverable, but this is not a substitute for authenticated indexing/performance data.

## Content/cannibalization observations
1. The site currently has multiple July 2026 pages focused on the same NRC ALARA / graded-approach rulemaking. After factual remediation, review these pages as a cluster and decide whether to consolidate, canonicalize, or differentiate intent. Prefer one authoritative current-rulemaking page plus distinct supporting pages rather than several near-duplicate news explainers.
2. `/services/` and `/services-2/` overlap strongly and should be consolidated around one canonical commercial-intent page.
3. Continue reviewing `/radiation-license-consultant/` versus `/radioactive-material-license-consulting/` for similar overlap.

## Next actions
1. Correct/reframe the DOE/ALARA article before the August 31, 2026 NRC comment deadline.
2. Correct package receipt monitoring/notification language.
3. Correct the RSO Qualifications Agreement State sentence.
4. Correct the New England consulting page's Agreement State paragraph.
5. Replace the homepage consultation CTA.
6. Consolidate `/services/` and `/services-2/` and remove consultation language.
7. Review ALARA rulemaking posts for cannibalization and internal-link them deliberately.
8. Obtain authenticated Search Console/Jetpack/Bing data for the next priority decision.
9. Only after P0/P1 are cleared, select Priority 31; provisional topic remains sealed-source leak-test requirements and records.
