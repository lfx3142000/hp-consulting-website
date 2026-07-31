# SEO/AEO Status Review — 2026-07-31

**Scope:** Live-site review of Advantage Health Physics WordPress site against repository strategy, content calendar, and SEO/AEO task queue.  
**Live site:** https://advantagehealthphysics.wordpress.com  
**Repository:** `lfx3142000/hp-consulting-website`  
**Data sources:** SEMrush Position Tracking, WordPress Jetpack Stats, live site inspection  

---

## SEO Metrics (SEMrush Position Tracking)

| Metric | Value | Delta vs Jul 27 |
|--------|-------|------------------|
| Visibility | 3.43% | 0 (flat) |
| Est. Traffic | 0 | 0 |
| Referring Domains | 0 | 0 |
| Keywords Tracked | 10 | 0 |

### Keyword Rankings (Jul 31, 2026)

| Keyword | Position | Target |
|---------|----------|--------|
| industrial radiation safety | 2 | Top 3 ✓ |
| health physics services | 3 | Top 3 ✓ |
| radiation safety services | 3 | Top 3 ✓ |
| health physicist | 4 | Top 5 ✓ |
| health physics consulting | 4 | Top 5 ✓ |
| medical health physics | 5 | Top 5 ✓ |
| nrc radiation safety regulations | 7 | Top 10 ✓ |
| radiation safety consultant | 7 | Top 10 ✓ |
| radiation protection consultant | 8 | Top 10 ✓ |

**Note:** All 9 tracked keywords rank in positions 2–8. However, visibility dropped sharply from ~10% (Jul 22) to 3.43% (Jul 24) and has been flat since. This drop is consistent with zero backlinks — Google is discounting the site's authority without external signals.

---

## AEO (Answer Engine Optimization) Status

| AEO Signal | Status | Notes |
|------------|--------|-------|
| Schema markup (FAQ, Service) | Unknown | Not confirmed via Google Rich Results Test |
| Featured snippet eligibility | Low | No long-form Q&A content detected |
| Google Business Profile | Missing | Not created yet — critical for local AEO |
| AI Overview appearances | Not tracked | Need GSC + manual search monitoring |
| Structured content (H2/H3 Q&A format) | Partial | Blog posts exist but not fully optimized for AEO |
| Entity consistency (NAP) | Partial | Name/Address/Phone not consistent across web |

---

## Traffic (Jetpack Stats — Last 7 Days)

| Date | Views |
|------|-------|
| Jul 25 | 0 |
| Jul 26 | 0 |
| Jul 27 | 0 |
| Jul 28 | 0 |
| Jul 29 | ~4 |
| Jul 30 | 0 |
| Jul 31 | ~3 |

**Total 7-day views:** ~7  
**Est. organic traffic from SEMrush:** 0  
The small view counts are likely direct/referral traffic, not search-driven.

---

## Critical Issues

### 1. Zero Backlinks (HIGHEST PRIORITY)
- 0 referring domains as of today
- Visibility plateau at 3.43% is directly tied to lack of external authority
- **Action:** Execute `docs/backlink-strategy.md` Tier 1 actions immediately

### 2. Google Business Profile Missing
- No local SEO / AEO coverage
- GBP is a free, high-DA backlink and AEO signal
- **Action:** Create GBP listing this week

### 3. No Schema Markup Confirmed
- Service schema, FAQ schema not verified
- Prevents eligibility for Google rich results and AI Overviews
- **Action:** Add/verify schema via WordPress Yoast or RankMath plugin

### 4. No AEO-Optimized Content
- No dedicated FAQ pages or Q&A blog posts in "What is..." format
- AI assistants (ChatGPT, Perplexity, Gemini) cannot easily surface the site
- **Action:** Publish 3–5 FAQ-format posts targeting "What is a radiation safety consultant?" type queries

---

## Completed Since Last Audit (Jul 27)

- [x] Backlink strategy documented (`docs/backlink-strategy.md`)
- [x] SEMrush position tracking confirmed active with 10 keywords
- [x] Visibility and keyword positions monitored

---

## Next Actions (Priority Order)

1. [ ] Submit site to HPS links page (hps.org/links)
2. [ ] Create Google Business Profile
3. [ ] Create LinkedIn Company Page with site URL
4. [ ] Submit to AAHP and AAPM directories
5. [ ] Verify schema markup via Google Rich Results Test
6. [ ] Publish FAQ-format blog post for AEO
7. [ ] Publish NRC inspection statistics data page for link-bait
8. [ ] Add 5 more keywords to SEMrush tracking (long-tail: "RSO training course", "radiation safety officer training", etc.)

---

## SEO Health Score Summary

| Category | Score | Trend |
|----------|-------|-------|
| On-Page SEO | 7/10 | → Stable |
| Keyword Rankings | 7/10 | → Stable |
| Authority / Backlinks | 1/10 | ↓ Critical |
| AEO Readiness | 3/10 | → Stable |
| Traffic | 2/10 | ↑ Slight uptick |
| Technical SEO | 6/10 | → Stable |
| **Overall** | **4/10** | **↓ Needs backlinks urgently** |
