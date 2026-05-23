# HP Consulting Website — TASKS.md

## Project Summary

Build and update the Advantage Health Physics website as a professional health physics / radiation safety consulting and resource website.

The website already has a substantial first draft: homepage, About page, Services page, Training page, Contact page, multiple service pages, and several SEO blog posts. The next stage is to clean up the live WordPress site, strengthen the quote-request funnel, add free downloadable resources for email capture, and organize SEO/AEO content around high-intent radiation safety questions.

The current project goal is to test market demand while presenting the site as a credible consulting business. Visitors should be able to request a quote, submit project inquiries, download free resources, and join an email list. The backend workflow should remain simple and mostly manual until demand is validated.

Primary goals:

1. Present a credible radiation safety / health physics consulting website.
2. Generate traffic through SEO and AEO content.
3. Capture quote requests and project inquiries.
4. Offer useful free resources in exchange for email signups.
5. Learn which health physics / radiation safety topics generate interest.
6. Delay complex consulting operations until demand is clearer.

Primary CTA:

> Request a quote for radiation safety, RSO, licensing, audit, training, shielding, instrumentation, or compliance support.

Secondary CTAs:

> Download a free radiation safety template or checklist.  
> Submit a radiation safety question.  
> Join the update list.

---

## Current Live Site Review

Reviewed site: `https://advantagehealthphysics.wordpress.com`

### What Already Exists

The live site already includes:

- Homepage with consulting positioning and core service summary.
- About page with professional background, regulatory expertise, consulting approach, technical capabilities, and service area.
- Services page with six major service categories.
- Training page with radiation worker, RSO, authorized user, and RSC training descriptions.
- Contact page with email address and contact form.
- Blog page with multiple SEO posts.
- Individual service pages for:
  - Radioactive Material License Consulting
  - Radiation Safety Audits and Mock NRC Inspections
  - Radiation Safety Program Development
  - RSO Consulting and Ongoing Compliance Support
  - Radiation Surveys
- Existing email: `info@advantagehealthphysics.com`
- Existing service area language: New England for in-person work and nationwide for remote consulting.

### Major Issues Found

The site is usable but needs cleanup and conversion improvements:

1. Homepage still includes WordPress template text such as “Welcome to WordPress.com” and placeholder sections.
2. Sidebar/footer includes default WordPress text widgets that should be removed or replaced.
3. Contact form exists but is generic; it should become a stronger quote-request form.
4. CTAs use “consultation” and “contact us,” but the desired primary CTA is “Request a Quote.”
5. Contact page promises response within one business day; consider softening unless that response time is realistic.
6. Blog posts exist, but they need better internal linking, CTAs, FAQ sections, and freebie/email capture placement.
7. Free downloadable templates/checklists are not yet implemented as lead magnets.
8. Site still shows WordPress.com branding and default template elements.
9. Blog comments appear enabled; consider disabling unless there is a reason to accept comments.
10. There is no clear resource/freebie landing page yet.
11. There is no obvious privacy/disclaimer/terms page customized for the business.
12. There is no clear analytics/SEO tracking plan documented in the repo.

---

## Status Key

| Status | Meaning |
|---|---|
| ✅ Done | Complete enough for current MVP |
| 🟡 Needs Update | Exists but should be improved |
| ⬜ Pending | Not started or not visible on live site |
| ⏸ Deferred | Do later after validation |
| ❌ Remove / Avoid | Do not build for this MVP |

---

## Deliverable Locations

| Deliverable | Location |
|---|---|
| Live website | `https://advantagehealthphysics.wordpress.com` |
| Future/custom domain | `https://advantagehealthphysics.com` |
| GitHub repo | `hp-consulting-website` |
| Main project task file | `/TASKS.md` |
| Page drafts | `/page-drafts/` |
| SEO/AEO content plan | `/content-plan/` |
| Blog/resource drafts | `/content-plan/` and `/page-drafts/` |
| Forms copy/specs | `/forms/` |
| Freebie / lead magnet drafts | `/freebies/` |
| Email templates | `/email-templates/` |
| Analytics notes | `/analytics/` |
| Future consulting workflow notes | `/future-funnel/` |
| Notion notes | Comet Notebook → HP Auto |
| WordPress admin | Stored separately in secure storage |
| Email/signup tracking | Google Sheet, Airtable, WordPress export, or email marketing platform |

---

# Task List

## 1. Immediate Live Site Cleanup

These are the highest-priority tasks because they affect credibility immediately.

