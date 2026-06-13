# HP Consulting Website — TASKS

## Strategy summary

The Advantage Health Physics website is currently a traffic and demand-validation MVP.

The goal is to publish useful health physics and radiation safety content, improve SEO/AEO visibility, and collect demand signals through project inquiries, quote requests, submitted questions, free resource downloads, and email signups.

The site should not yet behave like a fully staffed consulting operation. Avoid response-time promises, emergency-support promises, guaranteed consultations, and operational infrastructure that is not needed for validation.

## Key planning documents

| Document | Purpose |
|---|---|
| `BUILD_PLAN.md` | Master build plan and validation strategy |
| `content-plan/seo-aeo-build-plan.md` | SEO/AEO clusters, content structure, internal linking, publishing priority |
| `forms/request-intake-and-confirmation-copy.md` | Request form fields, CTA copy, confirmation copy, lead categories |
| `analytics/traffic-validation-plan.md` | Search Console, analytics, conversion tracking, and monthly review |
| `README.md` | Repository overview and operating strategy |

## Status key

| Status | Meaning |
|---|---|
| ✅ Done | Complete enough for current MVP |
| 🟡 Needs Update | Exists but should be improved |
| ⬜ Pending | Not started or not visible on live site |
| ⏸ Deferred | Do later after validation |
| ❌ Avoid | Do not build for this MVP |

---

# Phase 1 — Immediate live-site cleanup

These tasks affect credibility and should be completed before traffic-building work.

| # | Task | Status | Deliverable |
|---|---|---:|---|
| 1.1 | Remove WordPress template text and starter copy | ⬜ Pending | Live WordPress homepage/pages |
| 1.2 | Remove placeholder posts and demo content | ⬜ Pending | WordPress posts/pages |
| 1.3 | Remove or replace default sidebar/footer widgets | ⬜ Pending | WordPress theme/customizer |
| 1.4 | Remove placeholder sections such as video/demo blocks | ⬜ Pending | Homepage and theme blocks |
| 1.5 | Disable comments unless intentionally moderated | ⬜ Pending | WordPress discussion settings |
| 1.6 | Remove irrelevant tags that dilute topical authority | ⬜ Pending | WordPress post tags |
| 1.7 | Replace response-time promises with validation-safe copy | ⬜ Pending | Contact/request pages |
| 1.8 | Review mobile layout and CTA visibility | ⬜ Pending | Live site QA |
| 1.9 | Check all internal links and CTA buttons | ⬜ Pending | Live site QA |
| 1.10 | Add privacy and disclaimer pages before collecting emails/requests | ⬜ Pending | WordPress pages and repo drafts |

Acceptance criteria:

- No default WordPress/demo artifacts remain visible.
- No public copy promises a response time or accepted project.
- All main CTAs point to request, question, download, or signup actions.

---

# Phase 2 — Validation-safe conversion path

The conversion path should collect request and interest signals without creating an obligation to respond.

| # | Task | Status | Deliverable |
|---|---|---:|---|
| 2.1 | Create Request a Quote / Project Inquiry page draft | ⬜ Pending | `page-drafts/request-a-quote.md` |
| 2.2 | Build request/project inquiry form spec | ✅ Done | `forms/request-intake-and-confirmation-copy.md` |
| 2.3 | Add request/project inquiry form to WordPress | ⬜ Pending | WordPress form/page |
| 2.4 | Create Submit a Radiation Safety Question page draft | ⬜ Pending | `page-drafts/submit-a-question.md` |
| 2.5 | Create Free Resources / Templates page draft | ⬜ Pending | `page-drafts/free-radiation-safety-templates.md` |
| 2.6 | Create general Contact page copy with softer language | ⬜ Pending | `page-drafts/contact.md` |
| 2.7 | Create lead category/tag list for tracking | ✅ Done | `forms/request-intake-and-confirmation-copy.md` |
| 2.8 | Create optional auto-reply email copy | ✅ Done | `forms/request-intake-and-confirmation-copy.md` |
| 2.9 | Create Google Sheet or Airtable lead tracker | ⬜ Pending | External tracker and setup notes |

Preferred CTA:

> Submit a project inquiry or quote request. We review submissions to understand current radiation safety needs and may follow up if the project appears to be a good fit.

Preferred confirmation:

> Thank you. Your submission has been received. We review submissions to understand current radiation safety needs and may follow up if the project appears to be a good fit. Submitting this form does not create a consulting relationship, emergency response obligation, or guarantee of service.

---

# Phase 3 — Analytics and validation setup

