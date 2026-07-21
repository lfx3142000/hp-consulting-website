SEO & AEO Playbook
Version: 1.0 | Last Updated: July 2026
Reference Site: Advantage Health Physics (advantagehealthphysics.wordpress.com)

Table of Contents
Overview

Tool Stack

Phase 1 — Foundation Setup

Phase 2 — Keyword & Content Strategy

Phase 3 — AEO (Answer Engine Optimization)

Phase 4 — Technical SEO

Phase 5 — Off-Page & Authority

Recurring Health Checks

Tool Configuration Checklist

GitHub Actions Storage Management

Applying This Playbook to a New Site

1. Overview
This playbook covers both SEO (Search Engine Optimization) and AEO (Answer Engine Optimization) for small professional and consulting websites. AEO specifically targets AI assistants and answer engines — Perplexity, ChatGPT Browse, Google AI Overviews, and voice search — in addition to traditional search engines like Google and Bing.

Goals:

Get fully indexed and verified across all major search and answer platforms

Rank for niche, low-competition long-tail keywords relevant to your specialty

Appear in AI-generated answers for professional and service-based queries

Track organic traffic and keyword performance via GA4 and Semrush

Who this is for: Consultants, small service businesses, and niche professional sites launching on WordPress.com or self-hosted WordPress.

2. Tool Stack
Tool	Purpose	Required Plan	Cost
Google Search Console	Indexing, crawl health, keyword impressions	Free	$0
Google Analytics 4 (GA4)	Traffic, user behavior, conversion tracking	Free	$0
Ahrefs	Backlink analysis, keyword research, site audit	Free (limited)	$0
Semrush	Organic Traffic Insights, keyword gap, competitor research	Free (limited)	$0
WordPress.com	CMS and hosting	Free / Creator+	$0–$16/mo
Google Tag Manager	Optional — advanced tag management	Free	$0
WordPress.com Plan Note: Google Analytics tag installation requires Creator plan or higher ($16/mo). On the free plan, use Jetpack Stats as a temporary fallback, or upgrade when budget allows. All other tools work regardless of plan tier.

3. Phase 1 — Foundation Setup
3.1 Google Search Console
Go to search.google.com/search-console