| # | Task | Status | Deliverable Location | Notes |
|---|---|---:|---|---|
| 1.1 | Remove WordPress homepage template text | ⬜ Pending | WordPress homepage | Remove “Welcome to WordPress.com” and other starter-template copy |
| 1.2 | Remove or replace default sidebar/footer text widgets | ⬜ Pending | WordPress Customizer / Widgets | Replace with quote CTA, resource signup, or remove entirely |
| 1.3 | Remove “Add a Video” placeholder section | ⬜ Pending | WordPress homepage | Replace with trust section, service cards, or free resource CTA |
| 1.4 | Replace generic “Call to Action” links | ⬜ Pending | WordPress homepage/template | Point to Request a Quote or Resources page |
| 1.5 | Disable blog comments unless intentionally used | ⬜ Pending | WordPress discussion settings | Comments are likely unnecessary for a consulting/resource site |
| 1.6 | Remove visible default WordPress demo/template artifacts | ⬜ Pending | WordPress theme/settings | Improve professionalism |
| 1.7 | Review mobile appearance | ⬜ Pending | Live site | Confirm menu, forms, and CTAs work on phone |
| 1.8 | Check all internal service links | ⬜ Pending | Live site | Make sure all “Learn more” and CTA links go to intended pages |
| 1.9 | Replace “free initial consultation” language where needed | 🟡 Needs Update | Homepage, About, Services, Contact | Preferred CTA is “Request a Quote” |
| 1.10 | Soften response-time promise if needed | 🟡 Needs Update | Contact page | Current page says response within one business day; only keep if realistic |

---

## 2. Website Repositioning and Core Pages

The site should look commercially available, with a lightweight quote-request funnel.

| # | Task | Status | Deliverable Location | Notes |
|---|---|---:|---|---|
| 2.1 | Refresh homepage copy | 🟡 Needs Update | `/page-drafts/home.md` and WordPress homepage | Existing homepage is strong but needs cleanup, stronger quote CTA, and no placeholder sections |
| 2.2 | Refresh About page | 🟡 Needs Update | `/page-drafts/about.md` and WordPress About page | Existing About page is good; add CTA to request quote and maybe more concise credibility structure |
| 2.3 | Refresh Services page | 🟡 Needs Update | `/page-drafts/services.md` and WordPress Services page | Existing Services page is good; make each service card route to quote/freebie/content |
| 2.4 | Convert Contact page into Request a Quote / Inquiry page | 🟡 Needs Update | `/page-drafts/request-a-quote.md`, `/forms/quote-request-form.md`, WordPress Contact page | Current form is too generic |
| 2.5 | Create dedicated Request a Quote page | ⬜ Pending | `/page-drafts/request-a-quote.md` and `/forms/quote-request-form.md` | Main conversion page; can either replace Contact or exist separately |
| 2.6 | Create Resources page | ⬜ Pending | `/page-drafts/resources.md` | Hub for articles, templates, checklists, and guides |
| 2.7 | Create Free Resources / Templates page | ⬜ Pending | `/page-drafts/free-radiation-safety-templates.md` | Landing page for email-gated freebies |
| 2.8 | Create Submit a Radiation Safety Question page | ⬜ Pending | `/page-drafts/submit-a-question.md` and `/forms/submit-question-form.md` | Capture SEO/AEO topic ideas |
| 2.9 | Add footer CTA | ⬜ Pending | WordPress footer/theme settings | “Need radiation safety support? Request a quote.” |
| 2.10 | Add privacy policy | ⬜ Pending | `/page-drafts/privacy-policy.md` | Needed for email capture and forms |
| 2.11 | Add terms/disclaimer page | ⬜ Pending | `/page-drafts/terms-disclaimer.md` | Include informational-use and no guaranteed engagement language |

Suggested primary CTA language:

```text
Need radiation safety, RSO, licensing, audit, training, shielding, instrumentation, or compliance support?

Request a quote and describe your project. We will review the information and follow up if the project appears to be a good fit.
```

Suggested softer response language:

```text
We review quote requests and project inquiries as they are received. If the project appears to be a good fit, we may follow up for additional details.
```

---

## 3. Existing Service Pages

These pages already exist and should be improved rather than recreated from scratch.