| # | Task | Status | Deliverable |
|---|---|---:|---|
| 3.1 | Create traffic validation plan | ✅ Done | `analytics/traffic-validation-plan.md` |
| 3.2 | Verify Google Search Console | ⬜ Pending | Search Console |
| 3.3 | Submit sitemap | ⬜ Pending | Search Console |
| 3.4 | Set up Bing Webmaster Tools | ⬜ Pending | Bing Webmaster Tools |
| 3.5 | Set up lightweight site analytics | ⬜ Pending | WordPress stats, Jetpack, GA4, Plausible, or similar |
| 3.6 | Create monthly review file/template | 🟡 Needs Update | `analytics/monthly-review-template.md` or included in plan |
| 3.7 | Track source page and topic category for submissions | ⬜ Pending | Lead tracker |
| 3.8 | Track free resource downloads | ⬜ Pending | Email/form/download tool |
| 3.9 | Review metrics monthly and set next content priorities | ⬜ Pending | `analytics/search-console-notes.md` |

Validation targets are documented in `analytics/traffic-validation-plan.md`.

---

# Phase 4 — Service page optimization

Each existing service page should be improved rather than recreated from scratch.

Required structure for each service page:

- Direct-answer intro.
- Who this is for.
- Problems solved.
- Typical deliverables.
- Information to submit.
- Common mistakes.
- FAQ section.
- Related articles/resources.
- Request/project inquiry CTA.

| # | Page | Status | Draft location |
|---|---|---:|---|
| 4.1 | Homepage | 🟡 Needs Update | `page-drafts/home.md` |
| 4.2 | About | 🟡 Needs Update | `page-drafts/about.md` |
| 4.3 | Services | 🟡 Needs Update | `page-drafts/services.md` |
| 4.4 | Radioactive Material License Consulting | 🟡 Needs Update | `page-drafts/radioactive-material-license-consulting.md` |
| 4.5 | Radiation Safety Audits and Mock NRC Inspections | 🟡 Needs Update | `page-drafts/radiation-safety-audits.md` |
| 4.6 | Radiation Safety Program Development | 🟡 Needs Update | `page-drafts/radiation-safety-program-development.md` |
| 4.7 | RSO Consulting and Ongoing Compliance Support | 🟡 Needs Update | `page-drafts/rso-consulting.md` |
| 4.8 | Radiation Safety Training | 🟡 Needs Update | `page-drafts/training.md` |
| 4.9 | Radiation Surveys | 🟡 Needs Update | `page-drafts/radiation-surveys.md` |

---

# Phase 5 — SEO/AEO content plan

| # | Task | Status | Deliverable |
|---|---|---:|---|
| 5.1 | Create SEO/AEO build plan | ✅ Done | `content-plan/seo-aeo-build-plan.md` |
| 5.2 | Create internal linking map | ⬜ Pending | `content-plan/internal-linking-map.md` |
| 5.3 | Create AEO page/post template | ⬜ Pending | `content-plan/aeo-page-template.md` |
| 5.4 | Create content calendar | ⬜ Pending | `content-plan/content-calendar.md` |
| 5.5 | Add FAQ sections to top service pages | ⬜ Pending | WordPress pages/page drafts |
| 5.6 | Add author/expertise notes to technical pages | ⬜ Pending | WordPress pages/page drafts |
| 5.7 | Add last-updated dates to technical pages | ⬜ Pending | WordPress pages/posts |
| 5.8 | Add references/regulatory notes where appropriate | ⬜ Pending | WordPress pages/posts |

Priority content clusters:

1. Radioactive material licensing.
2. RSO support.
3. Audits and inspections.
4. Program development.
5. Surveys and instrumentation.
6. Package receipt and shipping.
7. Waste and decay-in-storage.
8. Shielding and hot lab planning.

---

# Phase 6 — Existing blog/content updates

Existing blog posts should be refreshed for AEO, internal linking, and conversion.

Update checklist for each post:

- Add direct-answer opening.
- Add FAQ section.
- Add related service links.
- Add related free resource CTA.
- Add submit-a-question CTA.
- Add author/expertise note.
- Add last-updated date.
- Add relevant references or regulatory notes.
- Check duplicate keyword targeting.

Priority posts to update:

| # | Existing or planned article | Status | Target action |
|---|---|---:|---|
| 6.1 | How to Prepare for an NRC Inspection | 🟡 Needs Update | Add audit checklist CTA |
| 6.2 | What Is an RSO? | 🟡 Needs Update | Add RSO support CTA |
| 6.3 | How to Apply for a Radioactive Material License | 🟡 Needs Update | Add RAM worksheet CTA |
| 6.4 | Common Mistakes in RAM License Applications | 🟡 Needs Update | Add license consulting CTA |
| 6.5 | Radiation Safety Program Annual Review | 🟡 Needs Update | Add annual review template CTA |
| 6.6 | ALARA Principles for NRC Licensees | 🟡 Needs Update | Link to program development/training |
| 6.7 | Occupational Dose Limits under 10 CFR 20 | 🟡 Needs Update | Add training/program links |
| 6.8 | How to Read an NRC Inspection Report | 🟡 Needs Update | Add audit/mock inspection CTA |

---

# Phase 7 — Free resources and lead magnets

First free resource should be broad and useful enough to test demand.