Click Add Property → enter your full URL (e.g., https://yoursite.wordpress.com/)

Select URL prefix method

Verify ownership using one of these methods:

HTML meta tag → paste into WordPress: Settings > Traffic > Site Verification > Google

Google Analytics → automatic if GA4 tag is already installed

DNS TXT record → best for custom domains

Submit your sitemap: Settings > Sitemaps → enter sitemap.xml

WordPress.com auto-generates: https://yoursite.wordpress.com/sitemap.xml

Confirm: Settings should show "You are a verified owner"

3.2 Google Analytics 4
Go to analytics.google.com

Create account → Create property → Choose Web

Enter site name and URL → Get your Measurement ID (format: G-XXXXXXXXXX)

Install the tracking tag:
Platform	Method
WordPress.com Creator+	WP Admin > Settings > Traffic > Google Analytics → paste Measurement ID
WordPress.com Free	Upgrade required — use Jetpack Stats as fallback
Self-hosted WordPress	Install Google Site Kit plugin
Custom site	Add gtag.js snippet to <head> of every page

Verify: GA4 dashboard → Reports → Realtime → visit your site to confirm hits

3.3 Ahrefs Site Verification
Go to app.ahrefs.com → Dashboard → Add Project

Enter your domain

Choose verification method:

Google Search Console (recommended) — requires OAuth authorization to your Google account

HTML tag — paste the tag into WordPress: Settings > Traffic > Site Verification > Google

HTML file — upload to site root (requires FTP/file access)

Click Verify — project status changes from Frozen → Active

Run initial Site Audit to establish a baseline health score

Environment note: If OAuth popups are blocked (e.g., browser automation contexts), use the HTML tag method. The same Google verification field in WordPress Traffic settings accepts both GSC and Ahrefs tags.

3.4 Semrush Project Setup
Go to semrush.com → Projects → Create Project

Enter domain and project name

Open Organic Traffic Insights within the project:

Click Connect Google Account → complete OAuth

Select GA4: Account → Property → Data Stream

Select Search Console property matching your domain

Set Location (e.g., United States) and Device (All)

Allow 24–48 hours for initial data to populate

Semrush combines GSC keyword data with GA4 behavior data for unified reporting

4. Phase 2 — Keyword & Content Strategy
4.1 Niche Keyword Targeting
For professional and consulting sites, prioritize long-tail, low-competition keywords over broad terms. Generic terms like "consultant" have enormous competition; niche combinations have far less.

Keyword formula patterns:

Pattern	Example
[Service] + [Location]	"radiation safety consulting Boston"
[Service] + [Industry]	"RSO services for healthcare facilities"
[Problem] + [Solution]	"radiation badge program small business"
[Question] + [Topic]	"how to set up a radiation safety program"
[Certification] + [Topic]	"40 hour RSO training online"
[Regulation] + [Compliance]	"NRC license requirements medical facility"
Research process:

Seed keywords in Semrush Keyword Magic Tool

Filter: KD (Keyword Difficulty) < 30, Volume > 50/mo

Export top 30 → group by topic/pillar

Map one primary keyword per page — no keyword cannibalization

4.2 Content Pillars
Build your site architecture around 3–5 core content pillars:

Pillar	Page Types	AEO Value
Services Overview	What you offer, pricing models, process	High — answers "what does X do"
Regulatory Compliance	NRC, state regs, license types	High — answers compliance questions
Training & Certification	RSO training, worker training, schedules	Medium — captures training queries
FAQ / Q&A Hub	Comprehensive question-answer library	Very High — direct AEO target
Case Studies	Real problems solved (anonymized)	Medium — builds trust + E-E-A-T
Each pillar should have:

One pillar page (long-form, 1500+ words, comprehensive overview)

3–5 cluster pages (focused, 600–900 words, single subtopic)

Internal links between cluster pages and the pillar page

4.3 Content Calendar
Frequency	Type	Goal
2x/month	Blog post (cluster page)	Build topical authority
1x/quarter	Pillar page update	Keep evergreen content fresh
Ongoing	FAQ additions	Expand AEO surface area
5. Phase 3 — AEO (Answer Engine Optimization)
AEO is the practice of structuring content so AI assistants (Perplexity, ChatGPT, Google AI Overviews) can extract and cite it as a direct answer. It complements SEO — pages that rank well in traditional search are also more likely to be cited by AI.

5.1 The Core AEO Principle
AI engines look for the most direct, credible answer to a question. Your content competes not just for a blue link but to be quoted verbatim as the answer.

AEO content rules:

Lead with the answer — first 1–2 sentences must directly answer the page's primary question

Use question-phrased headers — ## What is a Radiation Safety Officer? not ## RSO Overview

Short paragraphs — 2–3 sentences max; AI systems extract at the paragraph level

Bulleted lists for steps, features, and comparisons — easily quoted

Define terms — include clear definitions early in any technical content

Cite authoritative sources — NRC, EPA, OSHA, peer-reviewed journals

FAQ section on every service page — minimum 5 Q&A pairs

5.2 Schema Markup
Structured data signals directly to search engines and AI crawlers what your content means. Add JSON-LD to page <head> or via a schema plugin.

FAQ Schema (most important for AEO):

json
{
  "@context": "https://schema.org",
  "@type": "FAQPage",
  "mainEntity": [
    {
      "@type": "Question",
      "name": "What does a health physics consultant do?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "A health physics consultant advises organizations on radiation safety programs, regulatory compliance with NRC and state agencies, and the design of radiation protection measures for workers and the public."
      }
    },
    {
      "@type": "Question",
      "name": "Do I need a Radiation Safety Officer?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "Most NRC and Agreement State licenses require a designated Radiation Safety Officer (RSO). The RSO is responsible for implementing the radiation protection program and ensuring regulatory compliance."
      }
    }
  ]
}
LocalBusiness Schema (for local service businesses):