| # | Existing Page | Status | Deliverable Location | Next Update |
|---|---|---:|---|---|
| 3.1 | Radioactive Material License Consulting | 🟡 Needs Update | `/page-drafts/radioactive-material-license-consulting.md` | Add quote CTA, related blog links, and license amendment worksheet freebie |
| 3.2 | Radiation Safety Audits and Mock NRC Inspections | 🟡 Needs Update | `/page-drafts/radiation-safety-audits.md` | Add audit checklist freebie and quote CTA |
| 3.3 | Radiation Safety Program Development | 🟡 Needs Update | `/page-drafts/radiation-safety-program-development.md` | Add program audit checklist and document index freebie |
| 3.4 | RSO Consulting and Ongoing Compliance Support | 🟡 Needs Update | `/page-drafts/rso-consulting.md` | Add RSO inspection readiness checklist and quote CTA |
| 3.5 | Radiation Safety Training | 🟡 Needs Update | `/page-drafts/training.md` | Add training attendance form template and email signup |
| 3.6 | Radiation Surveys | 🟡 Needs Update | `/page-drafts/radiation-surveys.md` | Add radiation survey record template and survey quote CTA |

Service page update checklist:

```text
[ ] Add clear Request a Quote CTA near top and bottom
[ ] Add related freebie / download CTA
[ ] Add related blog/resource links
[ ] Add FAQ section
[ ] Add “Who this is for” section
[ ] Add “Typical deliverables” section if missing
[ ] Add disclaimer: scope depends on license, jurisdiction, and facility conditions
[ ] Add internal links to related services
```

---

## 4. WordPress MVP Setup

Keep the WordPress stack simple. Avoid heavy plugins and complex automation until traffic and leads justify it.

| # | Task | Status | Deliverable Location | Notes |
|---|---|---:|---|---|
| 4.1 | Confirm active WordPress theme | ⬜ Pending | `/analytics/site-setup-notes.md` | Note theme name and limitations |
| 4.2 | Confirm page editor workflow | ⬜ Pending | `/analytics/site-setup-notes.md` | Prefer Gutenberg/block editor |
| 4.3 | Confirm SEO plugin or WordPress.com SEO capability | ⬜ Pending | WordPress admin + `/analytics/site-setup-notes.md` | Rank Math/Yoast may depend on WordPress plan |
| 4.4 | Confirm forms capability | 🟡 Needs Update | WordPress admin + `/forms/` | Current contact form exists but needs better fields |
| 4.5 | Confirm email notification delivery | ⬜ Pending | WordPress admin | Make sure form submissions reach correct inbox |
| 4.6 | Add spam protection to forms if available | ⬜ Pending | WordPress admin | Cloudflare Turnstile, reCAPTCHA, Akismet, or WordPress.com equivalent |
| 4.7 | Confirm backup/export method | ⬜ Pending | WordPress admin / hosting | Export content periodically |
| 4.8 | Confirm sitemap is generated | ⬜ Pending | SEO plugin or WordPress.com sitemap | Submit to search engines |
| 4.9 | Set up Google Search Console | ⬜ Pending | Google Search Console | Required for SEO measurement |
| 4.10 | Set up Bing Webmaster Tools | ⬜ Pending | Bing Webmaster Tools | Useful for AEO/search visibility |
| 4.11 | Set up analytics | ⬜ Pending | GA4, Jetpack stats, Site Kit, Plausible, or similar | Track traffic and conversions |

---

## 5. Quote Request and Lead Capture

The site should allow quote requests, but the process should remain manual and selective.

| # | Task | Status | Deliverable Location | Notes |
|---|---|---:|---|---|
| 5.1 | Build improved Request a Quote form | ⬜ Pending | `/forms/quote-request-form.md` | Main conversion form |
| 5.2 | Add quote request form to website | ⬜ Pending | WordPress page: `/request-a-quote/` or `/contact/` | Primary CTA destination |
| 5.3 | Create form confirmation message | ⬜ Pending | `/forms/quote-request-confirmation.md` | “Received and will review; may follow up if good fit” |
| 5.4 | Create internal lead tracking sheet | ⬜ Pending | Google Sheet, Airtable, or WordPress export | Track submissions manually |
| 5.5 | Create lead category tags | ⬜ Pending | `/forms/lead-categories.md` | RSO, RAM license, training, audit, DOT/IATA, shielding, survey, waste |
| 5.6 | Create quote request email acknowledgement | ⬜ Pending | `/email-templates/quote-request-acknowledgement.md` | Polite response; request details if needed |
| 5.7 | Create project inquiry form | ⬜ Pending | `/forms/project-inquiry-form.md` | For visitors not ready for formal quote |
| 5.8 | Create submit-a-question form | ⬜ Pending | `/forms/submit-question-form.md` | Use questions to guide content |
| 5.9 | Create update list signup form | ⬜ Pending | `/forms/update-list-form.md` | General email capture |
| 5.10 | Add consent checkbox for email updates | ⬜ Pending | All forms | Needed for list-building clarity |