| # | Free resource | Status | Draft location |
|---|---|---:|---|
| 7.1 | Radiation Safety Program Audit Checklist | ⬜ Pending | `freebies/radiation-safety-program-audit-checklist.md` |
| 7.2 | RSO Inspection Readiness Checklist | ⬜ Pending | `freebies/rso-inspection-readiness-checklist.md` |
| 7.3 | RAM License Amendment Planning Worksheet | ⬜ Pending | `freebies/ram-license-amendment-planning-worksheet.md` |
| 7.4 | Radiation Survey Record Template | ⬜ Pending | `freebies/radiation-survey-record-template.md` |
| 7.5 | Radioactive Package Receipt Checklist | ⬜ Pending | `freebies/package-receipt-checklist.md` |
| 7.6 | Annual Radiation Safety Program Review Template | ⬜ Pending | `freebies/annual-radiation-safety-program-review-template.md` |
| 7.7 | Decay-in-Storage Log Template | ⬜ Pending | `freebies/decay-in-storage-log-template.md` |
| 7.8 | Radiation Safety Program Document Index | ⬜ Pending | `freebies/radiation-safety-program-document-index.md` |

Each free resource must include:

- Who it is for.
- What it helps with.
- Template/checklist content.
- General-use disclaimer.
- Download/signup CTA.
- Submit-a-question or project inquiry CTA.

---

# Phase 8 — Topic hubs

Create hubs only after the service pages and first resources are improved.

| # | Topic hub | Status | Draft location |
|---|---|---:|---|
| 8.1 | RSO Support | ⬜ Pending | `page-drafts/hub-rso-support.md` |
| 8.2 | Radioactive Materials Licensing | ⬜ Pending | `page-drafts/hub-ram-licensing.md` |
| 8.3 | Audits and Inspections | ⬜ Pending | `page-drafts/hub-audits-inspections.md` |
| 8.4 | Radiation Safety Program Development | ⬜ Pending | `page-drafts/hub-program-development.md` |
| 8.5 | Training and Worker Instructions | ⬜ Pending | `page-drafts/hub-training.md` |
| 8.6 | Surveys and Instrumentation | ⬜ Pending | `page-drafts/hub-surveys-instrumentation.md` |
| 8.7 | Package Receipt and Shipping | ⬜ Pending | `page-drafts/hub-package-receipt-shipping.md` |
| 8.8 | Shielding and Hot Lab Planning | ⬜ Pending | `page-drafts/hub-shielding-hot-labs.md` |
| 8.9 | Waste and Decay-in-Storage | ⬜ Pending | `page-drafts/hub-radioactive-waste.md` |

Each hub should link to:

- Primary service page.
- Related articles.
- Related free resource.
- Request/project inquiry page.
- Submit-a-question page.

---

# Phase 9 — Distribution

Keep distribution lightweight until forms, tracking, and at least one free resource are live.

| # | Task | Status | Deliverable |
|---|---|---:|---|
| 9.1 | Draft LinkedIn launch/resource post | ⬜ Pending | `content-plan/linkedin-launch-post.md` |
| 9.2 | Create short social posts from existing articles | ⬜ Pending | `content-plan/social-posts.md` |
| 9.3 | Identify professional communities/directories | ⬜ Pending | `content-plan/distribution-list.md` |
| 9.4 | Share first free resource manually | ⏸ Deferred | LinkedIn/professional networks |
| 9.5 | Consider targeted outreach only after conversion path works | ⏸ Deferred | Future plan |

---

# Phase 10 — Future funnel, deferred

Do not build these until traffic and demand are validated.

| # | Future task | Status |
|---|---|---:|
| 10.1 | Proposal template | ⏸ Deferred |
| 10.2 | Contract workflow | ⏸ Deferred |
| 10.3 | Payment workflow | ⏸ Deferred |
| 10.4 | Scheduling integration | ⏸ Deferred |
| 10.5 | CRM pipeline | ⏸ Deferred |
| 10.6 | Client portal | ❌ Avoid |
| 10.7 | Automated quote calculator | ❌ Avoid |
| 10.8 | LMS or membership site | ❌ Avoid |
| 10.9 | Paid ads | ⏸ Deferred |
| 10.10 | Cold email scraping | ❌ Avoid for MVP |

---

# Immediate next actions

Start here:

1. Clean visible WordPress placeholder/template artifacts.
2. Replace any one-business-day or free-consultation language with validation-safe copy.
3. Draft `page-drafts/request-a-quote.md` using `forms/request-intake-and-confirmation-copy.md`.
4. Draft `page-drafts/submit-a-question.md`.
5. Draft `page-drafts/privacy-policy.md` and `page-drafts/terms-disclaimer.md`.
6. Set up Google Search Console and submit sitemap.
7. Draft first free resource: `freebies/radiation-safety-program-audit-checklist.md`.
8. Update the Radiation Safety Audits page to link to the free resource and request form.
9. Create `content-plan/internal-linking-map.md`.
10. Complete first monthly metrics review once data exists.

## Bottom line

The site should stay focused on:

```text
Helpful content
-> SEO/AEO visibility
-> requests, questions, downloads, and signups
-> tracking and validation
-> evidence-based next steps
```
