# SEO/AEO Review — 2026-08-03

## Executive summary

Regulatory accuracy remediation should take priority over publishing another AEO page. The live site and content calendar contain outdated New England Agreement State language that can misdirect prospective licensees and reduce trust.

## Sources reviewed

- Live website: https://advantagehealthphysics.wordpress.com
- NRC Agreement States list and state program pages
- Repository `TASKS.md`
- `content-plan/content-calendar.md`
- `content-plan/seo-aeo-build-plan.md`

## Confirmed regulatory status

As of 2026-08-03, all six New England states are NRC Agreement States for applicable agreement materials:

- Connecticut
- Maine
- Massachusetts
- New Hampshire
- Rhode Island
- Vermont

NRC retains authority over reactors, fuel-cycle facilities, federal agencies, federally recognized tribal lands, and other retained or exclusive federal jurisdiction as applicable.

Official starting points:

- NRC Agreement States: https://www.nrc.gov/agreement-states
- Connecticut: https://www.nrc.gov/agreement-states/connecticut
- Maine: https://www.nrc.gov/agreement-states/maine
- New Hampshire: https://www.nrc.gov/agreement-states/new-hampshire
- Rhode Island: https://www.nrc.gov/agreement-states/rhode-island
- Vermont: https://www.nrc.gov/agreement-states/vermont

## High-priority live-site correction

### Radiation Safety Officer Qualifications page

URL:

`/radiation-safety-officer-qualifications-nrc-and-agreement-state-requirements/`

Current live statement:

> In New England, Massachusetts and Connecticut are Agreement States.

This is outdated. Replace the Agreement State section with:

> Agreement States administer their own radiation-control programs for agreement materials under authority transferred by the NRC. Qualification standards generally remain compatible with NRC requirements, but application forms, documentation expectations, license conditions, and regulator interpretations can differ by state and license category.
>
> All six New England states—Connecticut, Maine, Massachusetts, New Hampshire, Rhode Island, and Vermont—are Agreement States. Most non-federal applicants seeking authority to possess or use agreement materials in these states should apply to the applicable state radiation-control program rather than the NRC. NRC retains authority over nuclear reactors, fuel-cycle facilities, federal agencies, federally recognized tribal lands, and certain other retained-jurisdiction activities.
>
> Before submitting an RSO amendment or new-license application, verify the current state regulations, application guidance, license category, and regulator-specific training-and-experience documentation requirements.

Also change the CTA from:

> Need help evaluating RSO qualifications or preparing a license application? Submit a project inquiry to discuss your situation.

To the validation-safe version:

> Submit a project inquiry or quote request. We review submissions to understand current radiation safety needs and may follow up if the project appears to be a good fit.

## Content-calendar corrections

The following calendar titles are outdated and should be renamed without changing their existing slugs:

| Priority | Current title | Corrected title |
|---|---|---|
| 17 | Maine radioactive material license: NRC regulates RAM in Maine | Maine radioactive material license: state licensing requirements and regulator guide |
| 18 | New Hampshire radioactive material license: NRC regulates RAM in New Hampshire | New Hampshire radioactive material license: state licensing requirements and regulator guide |
| 19 | Vermont radioactive material license: NRC regulates RAM in Vermont | Vermont radioactive material license: state licensing requirements and regulator guide |

The calendar also contains malformed table cells in Priorities 22–25 (`||`, `L|`, `Comp|`, and `Compl|`). Repair these during the next calendar edit.

## Pages requiring immediate verification

Review these live pages for the same jurisdiction error and update titles, headings, metadata, and body copy where necessary:

1. `/maine-radioactive-material-license/`
2. `/new-hampshire-radioactive-material-license/`
3. `/vermont-radioactive-material-license/`
4. `/nrc-vs-agreement-state-new-england/`
5. `/radioactive-material-license-reciprocity-in-new-england/`
6. `/radiation-safety-officer-qualifications-nrc-and-agreement-state-requirements/`

Do not change slugs solely to correct titles unless a redirect can be configured. Preserve existing URLs and update the page title, H1, metadata, opening answer, jurisdiction note, and internal anchor text.

## Live-site SEO/AEO observations

- The homepage has clear service positioning and a project-inquiry CTA.
- The homepage still includes a prominent `Schedule a Free Consultation` CTA. This conflicts with the repository's validation-safe strategy and should be replaced with `Submit a Project Inquiry` or `Request a Quote` unless guaranteed consultations are intentionally being offered.
- The live RSO qualifications page has a useful direct-answer structure, headings, FAQs, and related resources, but requires the Agreement State correction above.
- Search-visible content includes a mix of evergreen blog posts and newer standalone AEO pages. Internal links should use descriptive anchor text rather than bare resource titles where practical.
- The public crawl confirms multiple recent AEO pages are discoverable, but it does not establish full index coverage or canonical correctness.

## Analytics status

Authenticated Google Search Console, Bing Webmaster Tools, and WordPress/Jetpack analytics were not accessible in this run. Therefore no impressions, clicks, CTR, average-position, conversion, or coverage metrics are reported.

The repository states that Search Console, Bing, and WordPress analytics were configured, but the monthly performance review remains incomplete. Exporting the following into `analytics/search-console-notes.md` would make future prioritization evidence-based:

- Last 28 days vs previous 28 days
- Queries: clicks, impressions, CTR, average position
- Pages: clicks, impressions, CTR, average position
- Pages ranking positions 8–20
- High-impression pages with below-site-average CTR
- Indexed/not-indexed counts and reasons
- Sitemap submitted/discovered/indexed counts
- Inquiry, question, signup, and resource-download conversions by source page

## Priority order

1. Correct inaccurate Agreement State statements and page titles.
2. Replace the homepage consultation promise with validation-safe inquiry language.
3. Repair content-calendar titles and malformed table cells.
4. Complete the overdue monthly analytics review.
5. Only after accuracy and analytics review, select Priority 31+ from actual query and landing-page data.

## Suggested next AEO topics if analytics remain unavailable

1. Sealed source leak-test requirements and records
2. Radiation survey instrument calibration requirements
3. Radioactive-material inventory and reconciliation records
4. Agreement State inspection preparation
5. Responding to inspection findings and corrective actions

These remain provisional until Search Console data can be reviewed.