Suggested quote request form fields:

```text
Name
Email
Organization
Organization type
State / region
Project type
Brief project description
Desired timeline
Relevant radioactive material / radiation source, if applicable
Current license status, if applicable
What kind of support is needed?
Permission to contact about this inquiry
Optional: join update list
```

Suggested confirmation language:

```text
Thank you for submitting a quote request. Your information has been received and will be reviewed. If the project appears to be a good fit, we may follow up for additional details.
```

---

## 6. Freebies / Lead Magnets for Email List

Offer useful radiation safety templates, checklists, and forms in exchange for an email signup. These should be practical, lightweight, and valuable enough that radiation safety staff, EHS staff, lab managers, or small licensees would download them.

| # | Freebie / Lead Magnet | Status | Deliverable Location | Related Page / Funnel |
|---|---|---:|---|---|
| 6.1 | Radiation Safety Program Audit Checklist | ⬜ Pending | `/freebies/radiation-safety-program-audit-checklist.md` | Audits, RSO, program development |
| 6.2 | RSO Inspection Readiness Checklist | ⬜ Pending | `/freebies/rso-inspection-readiness-checklist.md` | RSO consulting, NRC inspection posts |
| 6.3 | RAM License Amendment Planning Worksheet | ⬜ Pending | `/freebies/ram-license-amendment-planning-worksheet.md` | License consulting |
| 6.4 | Radiation Safety Training Attendance Form Template | ⬜ Pending | `/freebies/training-attendance-form-template.md` | Training page |
| 6.5 | Radiation Survey Record Template | ⬜ Pending | `/freebies/radiation-survey-record-template.md` | Radiation surveys page |
| 6.6 | Contamination/Wipe Test Log Template | ⬜ Pending | `/freebies/wipe-test-log-template.md` | Surveys, contamination control |
| 6.7 | Radioactive Package Receipt Checklist | ⬜ Pending | `/freebies/package-receipt-checklist.md` | Package receipt SEO/AEO content |
| 6.8 | Decay-in-Storage Log Template | ⬜ Pending | `/freebies/decay-in-storage-log-template.md` | Waste content |
| 6.9 | Radiation Safety Program Document Index | ⬜ Pending | `/freebies/radiation-safety-program-document-index.md` | Audit and program management |
| 6.10 | Annual Radiation Safety Program Review Template | ⬜ Pending | `/freebies/annual-radiation-safety-program-review-template.md` | Existing annual review blog post |
| 6.11 | Lead magnet landing page template | ⬜ Pending | `/freebies/lead-magnet-landing-page-template.md` | Reusable format for all freebies |
| 6.12 | Resource download email template | ⬜ Pending | `/email-templates/resource-download-email.md` | Sends download and invites quote request |
| 6.13 | Freebie follow-up email template | ⬜ Pending | `/email-templates/freebie-followup-email.md` | Soft CTA: reply or request quote |

Each freebie should include:

```text
Title
Who it is for
What it helps with
Disclaimer: template only; adapt to license and regulations
Email capture form
Download link or email delivery
Soft CTA to request a quote
```

Recommended first freebie:

```text
Radiation Safety Program Audit Checklist
```

Reason: broad appeal, strong consulting signal, useful for SEO, and easy to convert into future audit-readiness services.

---

## 7. Existing Blog and SEO Content

The site already has multiple blog posts. Do not recreate them from scratch; improve and organize them.

### Existing Blog Posts Seen on Live Site

