# SEO & AEO Playbook

**Version:** 2.0 | **Last Updated:** July 2026
**Reference Site:** Advantage Health Physics (advantagehealthphysics.wordpress.com)
**Repository:** lfx3142000/hp-consulting-website

---

## Table of Contents

1. [Overview](#overview)
2. [Tool Stack](#tool-stack)
3. [Phase 1 - Foundation Setup](#phase-1--foundation-setup)
4. [Phase 2 - Keyword & Content Strategy](#phase-2--keyword--content-strategy)
5. [Phase 3 - AEO (Answer Engine Optimization)](#phase-3--aeo-answer-engine-optimization)
6. [Phase 4 - Technical SEO](#phase-4--technical-seo)
7. [Phase 5 - Regulatory Content Strategy (NRC Focus)](#phase-5--regulatory-content-strategy-nrc-focus)
8. [GitHub Actions Storage Management](#github-actions-storage-management)
9. [Monthly Maintenance Checklist](#monthly-maintenance-checklist)

---

## Overview

This playbook documents the repeatable SEO and AEO workflow for all consulting and project websites under this account. It covers tool configuration, content strategy, technical maintenance, and regulatory content opportunities specific to the health physics and radiation safety niche.

**Goals:**
- Rank for high-intent health physics and radiation safety queries
- Capture AI answer engine citations (Perplexity, ChatGPT, Gemini)
- Establish topical authority around NRC regulatory compliance
- Drive inbound consulting leads via organic search

---

## Tool Stack

| Tool | Purpose | Tier |
|------|---------|------|
| Google Search Console (GSC) | Index monitoring, keyword impressions | Free |
| Google Analytics 4 (GA4) | Traffic and conversion tracking | Free |
| Ahrefs | Backlink analysis, keyword research, site audit | Paid (Lite) |
| Semrush | Competitive analysis, organic traffic insights | Free/Paid |
| Jetpack Stats | WordPress traffic overview | Free (bundled) |
| GitHub Actions | CI/CD, automated checks | Free tier |

---

## Phase 1 - Foundation Setup

### 1.1 Google Search Console
1. Go to https://search.google.com/search-console
2. Add property > URL prefix > enter site URL
3. Verify via HTML tag (WordPress: use Yoast SEO or Site Kit plugin)
4. Submit sitemap: `https://yoursite.com/sitemap.xml`
5. Request indexing for homepage and key service pages

### 1.2 Google Analytics 4
- **WordPress.com Free/Personal:** GA4 tag injection is blocked; use Jetpack Stats as proxy
- **WordPress.com Business or self-hosted:** Install GA4 via Site Kit plugin or header injection
- Create a GA4 property, copy Measurement ID (G-XXXXXXXXXX)
- Set up conversion events: `generate_lead`, `contact_form_submit`

### 1.3 Ahrefs Project Setup
1. Log in > Projects > Add project
2. Enter domain, select GSC verification
3. Enable Site Audit (crawl weekly)
4. Set up Rank Tracker with target keywords (see Phase 2)
5. Enable alerts for new/lost backlinks

### 1.4 Semrush Project Setup
1. Log in > Projects > Create project
2. Connect Organic Traffic Insights to GA4
3. Run initial Site Audit
4. Set up Position Tracking for 10-20 seed keywords

---

## Phase 2 - Keyword & Content Strategy

### 2.1 Seed Keywords - Health Physics Niche

**High-Intent Commercial:**
- health physics consulting services
- radiation safety officer consulting
- RSO services [state]
- ALARA program development
- NRC license application consultant
- radioactive material license help

**Informational / Authority:**
- NRC proposed rule changes [year]
- 10 CFR Part 20 changes
- radiation protection program requirements
- occupational dose limits NRC
- RSO qualifications requirements
- how to prepare for NRC inspection

**AEO / Featured Snippet Targets:**
- what does a health physics consultant do
- what is ALARA in radiation safety
- NRC 10 CFR Part 35 requirements
- how long does NRC license application take

### 2.2 Content Clusters

Build topical authority around these clusters:

1. **NRC Regulatory Compliance** (see Phase 5 for detail)
2. **Radiation Safety Programs** - ALARA, dosimetry, posting requirements
3. **Training & Certification** - RSO 40-hour, ABHP exam prep
4. **License Applications** - Part 30, 35, 50 byproduct material licenses
5. **Inspection Readiness** - NRC inspection checklist, common citations

### 2.3 Content Cadence

| Frequency | Content Type |
|-----------|-------------|
| Weekly | Short regulatory update post (300-500 words) |
| Bi-weekly | In-depth guide or how-to (1,000-2,000 words) |
| Monthly | Case study or service spotlight |
| As needed | NRC proposed rule comment or analysis post |

---

## Phase 3 - AEO (Answer Engine Optimization)

AEO targets AI assistants (ChatGPT, Perplexity, Gemini, Claude) that synthesize answers from indexed web content.

### 3.1 Structural Requirements
- Use clear H2/H3 question-format headings ("What is...?", "How do I...?", "When is...required?")
- Open each section with a direct 1-2 sentence answer (inverted pyramid)
- Add FAQ schema markup to all service and guide pages
- Keep paragraphs short (3-4 sentences max)
- Include definitions for technical terms (NRC jargon, CFR citations)

### 3.2 Schema Markup
Add these schema types to key pages:
- `FAQPage` - service pages and regulatory guides
- `HowTo` - step-by-step compliance guides
- `Article` - blog posts and regulatory updates
- `LocalBusiness` - homepage (include service area)
- `Person` - about page (establishes E-E-A-T)

### 3.3 E-E-A-T Signals
- **Experience:** Mention years of field experience, specific project types
- **Expertise:** List certifications (CHP, CHMM, etc.), NRC interaction experience
- **Authoritativeness:** Link to NRC.gov, Federal Register, peer-reviewed sources
- **Trustworthiness:** Display credentials, contact info, physical location/service area

### 3.4 Citation Bait Tactics
- Write posts that directly answer questions AI models are likely to be asked
- Format key facts as standalone callout boxes or blockquotes
- Create a "Quick Reference" section in each regulatory post
- Publish NRC rule change summaries within 48 hours of Federal Register publication

---

## Phase 4 - Technical SEO

### 4.1 Core Web Vitals Targets
- LCP (Largest Contentful Paint): < 2.5s
- CLS (Cumulative Layout Shift): < 0.1
- FID / INP: < 200ms

### 4.2 WordPress.com Limitations & Workarounds
| Limitation | Workaround |
|------------|------------|
| No GA4 tag on Free/Personal | Use Jetpack Stats + GSC data |
| No custom plugins on Free | Upgrade to Business for Yoast SEO |
| No custom headers/scripts | Use WordPress.com native SEO settings |

### 4.3 Sitemap & Indexing
- WordPress.com auto-generates sitemap at `/sitemap.xml`
- Submit to GSC and Bing Webmaster Tools
- Use GSC URL Inspection to force-crawl new posts
- Check crawl errors weekly in GSC Coverage report

### 4.4 Internal Linking Strategy
- Every new post links to 2-3 existing cornerstone pages
- Service pages cross-link to relevant regulatory guides
- Use descriptive anchor text (not "click here")

---

## Phase 5 - Regulatory Content Strategy (NRC Focus)

This is the highest-leverage content opportunity for Advantage Health Physics. NRC proposed rule changes generate specific, time-sensitive search demand that competitors largely ignore.

### 5.1 Why NRC Rule Change Content Matters

- **Low competition:** Most health physics consulting sites do not publish timely regulatory analysis
- **High authority signal:** Demonstrates deep regulatory expertise to users and AI models alike
- **Evergreen + timely:** Rule changes create an initial traffic spike, then sustained long-tail traffic as the rule takes effect
- **Lead generation:** Prospects searching for rule change implications are actively assessing compliance exposure - they are consulting-ready prospects
- **AEO gold:** AI assistants frequently cite authoritative summaries of regulatory changes; being first and thorough increases citation likelihood

### 5.2 Current High-Priority NRC Proposed Rules (Monitor These)

| Rulemaking | CFR Part | Content Opportunity |
|------------|----------|---------------------|
| Radiation Protection Modernization | 10 CFR Part 20 | Dose limit changes, ALARA updates |
| Medical Use of Byproduct Material | 10 CFR Part 35 | Therapy and imaging license impacts |
| Low-Level Radioactive Waste Disposal | 10 CFR Part 61 | Disposal site criteria changes |
| Advanced Nuclear Reactor Licensing | 10 CFR Parts 50/52 | New framework impacts |
| Enhanced WRN Security Requirements | Various | Security plan updates |

*Monitor: https://www.nrc.gov/about-nrc/regulatory/rulemaking/regs-being-developed.html*

### 5.3 Content Templates for NRC Rule Change Posts

**Template A - Proposed Rule Summary (publish within 48 hrs of Federal Register notice)**
```
Title: NRC Proposes Changes to [Part XX]: What [Audience] Need to Know

H2: What is Being Proposed?
H2: Who is Affected?
H2: Key Changes from Current Requirements
H2: Comment Period and Timeline
H2: How to Prepare Now
CTA: Contact Advantage Health Physics for a compliance gap assessment
```

**Template B - Final Rule Compliance Checklist (publish when final rule is issued)**
```
Title: [Part XX] Final Rule: Compliance Checklist for [License Type]

H2: What Changed from the Proposed Rule?
H2: Effective Date and Compliance Deadlines
H2: Step-by-Step Compliance Checklist
H2: Common Mistakes to Avoid
H2: Do You Need Help Getting Into Compliance?
CTA: Schedule a compliance review
```

**Template C - Evergreen FAQ (publish for any active or recent rule)**
```
Title: [Topic]: Frequently Asked Questions
Format: FAQ schema with direct answers
Target: AEO / featured snippet capture
```

### 5.4 Federal Register Monitoring Workflow
1. Subscribe to NRC email updates: https://public-blog.nrc-gateway.gov/subscribe/
2. Monitor Federal Register RSS for NRC actions: https://www.federalregister.gov/agencies/nuclear-regulatory-commission
3. Set Google Alert: `"NRC" "proposed rule" site:federalregister.gov`
4. Set Ahrefs content alerts for competitor content on NRC keywords
5. Publish within 48 hours of any significant proposed rule notice

### 5.5 Target Keywords by Rule Area

**10 CFR Part 20 (Radiation Protection):**
- NRC Part 20 proposed changes 2025 2026
- occupational dose limit changes NRC
- ALARA program updates NRC rule
- radiation protection program modernization

**10 CFR Part 35 (Medical Use):**
- NRC Part 35 proposed rule
- medical use byproduct material license changes
- NRC authorized medical physicist requirements

**10 CFR Part 61 (Low-Level Waste):**
- NRC Part 61 rule changes
- low-level radioactive waste disposal requirements
- NRC LLRW site criteria

**General Regulatory:**
- NRC proposed rulemaking 2025 2026
- how to comment on NRC proposed rule
- NRC final rule compliance deadline
- NRC rulemaking tracker

---

## GitHub Actions Storage Management

### Problem
GitHub Actions artifact storage has a 0.5 GB free tier limit. Accumulated build artifacts caused 100% storage usage (confirmed July 2026).

### Solution Applied
Added `retention-days: 1` to all `actions/upload-artifact` steps in non-critical CI workflows across 4 repositories.

### Standard YAML Pattern
```yaml
- name: Upload build artifacts
  uses: actions/upload-artifact@v4
  with:
    name: build-output
    path: ./dist
    retention-days: 1  # Prevents storage accumulation on free tier
```

### Ongoing Policy
- All new CI workflows: `retention-days: 1` unless artifacts are needed for deployment
- Production deployment artifacts: `retention-days: 7` maximum
- Audit storage quarterly at: https://github.com/settings/billing

---

## Monthly Maintenance Checklist

### Week 1 - Performance Review
- [ ] GSC: Check impressions, clicks, average position for target keywords
- [ ] GSC: Review Coverage report for crawl errors
- [ ] GA4 / Jetpack: Review top pages and traffic sources
- [ ] Ahrefs: Check rank tracker movement
- [ ] Review Core Web Vitals in GSC Experience report

### Week 2 - Content
- [ ] Publish at least 1 new post (regulatory update preferred)
- [ ] Check Federal Register for new NRC proposed rules
- [ ] Update posts referencing pending rules with new status
- [ ] Add internal links from new post to 2-3 existing pages

### Week 3 - Technical
- [ ] Run Ahrefs Site Audit, fix new issues
- [ ] Check backlink profile for new/lost links
- [ ] Verify sitemap is current and resubmit if new pages added
- [ ] Test contact forms and CTAs

### Week 4 - Strategy
- [ ] Review competitor content for keyword gaps
- [ ] Identify 3 new keyword targets for next month
- [ ] Check GitHub Actions storage usage
- [ ] Review and update this playbook as needed

---

*Maintained by: lfx3142000 | Advantage Health Physics Consulting*
*NRC Rulemaking Reference: https://www.nrc.gov/about-nrc/regulatory/rulemaking/regs-being-developed.html*
