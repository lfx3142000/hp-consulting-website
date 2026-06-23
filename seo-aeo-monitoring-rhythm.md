# SEO and AEO Monitoring Rhythm

This document defines the regular monitoring tasks needed to track search visibility, answer-engine visibility, content performance, technical health, and conversion signals for the Advantage Health Physics website. The goal is to maintain a lightweight but disciplined operating rhythm during the MVP validation phase, so actions stay proportional to traffic and lead volume while still surfacing meaningful patterns early.[cite:1]

## Operating principle

The website is currently in a validation MVP stage, with the near-term purpose of testing organic search traffic, answer-engine visibility, and demand signals rather than building a heavy operating stack.[cite:1] Because the current site strategy emphasizes learning which service categories and content clusters attract attention, monitoring should focus on trends, exceptions, and decision signals rather than daily over-analysis.[cite:1]

## Task frequency map

| Frequency | Task | What to review | Why it matters |
|---|---|---|---|
| Weekly | Check Google Search Console performance | Total clicks, impressions, average position, CTR, top queries, top pages, and pages gaining first impressions | Detects early traction and identifies pages or topics beginning to surface in search.[cite:1] |
| Weekly | Review indexing and coverage | Newly indexed pages, excluded pages, crawl anomalies, sitemap status, and manual indexing needs for newly published content | Confirms that published pages can actually be discovered and evaluated by search engines.[cite:1] |
| Weekly | Spot-check answer-engine readiness | FAQ-rich pages, concise answer sections, schema presence where applicable, pages with direct question headings, and pages that may be strong candidates for AI summaries | Supports the site's stated goal of testing answer-engine visibility, not just classic search rankings.[cite:1] |
| Weekly | Review lead and conversion signals | Form submissions, quote requests, submitted questions, free resource downloads, and email signups | The site is explicitly designed to collect demand signals, so these actions matter more than traffic alone.[cite:1] |
| Weekly | Review top landing pages for intent match | Whether the page answers the likely query quickly, includes a clear CTA, links to next-step pages, and reflects current service positioning | Helps determine whether traffic aligns with real consulting demand and whether content is moving visitors toward inquiry actions.[cite:1] |
| Every 2 weeks | Check internal linking health | New pages added to hubs, related service-page links, FAQ cross-links, and orphaned or weakly connected pages | Internal links are central to the repository's SEO/AEO build approach and help reinforce topical clusters.[cite:1] |
| Every 2 weeks | Review snippet quality | Title tags, meta descriptions, H1 clarity, featured-snippet-style summaries, and FAQ formatting on pages that are getting impressions | Improves the odds that impressions turn into clicks and increases answer extraction clarity for AI-driven experiences. |
| Monthly | Run the formal analytics review | Search Console trends, analytics traffic, conversion counts, top-performing clusters, weak pages, and next content/service decisions | The repository already defines a monthly validation review as part of the MVP funnel and traffic validation process.[cite:1] |
| Monthly | Assess content cluster performance | Compare service pages, free resources, and informational content by impressions, clicks, conversions, and assisted paths | Shows which topics deserve expansion and which should wait until more evidence appears.[cite:1] |
| Monthly | Review technical SEO basics | Broken links, redirect issues, page speed concerns, mobile rendering issues, schema errors, duplicate metadata, and sitemap freshness | Prevents slow technical decay that can suppress visibility even when content quality is improving. |
| Monthly | Update action log and decisions | What changed, what improved, what declined, what hypotheses emerged, and what will be changed next month | Keeps monitoring tied to decisions instead of producing passive dashboards. |
| Quarterly | Re-prioritize the roadmap | Whether to expand AEO pages beyond current priorities, strengthen service pages, create more downloadable resources, or revise CTAs | The repo notes that AEO priorities beyond the current batch should wait for evidence from the first analytics review and subsequent demand patterns.[cite:1] |
| Quarterly | Benchmark authority and trust signals | Backlinks, mentions, citations, expertise signals, testimonial readiness, and page trust gaps | Helps determine whether the site needs stronger credibility signals to compete for higher-intent queries. |
| Quarterly | Reassess measurement setup | Form tracking completeness, download tracking, source attribution, and lead-sheet reliability | The repo still lists tracking-related setup items as pending, so periodic validation is necessary until measurement is stable.[cite:1] |

## Weekly tasks

### 1. Search Console performance review

Carry out a lightweight review once per week, ideally on the same weekday. Focus on clicks, impressions, CTR, average position, top queries, and top pages, but pay most attention to directional change: pages getting first impressions, queries appearing repeatedly, and any page that suddenly gains traction or drops out.[cite:1]

### 2. Indexing and coverage check