| # | Existing Blog Post | Status | Deliverable Location | Next Update |
|---|---|---:|---|---|
| 7.1 | Guide to Radiation Safety Programs for RAM Licensees | 🟡 Needs Update | `/page-drafts/guide-radiation-safety-programs-ram-licensees.md` | Add resource CTA and internal links |
| 7.2 | ALARA Principles in Radiation Safety: What NRC Licensees Need to Know | 🟡 Needs Update | `/page-drafts/alara-principles-nrc-licensees.md` | Add FAQ and link to ALARA/program services |
| 7.3 | What Is an RSO? Understanding the Radiation Safety Officer Role Under NRC Regulations | 🟡 Needs Update | `/page-drafts/what-is-an-rso.md` | Add RSO quote CTA and checklist CTA |
| 7.4 | How to Prepare for an NRC Inspection | 🟡 Needs Update | `/page-drafts/nrc-inspection-preparation.md` | Add inspection readiness freebie |
| 7.5 | Understanding Radiation Dose Limits for Occupational Workers Under 10 CFR 20 | 🟡 Needs Update | `/page-drafts/occupational-dose-limits-10-cfr-20.md` | Add FAQ and training CTA |
| 7.6 | Radiation Safety Program Annual Review: A Complete Checklist for RSOs | 🟡 Needs Update | `/page-drafts/radiation-safety-program-annual-review.md` | Convert to lead magnet funnel |
| 7.7 | ALARA Principle Explained: Practical Strategies for Radiation Workers | 🟡 Needs Update | `/page-drafts/alara-practical-strategies.md` | Merge/link with other ALARA post if duplicate |
| 7.8 | How to Read and Understand Your NRC Inspection Report | 🟡 Needs Update | `/page-drafts/nrc-inspection-report-guide.md` | Add audit/inspection quote CTA |
| 7.9 | Common Mistakes in Radioactive Material License Applications | 🟡 Needs Update | `/page-drafts/ram-license-application-mistakes.md` | Add license worksheet CTA |
| 7.10 | How to Apply for a Radioactive Material License | 🟡 Needs Update | `/page-drafts/apply-for-radioactive-material-license.md` | Add license consulting CTA and worksheet |

Blog update checklist:

```text
[ ] Add direct-answer opening section
[ ] Add FAQ section
[ ] Add related service links
[ ] Add relevant freebie CTA
[ ] Add Request a Quote CTA
[ ] Add references/regulatory notes
[ ] Add author/expertise note
[ ] Add last-updated date
[ ] Check for duplicate articles targeting the same keyword
[ ] Add internal links to topic hubs
```

---

## 8. SEO and AEO Content Plan

Create practical, direct-answer pages that can rank in search and appear in answer engines. Each page should answer one real question clearly.

| # | Task | Status | Deliverable Location | Notes |
|---|---|---:|---|---|
| 8.1 | Create SEO/AEO topic cluster plan | ⬜ Pending | `/content-plan/topic-clusters.md` | Organize by service area |
| 8.2 | Create keyword/question list | ⬜ Pending | `/content-plan/seo-aeo-keywords.md` | Include question-based searches |
| 8.3 | Create content calendar | ⬜ Pending | `/content-plan/content-calendar.md` | Prioritize updates to existing pages before adding too many new ones |
| 8.4 | Create page template for AEO posts | ⬜ Pending | `/content-plan/aeo-page-template.md` | Direct answer, practical explanation, FAQ |
| 8.5 | Create internal linking map | ⬜ Pending | `/content-plan/internal-linking-map.md` | Link articles to service pages, freebie pages, and quote form |
| 8.6 | Add FAQ sections to key pages | ⬜ Pending | Existing service/blog pages | Good for AEO |
| 8.7 | Add author/expertise note to technical pages | ⬜ Pending | Existing service/blog pages | Important for credibility |
| 8.8 | Add references section to technical pages | ⬜ Pending | Existing service/blog pages | Link to NRC, Agreement States, DOT, EPA, OSHA, etc. |
| 8.9 | Add “last updated” date to articles | ⬜ Pending | WordPress posts/pages | Supports trust and freshness |
| 8.10 | Create topic hubs | ⬜ Pending | `/page-drafts/hub-*.md` | Cluster content by service area |

AEO page structure:

```text
# Question-Based Title

## Direct Answer
Answer in 2–4 clear sentences.

## Practical Explanation
Explain the topic in plain language.

## When This Matters
List common use cases or facility types.

## Typical Records, Controls, or Steps
Use a table or checklist.

## Common Mistakes
List practical pitfalls.

## Related Questions
Add 4–8 FAQ entries.

## References and Regulatory Notes
Link to authoritative sources when relevant.

## Need Help?
Soft CTA to request a quote or download a related template.
```

---

## 9. New Priority Content Pages

Since several blog posts already exist, prioritize pages that fill gaps, support freebies, or target high-intent quote requests.