json
{
  "@context": "https://schema.org",
  "@type": "ProfessionalService",
  "name": "Advantage Health Physics",
  "url": "https://advantagehealthphysics.wordpress.com",
  "description": "Health physics consulting services for regulatory compliance, RSO support, and radiation safety programs.",
  "areaServed": "United States",
  "knowsAbout": ["radiation safety", "health physics", "NRC compliance", "RSO services"]
}
Validation: Test at schema.org/validator and search.google.com/test/rich-results

5.3 E-E-A-T Signals
Google and AI engines both reward Experience, Expertise, Authoritativeness, Trustworthiness. These signals make your content more likely to be cited.

Checklist:

Author bio on every page — include credentials (CHP, MS, PhD, certifications)

Dedicated About page with full professional background

LinkedIn profile linked from site

Client testimonials or anonymized case references

External citations — published papers, conference presentations, training completions

NAP consistency — identical Name, Address, Phone across all platforms

Privacy policy and terms pages present (trust signals)

Contact page with a real email and/or phone number

5.4 Directories & Citations
Submit to these to build authority and local signals:

Directory	Priority	Notes
Google Business Profile	Critical	Required for local search
LinkedIn Company Page	High	B2B visibility
Health Physics Society	High	Niche authority
Bing Places	Medium	Bing + Cortana integration
Yelp / BBB	Medium	General trust signals
NRC-adjacent professional listings	High	Niche authority
6. Phase 4 — Technical SEO
6.1 On-Page Checklist (Every Page)
Title tag: 50–60 characters, primary keyword near the front

Meta description: 150–160 characters, action-oriented, includes keyword

H1: Exactly one per page, matches primary keyword intent

H2/H3: Logical hierarchy, question-phrased where possible

Images: Alt text on every image; descriptive, keyword-aware filenames

Internal links: Minimum 2–3 per page to related content

URL structure: Short, lowercase, hyphenated, keyword-rich (e.g., /radiation-safety-officer-services)

Word count: Pillar pages 1500+, cluster pages 600–900, FAQ answers 100–150 each

Outbound links: At least 1–2 links to authoritative external sources per page

6.2 Site-Level Technical Checks
HTTPS/SSL enabled (included on WordPress.com)

Sitemap at /sitemap.xml and submitted to GSC and Bing Webmaster Tools

robots.txt not blocking important pages or JS/CSS

No broken links (crawl monthly with Ahrefs Site Audit)

Canonical tags on any duplicate or near-duplicate content

Core Web Vitals passing:

LCP (Largest Contentful Paint) < 2.5s

FID (First Input Delay) < 100ms

CLS (Cumulative Layout Shift) < 0.1

Mobile-friendly (test at search.google.com/test/mobile-friendly)

Page speed < 3s (test at pagespeed.web.dev)

6.3 WordPress.com Traffic Settings
Navigate to WP Admin > Settings > Traffic:

Setting	Action
Google Site Verification	Paste HTML meta tag (from GSC or Ahrefs)
Bing Site Verification	Paste Bing Webmaster Tools verification tag
Google Analytics	Paste GA4 Measurement ID (Creator plan required)
SEO Title Formats	Customize for posts, pages, homepage
Front Page Meta Description	Write a concise 155-char site description
7. Phase 5 — Off-Page & Authority
7.1 Backlink Strategy
Quality backlinks remain one of the strongest ranking signals for both traditional SEO and AI citation likelihood. Focus on relevance over quantity.

Priority sources:

Professional associations (Health Physics Society, AAHP, state radiation control programs)

Guest posts or expert quotes on industry blogs

University/research institution mentions or partnerships

Local business directories (Chamber of Commerce, local government)

Press releases for certifications, milestones, or new services

Tactics:

HARO / Qwoted — respond to journalist queries in your specialty

Broken link building — find broken links on niche sites, offer your content as replacement

Resource pages — request listing on "radiation safety

