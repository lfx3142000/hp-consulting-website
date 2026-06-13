# Advantage Health Physics Website Build Plan

## 1. Strategy

Advantage Health Physics is currently a traffic and demand-validation website. The immediate purpose is to test whether health physics and radiation safety content can attract qualified visitors and generate requests, questions, downloads, and email signups.

The site should look credible and professional, but it should not yet behave like a fully staffed consulting operation. The current MVP should collect signals of demand without promising immediate response, emergency coverage, scheduled consultations, or guaranteed acceptance of projects.

## 2. Current MVP goal

Build a credible radiation safety / health physics website that:

1. Ranks for useful SEO and AEO queries.
2. Answers common radiation safety questions clearly.
3. Routes visitors to quote requests, project inquiries, submitted questions, free downloads, and email signup.
4. Tracks which topics and service categories generate interest.
5. Avoids heavy consulting operations until demand is validated.

## 3. Validation-first positioning

Use this positioning across the site:

> Advantage Health Physics provides practical radiation safety, health physics, licensing, audit, training, shielding, survey, and compliance resources for NRC and Agreement State licensees. Visitors may submit project inquiries or quote requests, and we may follow up if the project appears to be a good fit.

The website should not imply guaranteed availability. Prefer:

> Submit a project inquiry or quote request. We review submissions to understand radiation safety needs and may follow up if the project appears to be a good fit.

Avoid:

- "We respond within one business day."
- "Schedule a free consultation."
- "Immediate RSO support."
- "Emergency radiation safety response."
- "We can support all projects."
- "We will contact every requester."

## 4. North-star funnel

```text
SEO/AEO content
-> organic search impressions
-> page visits
-> quote request / project inquiry / submitted question / free download / email signup
-> simple tracking sheet
-> monthly validation review
-> decide what to build next
```

## 5. Success metrics

### 30-day target after cleanup

- Live site has no obvious WordPress template artifacts.
- Request/project inquiry form is live.
- Submit-a-question form is live.
- At least one free resource is live.
- Google Search Console is verified and sitemap submitted.
- 10+ important pages/posts are indexed or submitted for indexing.
- 100+ organic impressions.
- 3+ total validation events: requests, inquiries, questions, downloads, or email signups.

### 90-day target

- 25-40 useful pages/posts/resources are live.
- 1,000+ organic impressions.
- 10+ total validation events.
- 25+ free resource downloads or email signups.
- At least three content clusters have measurable impressions.
- Top 3 service/topic categories are clear enough to guide the next build cycle.

## 6. Build phases

### Phase 0: Documentation and alignment

Deliverables:

- `/BUILD_PLAN.md` - master strategy and build plan.
- `/AI_EXECUTION_GUIDE.md` - instructions for AI agents.
- `/TASKS.md` - execution checklist.
- `/content-plan/seo-aeo-build-plan.md` - keyword, page, AEO, and linking plan.
- `/forms/request-intake-and-confirmation-copy.md` - form fields and safe confirmation language.
- `/analytics/traffic-validation-plan.md` - tracking and monthly review system.

Acceptance criteria:

- All repo docs frame this as a validation MVP.
- All CTA copy avoids guaranteed response language.
- All implementation tasks are specific enough for an AI or human to carry out.

### Phase 1: Live-site cleanup

Purpose: remove credibility problems before traffic growth.

Tasks:

1. Remove WordPress template text, starter copy, demo posts, demo widgets, and placeholder sections.
2. Remove or replace default sidebar/footer widgets.
3. Remove placeholder sections such as "Add a Video" unless a real professional video is available.
4. Disable blog comments unless there is a moderation plan.
5. Remove irrelevant tags that dilute topical authority.
6. Check homepage, services, posts, and forms on mobile.
7. Confirm all internal links and CTA buttons work.
8. Add privacy and disclaimer pages before collecting emails or requests.
9. Replace response-time promises with validation-safe language.

Acceptance criteria:

- No visible default WordPress/demo content remains.
- No public copy promises a response time or accepted project.
- All main CTAs point to request, question, or resource actions.

### Phase 2: Conversion path for validation

Purpose: collect useful demand signals without creating service obligations.

Core conversion assets:

1. Request a Quote / Project Inquiry page.
2. Submit a Radiation Safety Question page.
3. Free Resources / Templates page.
4. Email update signup form.
5. General Contact page with conservative language.

Required confirmation language:

> Thank you. Your submission has been received. We review submissions to understand radiation safety needs and may follow up if the project appears to be a good fit. Submitting this form does not create a consulting relationship, emergency response obligation, or guarantee of service.

Acceptance criteria:

- Request form captures enough information to categorize demand.
- Submitted questions can be used to guide future SEO/AEO content.
- Free resource downloads are tracked by topic.
- No workflow depends on immediate response or full CRM setup.

### Phase 3: SEO/AEO technical foundation