| # | Page / Article | Status | Deliverable Location | CTA / Related Freebie |
|---|---|---:|---|---|
| 9.1 | Radiation Safety Program Audit Checklist | ⬜ Pending | `/page-drafts/radiation-safety-program-audit-checklist.md` | Download audit checklist |
| 9.2 | RSO Inspection Readiness Checklist | ⬜ Pending | `/page-drafts/rso-inspection-readiness-checklist.md` | Download checklist |
| 9.3 | What records are needed for a RAM license inspection? | ⬜ Pending | `/page-drafts/ram-license-inspection-records.md` | Audit checklist |
| 9.4 | How often do radiation surveys need to be performed? | ⬜ Pending | `/page-drafts/radiation-survey-frequency.md` | Survey record template |
| 9.5 | What is a restricted area in radiation safety? | ⬜ Pending | `/page-drafts/restricted-area-radiation-safety.md` | Request quote |
| 9.6 | What is a controlled area? | ⬜ Pending | `/page-drafts/controlled-area-radiation-safety.md` | Request quote |
| 9.7 | Radioactive material package receipt survey requirements | ⬜ Pending | `/page-drafts/radioactive-package-receipt-requirements.md` | Package receipt checklist |
| 9.8 | How to choose a radiation survey meter | ⬜ Pending | `/page-drafts/choose-radiation-survey-meter.md` | Survey/instrument inquiry |
| 9.9 | Decay-in-storage requirements and records | ⬜ Pending | `/page-drafts/decay-in-storage-records.md` | Decay-in-storage log |
| 9.10 | RAM license amendment checklist | ⬜ Pending | `/page-drafts/ram-license-amendment-checklist.md` | License worksheet |
| 9.11 | Radiation safety training record requirements | ⬜ Pending | `/page-drafts/radiation-safety-training-records.md` | Training attendance form |
| 9.12 | Radiation safety program document index | ⬜ Pending | `/page-drafts/radiation-safety-program-document-index.md` | Document index freebie |

---

## 10. Topic Hubs

Create hub pages that group related content and route users to quote requests or freebies.

| # | Topic Hub | Status | Deliverable Location | Notes |
|---|---|---:|---|---|
| 10.1 | RSO Support | ⬜ Pending | `/page-drafts/hub-rso-support.md` | Link to RSO articles, RSO consulting page, and quote form |
| 10.2 | Radioactive Materials Licensing | ⬜ Pending | `/page-drafts/hub-ram-licensing.md` | Link to license articles, license service page, and worksheet |
| 10.3 | Radiation Safety Training | ⬜ Pending | `/page-drafts/hub-radiation-safety-training.md` | Link to training page, training records, forms |
| 10.4 | Radiation Safety Audits and Inspections | ⬜ Pending | `/page-drafts/hub-audits-inspections.md` | Link to audit service and audit checklist |
| 10.5 | Radiation Surveys and Instrumentation | ⬜ Pending | `/page-drafts/hub-surveys-instrumentation.md` | Link to survey service and survey templates |
| 10.6 | DOT/IATA and Package Receipt | ⬜ Pending | `/page-drafts/hub-package-receipt-shipping.md` | Link to package receipt checklist |
| 10.7 | Shielding and Hot Lab Planning | ⬜ Pending | `/page-drafts/hub-shielding-hot-labs.md` | Future high-value service |
| 10.8 | Radioactive Waste and Decay-in-Storage | ⬜ Pending | `/page-drafts/hub-radioactive-waste.md` | Link to decay-in-storage log |

---

## 11. Email List and Follow-Up

Email capture should support freebie delivery, future resource updates, and soft quote conversion.

| # | Task | Status | Deliverable Location | Notes |
|---|---|---:|---|---|
| 11.1 | Choose email list tool | ⬜ Pending | `/analytics/email-list-setup.md` | MailerLite, ConvertKit, Mailchimp, Brevo, Jetpack Newsletter, or WordPress option |
| 11.2 | Create general welcome email | ⬜ Pending | `/email-templates/welcome-email.md` | Thank user and link resources |
| 11.3 | Create freebie delivery email | ⬜ Pending | `/email-templates/resource-download-email.md` | Include download link |
| 11.4 | Create soft quote CTA email | ⬜ Pending | `/email-templates/soft-quote-cta-email.md` | “Need help adapting this to your program?” |
| 11.5 | Create monthly update email template | ⬜ Pending | `/email-templates/monthly-update-email.md` | Round up new resources |
| 11.6 | Add signup CTA to resource pages | ⬜ Pending | WordPress pages | Place near related templates/checklists |
| 11.7 | Track source of signups | ⬜ Pending | Email tool or tracking sheet | Identify which freebies work |

---

## 12. Measurement and Validation

Track search traffic, quote requests, freebie downloads, and content performance.