Verify that newly published or updated pages are indexed, that the sitemap is clean, and that no important pages are excluded unexpectedly. This should also include checking for crawl anomalies or coverage warnings that could block discovery of new service or resource pages.[cite:1]

### 3. AEO spot-check

Review a small set of priority pages each week to see whether they provide a concise answer near the top, structured question-and-answer formatting, strong subhead clarity, and FAQ-style sections where appropriate. For this site, the most useful pages to inspect are service pages, high-intent question pages, and resource pages that could be surfaced by AI answer systems.[cite:1]

### 4. Conversion signal review

Because the site exists to validate demand, review the actions that matter most: project inquiries, quote requests, submitted questions, free resource downloads, and email signups. A page with modest traffic but strong inquiry behavior may be more valuable than a page with higher traffic and no downstream action.[cite:1]

## Biweekly tasks

### Internal linking review

Every two weeks, review whether newer pages are connected into the existing content clusters and whether service pages link naturally to related informational pages and resources. This is especially important because the repository already frames internal linking as part of the SEO/AEO build plan, so weak cross-linking would reduce the value of the content inventory already published.[cite:1]

### Snippet and answer-format review

Pages earning impressions but low CTR should be reviewed for title clarity, search-intent alignment, and stronger summary text near the top of the page. At the same time, pages intended for answer-engine visibility should be checked for direct question headings, concise definitions, short explanatory blocks, and scannable formatting.

## Monthly tasks

### 1. Full validation review

Run a structured monthly review that combines Search Console, site analytics, and conversion tracking. The repository describes the MVP funnel as SEO/AEO content leading to organic traffic, then inquiries or downloads, then a monthly validation review that informs the next content or service decision, so this review is the main decision point in the operating rhythm.[cite:1]

### 2. Content cluster evaluation

Group results by topic cluster rather than looking only at individual URLs. For example, compare performance across service pages, regulatory guidance posts, license-related posts, audit-related resources, and free templates to identify where the site is attracting both attention and credible buying intent.[cite:1]

### 3. Technical hygiene review

Use a monthly pass to inspect fundamentals such as broken links, redirect chains, canonical consistency, metadata duplication, schema validity, and obvious page speed problems. This does not need enterprise tooling at the MVP stage, but it should be systematic enough to catch issues before they accumulate.

### 4. Decision log update

Document what changed during the month, what signals were strongest, and what action should follow. Good outputs include decisions such as “expand radiation safety audit content,” “improve CTA placement on service pages,” or “hold off on new clusters until existing pages accumulate more impressions.”

## Quarterly tasks

### Strategic reprioritization

Every quarter, step back from page-level metrics and evaluate whether the current publishing mix is still justified. Since the repo explicitly states that further AEO content expansion should wait for analytics evidence, quarterly review is the right cadence for deciding whether to build more pages, strengthen commercial pages, or shift effort toward conversion optimization instead.[cite:1]

### Measurement audit

Quarterly review should also confirm that all major demand signals are still being captured correctly. This matters because the repository lists lead-tracker integration and download/submission tracking among the key remaining tasks, which means the measurement layer may still be evolving and needs periodic validation.[cite:1]

## Recommended operating cadence

A practical rhythm for this project is:

- Monday or Tuesday each week: 20 to 30 minute Search Console, indexing, AEO, and conversion review.
- Every other week: 30 minute internal-linking and snippet-quality review.
- Once per month: 60 to 90 minute validation review with a written action log.
- Once per quarter: 90 minute strategy and measurement audit.

## Minimum dashboard fields

To keep the process simple, track these fields in a recurring review sheet:

- Date of review.
- Total clicks and impressions.
- Top 5 gaining pages.
- Top 5 gaining queries.
- Pages with new first impressions.
- Pages with strong traffic but weak CTA performance.
- Pages with conversions or assisted conversions.
- Indexing or technical issues found.
- AEO formatting improvements needed.
- Action decisions for the next cycle.

## Thresholds for action

Use monitoring to trigger action, not just observation. Typical triggers include:

- A page gets impressions for 2 to 4 straight weeks but low CTR, revise title, meta description, and opening answer block.
- A page gets traffic but no conversions, improve CTA placement and internal links to service or inquiry pages.
- A query cluster starts appearing repeatedly, expand that topic with supporting articles, FAQs, or resource pages.
- Important pages are not indexed after submission and reasonable delay, inspect crawlability, sitemap status, and on-page quality.
- One cluster drives most conversions, prioritize adjacent high-intent pages in that cluster before broadening elsewhere.

## Suggested ownership model

If one person is running the site, combine tactical review and decision logging into a single weekly ritual plus one deeper monthly review. The monthly review should produce no more than 3 to 5 actions, so the monitoring process stays lightweight and aligned with the MVP purpose of validating demand before building heavier infrastructure.[cite:1]