Purpose: make content discoverable and answer-ready.

Tasks:

1. Verify Google Search Console.
2. Submit sitemap.
3. Set up Bing Webmaster Tools.
4. Set up basic analytics: WordPress stats, Jetpack, GA4, Plausible, or another simple tool.
5. Confirm title/meta controls available on current WordPress plan.
6. Add search titles and descriptions for top pages if possible.
7. Create a recurring monthly Search Console review process.
8. Add direct-answer sections to service pages and posts.
9. Add FAQ sections to high-value pages.
10. Add last-updated dates and author/expertise notes.
11. Add organization/article/FAQ/breadcrumb schema if the WordPress plan allows it.

Acceptance criteria:

- Search Console and sitemap are active.
- Top pages have one clear H1, direct-answer intro, internal links, and CTA.
- Articles link to related services, resources, and topic hubs.

### Phase 4: Service-page optimization

Priority service pages:

1. Radioactive Material License Consulting.
2. Radiation Safety Audits and Mock NRC Inspections.
3. Radiation Safety Program Development.
4. RSO Consulting and Ongoing Compliance Support.
5. Radiation Safety Training.
6. Radiation Surveys.

Each service page must include:

- Direct-answer intro.
- Who this is for.
- Problems solved.
- Typical deliverables.
- What information to submit.
- Common mistakes.
- Related resources.
- FAQ section.
- Validation-safe request CTA.

### Phase 5: SEO/AEO content expansion

Prioritize pages that answer real questions and support high-intent services.

First content wave:

1. NRC Form 313 checklist.
2. RAM license amendment checklist.
3. Common mistakes in radioactive material license applications.
4. How to prepare for an NRC inspection.
5. RSO inspection readiness checklist.
6. Radiation safety program annual review checklist.
7. Radiation safety manual review checklist.
8. Radioactive material package receipt checklist.
9. Radiation survey record template.
10. Decay-in-storage recordkeeping checklist.

Each article/page must follow this structure:

```text
# Question or specific service-oriented title

## Direct answer
2-4 clear sentences.

## Practical explanation
Plain-language explanation.

## When this matters
Facility types and scenarios.

## Typical steps, records, or deliverables
Checklist or table.

## Common mistakes
Practical pitfalls.

## Related resources
Internal links.

## FAQ
4-8 concise Q&A entries.

## Regulatory notes and references
Authoritative references where appropriate.

## Submit a question or request information
Validation-safe CTA.
```

### Phase 6: Free resources and lead magnets

First free resources:

1. Radiation Safety Program Audit Checklist.
2. RSO Inspection Readiness Checklist.
3. RAM License Amendment Planning Worksheet.
4. Radiation Survey Record Template.
5. Radioactive Package Receipt Checklist.
6. Annual Radiation Safety Program Review Template.

Each freebie must include:

- Title.
- Who it is for.
- What it helps with.
- Template/checklist content.
- Disclaimer: adapt to license, jurisdiction, and facility conditions.
- Download/signup CTA.
- Soft request/question CTA.

### Phase 7: Topic hubs and internal linking

Create topic hubs to organize content.

Priority hubs:

1. RSO Support.
2. Radioactive Materials Licensing.
3. Audits and Inspections.
4. Radiation Safety Program Development.
5. Training and Worker Instructions.
6. Surveys and Instrumentation.
7. DOT/IATA, Package Receipt, and Shipping.
8. Shielding, Hot Labs, and Facility Planning.
9. Radioactive Waste and Decay-in-Storage.

Each hub should link to:

- One primary service page.
- 3-8 related articles.
- At least one related free resource.
- Request/project inquiry form.
- Submit-a-question form.

### Phase 8: Measurement and monthly iteration

Each month, review:

1. Top search queries.
2. Top landing pages.
3. Pages with impressions but low CTR.
4. Pages with traffic but no conversions.
5. Quote requests.
6. Project inquiries.
7. Submitted questions.
8. Free resource downloads.
9. Email signups.
10. Best next content opportunities.

Use the results to choose the next page, freebie, or service angle. Do not build full operations until the data justifies it.

## 7. What not to build yet

Avoid until validation is stronger:

- Automated quote calculator.
- Contract workflow.
- Payment processing.
- Client portal.
- Scheduling integration.
- Complex CRM.
- LMS platform.
- Membership site.
- Paid ads.
- Cold email scraping.
- Custom web application.

## 8. AI implementation rule

An AI agent should continue this project by reading these files in order:

1. `/BUILD_PLAN.md`
2. `/AI_EXECUTION_GUIDE.md`
3. `/TASKS.md`
4. `/content-plan/seo-aeo-build-plan.md`
5. `/forms/request-intake-and-confirmation-copy.md`
6. `/analytics/traffic-validation-plan.md`

Then it should pick the highest-priority incomplete task, create or update the relevant repo document, and provide exact WordPress copy/paste instructions when admin access is needed.