| # | Metric / Task | Status | Deliverable Location | Notes |
|---|---|---:|---|---|
| 12.1 | Create metrics tracker | ⬜ Pending | `/analytics/metrics-tracker.md` | Manual monthly summary |
| 12.2 | Track organic impressions | ⬜ Pending | Google Search Console | SEO visibility |
| 12.3 | Track organic clicks | ⬜ Pending | Google Search Console | Search traffic |
| 12.4 | Track top queries | ⬜ Pending | `/analytics/search-console-notes.md` | Use for future content |
| 12.5 | Track top landing pages | ⬜ Pending | `/analytics/search-console-notes.md` | Identify what works |
| 12.6 | Track quote requests | ⬜ Pending | Lead tracking sheet | Main conversion |
| 12.7 | Track project inquiry submissions | ⬜ Pending | Lead tracking sheet | Secondary conversion |
| 12.8 | Track question submissions | ⬜ Pending | Lead tracking sheet | Content ideas |
| 12.9 | Track freebie downloads | ⬜ Pending | Email tool / form plugin | Lead magnet performance |
| 12.10 | Track email subscribers | ⬜ Pending | Email tool | Audience building |
| 12.11 | Track topic categories | ⬜ Pending | Lead tracking sheet | RSO, audits, training, license, etc. |
| 12.12 | Complete monthly review | ⬜ Pending | `/analytics/monthly-review-template.md` | Decide what to build next |

Monthly review template:

```text
Month:
Top 10 search queries:
Top 10 landing pages:
Pages with impressions but low CTR:
Pages with traffic but no conversions:
Quote requests:
Project inquiries:
Submitted questions:
Freebie downloads:
Email signups:
Most common topic categories:
Best next content opportunities:
Decision for next month:
```

Early validation targets:

```text
30 days:
- Clean live site with no default template artifacts
- Request quote form live
- 1 freebie funnel live
- 10+ indexed pages/posts
- 100+ organic impressions
- 3+ quote/project/question submissions or freebie downloads

90 days:
- 30+ indexed pages/posts
- 1,000+ organic impressions
- 10+ quote/project/question submissions
- 25+ email subscribers or freebie downloads
- Clear evidence of top 3 topic clusters
```

---

## 13. Distribution

Use lightweight distribution first. Do not start paid ads or cold outreach until the site has working forms, analytics, and at least one freebie.

| # | Task | Status | Deliverable Location | Notes |
|---|---|---:|---|---|
| 13.1 | Draft LinkedIn announcement post | ⬜ Pending | `/content-plan/linkedin-launch-post.md` | Announce practical radiation safety resources and quote requests |
| 13.2 | Create short LinkedIn posts from each article | ⬜ Pending | `/content-plan/social-posts.md` | Repurpose SEO content |
| 13.3 | Share first freebie on LinkedIn | ⬜ Pending | LinkedIn + `/freebies/` | Build email list |
| 13.4 | Identify professional communities | ⬜ Pending | `/content-plan/distribution-list.md` | HPS, EHS groups, LinkedIn, forums |
| 13.5 | Defer cold email scraping | ⏸ Deferred | `/future-funnel/cold-email-placeholder.md` | Do later only if offer is clear |
| 13.6 | Defer Google Ads | ⏸ Deferred | `/future-funnel/google-ads-placeholder.md` | Do only after organic pages and forms convert |

---

## 14. Future Consulting Funnel — Deferred

Do not build full consulting infrastructure yet. Keep notes/placeholders only.

| # | Future Task | Status | Deliverable Location | Notes |
|---|---|---:|---|---|
| 14.1 | Formal quote/proposal template | ⏸ Deferred | `/future-funnel/proposal-template.md` | Useful after lead flow begins |
| 14.2 | Contract workflow | ⏸ Deferred | `/future-funnel/contract-workflow.md` | Not needed for MVP |
| 14.3 | Scheduling integration | ⏸ Deferred | `/future-funnel/scheduling-workflow.md` | Avoid until calls are needed |
| 14.4 | Payment processing | ⏸ Deferred | `/future-funnel/payment-workflow.md` | Not needed yet |
| 14.5 | Client intake packet | ⏸ Deferred | `/future-funnel/client-intake-packet.md` | Future consulting phase |
| 14.6 | CRM pipeline | ⏸ Deferred | `/future-funnel/crm-pipeline.md` | Use spreadsheet first |
| 14.7 | Client portal | ❌ Remove / Avoid | N/A | Too much for MVP |
| 14.8 | Automated quote calculator | ❌ Remove / Avoid | N/A | Too much for MVP |

---

## 15. Recommended Repository Structure

Create or maintain this structure so an AI agent can continue work easily.

```text
/
  TASKS.md
  README.md

/content-plan/
  seo-aeo-keywords.md
  topic-clusters.md
  content-calendar.md
  aeo-page-template.md
  internal-linking-map.md
  linkedin-launch-post.md
  social-posts.md
  distribution-list.md

/page-drafts/
  home.md
  about.md
  services.md
  request-a-quote.md
  resources.md
  free-radiation-safety-templates.md
  submit-a-question.md
  contact.md
  privacy-policy.md
  terms-disclaimer.md
  radioactive-material-license-consulting.md
  radiation-safety-audits.md
  radiation-safety-program-development.md
  rso-consulting.md
  training.md
  radiation-surveys.md

/forms/
  quote-request-form.md
  quote-request-confirmation.md
  project-inquiry-form.md
  submit-question-form.md
  update-list-form.md
  lead-categories.md

/freebies/
  radiation-safety-program-audit-checklist.md
  rso-inspection-readiness-checklist.md
  ram-license-amendment-planning-worksheet.md
  training-attendance-form-template.md
  radiation-survey-record-template.md
  wipe-test-log-template.md
  package-receipt-checklist.md
  decay-in-storage-log-template.md
  radiation-safety-program-document-index.md
  annual-radiation-safety-program-review-template.md
  lead-magnet-landing-page-template.md

/email-templates/
  quote-request-acknowledgement.md
  resource-download-email.md
  freebie-followup-email.md
  welcome-email.md
  soft-quote-cta-email.md
  monthly-update-email.md

/analytics/
  site-setup-notes.md
  email-list-setup.md
  metrics-tracker.md
  search-console-notes.md
  monthly-review-template.md

/future-funnel/
  proposal-template.md
  contract-workflow.md
  scheduling-workflow.md
  payment-workflow.md
  client-intake-packet.md
  crm-pipeline.md
  cold-email-placeholder.md
  google-ads-placeholder.md
```

---

## 16. Immediate Next Actions

An AI agent continuing this project should start here:

| Priority | Task | Status | Deliverable Location |
|---|---|---:|---|
| 1 | Update `/TASKS.md` with this site-reviewed plan | ⬜ Pending | `/TASKS.md` |
| 2 | Clean homepage template artifacts | ⬜ Pending | WordPress homepage |
| 3 | Remove default WordPress sidebar/footer widgets | ⬜ Pending | WordPress Customizer / Widgets |
| 4 | Draft improved Request a Quote page and form | ⬜ Pending | `/page-drafts/request-a-quote.md`, `/forms/quote-request-form.md` |
| 5 | Replace generic Contact form with quote-oriented form | ⬜ Pending | WordPress Contact or Request Quote page |
| 6 | Draft first freebie: Radiation Safety Program Audit Checklist | ⬜ Pending | `/freebies/radiation-safety-program-audit-checklist.md` |
| 7 | Draft freebie landing page template | ⬜ Pending | `/freebies/lead-magnet-landing-page-template.md` |
| 8 | Add freebie CTA to audit, RSO, and annual review pages | ⬜ Pending | WordPress service/blog pages |
| 9 | Create Search Console / analytics setup notes | ⬜ Pending | `/analytics/site-setup-notes.md`, `/analytics/search-console-notes.md` |
| 10 | Build internal linking map from existing posts to service pages | ⬜ Pending | `/content-plan/internal-linking-map.md` |

---

## 17. What Not To Build Yet

Avoid these until demand is validated:

```text
Automated quote calculator
Contract automation
Payment processing for consulting
Client portal
Complex CRM
Paid ads
Cold email scraping
LMS platform
Membership site
User accounts
Custom web app
Large automation stack
```

The MVP should stay focused on:

```text
Useful radiation safety content
→ SEO/AEO traffic
→ quote requests, questions, downloads, and email signups
→ market validation
→ selective follow-up or future product decisions
```

---

## Bottom Line

The project is no longer a blank website build. The core site exists and has meaningful service and blog content.

The next phase is cleanup and conversion:

```text
Clean live WordPress site
+ strengthen Request a Quote path
+ organize service pages and blog posts
+ add free templates/checklists for email signup
+ set up tracking
+ use SEO/AEO performance to decide what to build next
```

Current MVP:

```text
Professional website
+ SEO/AEO resource pages
+ quote request form
+ free templates/checklists for email signup
+ simple lead tracking
+ monthly validation review
```
