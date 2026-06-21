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
|---|---|---|---|
| 1.1 | Remove WordPress template text and starter copy | ✅ Done | Live WordPress homepage/pages |
| 1.2 | Remove placeholder posts and demo content | ✅ Done | WordPress posts/pages |
| 1.3 | Remove or replace default sidebar/footer widgets | ✅ Done | WordPress theme/customizer |
| 1.4 | Remove placeholder sections such as video/demo blocks | ✅ Done | Homepage and theme blocks |
| 1.5 | Disable comments unless intentionally moderated | ✅ Done | WordPress discussion settings |
| 1.6 | Remove irrelevant tags that dilute topical authority | ✅ Done | WordPress post tags |
| 1.7 | Replace response-time promises with validation-safe copy | ✅ Done | Contact/request pages |
| 1.8 | Review mobile layout and CTA visibility | ✅ Done | Live site QA — CTAs verified, mobile preview confirmed 2026-06-20 |
| 1.9 | Check all internal links and CTA buttons | ✅ Done | Live site QA — CTAs verified, Related Resources links fixed on Audits and RSO Consulting pages |
| 1.10 | Add privacy and disclaimer pages before collecting emails/requests | ✅ Done | WordPress pages and repo drafts |

Acceptance criteria:
* No default WordPress/demo artifacts remain visible.
* No public copy promises a response time or accepted project.
* All main CTAs point to request, question, download, or signup actions.

# Phase 2 — Validation-safe conversion path
The conversion path should collect request and interest signals without creating an obligation to respond.

| # | Task | Status | Deliverable |
|---|---|---|---|
| 2.1 | Create Request a Quote / Project Inquiry page draft | ✅ Done | `page-drafts/request-a-quote.md` |
| 2.2 | Build request/project inquiry form spec | ✅ Done | `forms/request-intake-and-confirmation-copy.md` |
| 2.3 | Add request/project inquiry form to WordPress | ✅ Done | WordPress form/page |
| 2.4 | Create Submit a Radiation Safety Question page draft | ✅ Done | `page-drafts/submit-a-question.md` |
| 2.5 | Create Free Resources / Templates page draft | ✅ Done | `page-drafts/free-radiation-safety-templates.md` |
| 2.6 | Create general Contact page copy with softer language | ✅ Done | `page-drafts/contact.md` |
| 2.7 | Create lead category/tag list for tracking | ✅ Done | `forms/request-intake-and-confirmation-copy.md` |
| 2.8 | Create optional auto-reply email copy | ✅ Done | `forms/request-intake-and-confirmation-copy.md` |
| 2.9 | Create Google Sheet or Airtable lead tracker | ⬜ Pending | External tracker and setup notes |

# Phase 3 — Analytics and validation setup
| # | Task | Status | Deliverable |
|---|---|---|---|
| 3.1 | Create traffic validation plan | ✅ Done | `analytics/traffic-validation-plan.md` |
| 3.2 | Verify Google Search Console | ✅ Done | Search Console |
| 3.3 | Submit sitemap | ✅ Done | Search Console (submitted/processing) |
| 3.4 | Set up Bing Webmaster Tools | ⬜ Pending | Bing Webmaster Tools |
| 3.5 | Set up lightweight site analytics | ✅ Done | WordPress stats / Jetpack |
| 3.6 | Create monthly review file/template | 🟡 Needs Update | `analytics/monthly-review-template.md` |
| 3.7 | Track source page and topic category for submissions | ⬜ Pending | Lead tracker |
| 3.8 | Track free resource downloads | ⬜ Pending | Email/form/download tool |
| 3.9 | Review metrics monthly and set next content priorities | ⬜ Pending | `analytics/search-console-notes.md` |

# Phase 4 — Service page optimization
| # | Page | Status | Draft location |
|---|---|---|---|
| 4.1 | Homepage | ✅ Done | `page-drafts/home.md` |
| 4.2 | About | ✅ Done | `page-drafts/about.md` — updated 2026-06-20, internal links and CTA section added |
| 4.3 | Services | ✅ Done | `page-drafts/services.md` |
| 4.4 | Radioactive Material License Consulting | ✅ Done | `page-drafts/radioactive-material-license-consulting.md` |
| 4.5 | Radiation Safety Audits and Mock NRC Inspections | ✅ Done | `page-drafts/radiation-safety-audits.md` |
| 4.6 | Radiation Safety Program Development | ✅ Done | `page-drafts/radiation-safety-program-development.md` |
| 4.7 | RSO Consulting and Ongoing Compliance Support | ✅ Done | `page-drafts/rso-consulting.md` |
| 4.8 | Radiation Safety Training | ✅ Done | `page-drafts/training.md` |
| 4.9 | Radiation Surveys | ✅ Done | `page-drafts/radiation-surveys.md` |

# Phase 5 — SEO/AEO content plan
| # | Task | Status | Deliverable |
|---|---|---|---|
| 5.1 | Create SEO/AEO build plan | ✅ Done | `content-plan/seo-aeo-build-plan.md` |
| 5.2 | Create internal linking map | ✅ Done | `content-plan/internal-linking-map.md` |
| 5.3 | Create AEO page/post template | ✅ Done | `content-plan/aeo-page-template.md` — created 2026-06-18 |
| 5.4 | Create content calendar | ✅ Done | `content-plan/content-calendar.md` — created 2026-06-18, updated through Priority 30 (2026-06-20) |
| 5.5 | Add FAQ sections to top service pages | ✅ Done | WordPress pages/page drafts |

# Phase 7 — Free resources and lead magnets
| # | Free resource | Status | Draft location |
|---|---|---|---|
| 7.1 | Radiation Safety Program Audit Checklist | ✅ Done | `freebies/radiation-safety-program-audit-checklist.md` |
| 7.2 | RSO Inspection Readiness Checklist | ✅ Done | `freebies/rso-inspection-readiness-checklist.md` |checklist.md` |

## Completed — Session 2026-06-16
* ✅ i. Related Resources links fixed on Radiation Safety Audits page (3 links added)
* ✅ ii. Related Resources links fixed on RSO Consulting page (3 links added)
* ✅ iii. QA pass on primary service pages: Radiation Safety Audits, RSO Consulting, Radiation Safety Program Development, Radiation Safety Training, Radiation Surveys, Radioactive Material License Consulting — all CTAs resolve correctly
* ✅ iv. RSO Inspection Readiness Checklist page published (Task 7.2)
* ✅ v. FAQ sections added to Radiation Safety Audits and RSO Consulting pages (Task 5.5)

## Immediate next actions
* i. Set up Bing Webmaster Tools (submit sitemap).
* ii. Create Google Sheet lead tracker (project inquiry log).
* iii. Add Related Resources section to Radiation Safety Training, Radiation Surveys, and Radiation Safety Program Development pages.
* iv. Mark Task 1.9 as Done in Phase 1 table.
* 
## Completed — Session 2026-06-16 (continued)
* ✅ vi. Bing Webmaster Tools set up via Google Search Console import — 1 sitemap, 59 URLs discovered
* ✅ vii. Google Sheet lead tracker created: https://docs.google.com/spreadsheets/d/12kC77iC0JEBgFY3HHv6wOGibcON6WE03vB5t9mA3PZI/edit
* ✅ viii. Related Resources section added to Radiation Safety Training, Radiation Surveys, and Radiation Safety Program Development pages

## Immediate next actions
* i. Delete duplicate pages: /radiation-safety-program-audit-checklist-2/, /rso-consulting-2/, /radiation-surveys-2/, /submit-a-question/
* ii. Add FAQ section to Radiation Safety Training and Radiation Surveys pages
* iii. Monthly analytics review (first review due after 30 days of traffic)


## Completed — Session 2026-06-17
* ✅ ix. Verified duplicate pages (radiation-surveys-2, rso-consulting-2, radiation-safety-program-audit-checklist-2, submit-a-question) — already removed from previous sessions; no live duplicates found
* ✅ x. FAQ section added to Radiation Surveys page (5 Q&A covering survey types, frequency, equipment, reports, service area)
* ✅ xi. FAQ section added to Radiation Safety Training for Workers and RSOs page (5 Q&A covering who needs training, frequency, customization, documentation, RSO training)

## Immediate next actions
* i. Monthly analytics review (first review due after 30 days of traffic)
* ii. Review mobile layout and CTA visibility (Task 1.8)
* iii. Update About page content (Task 4.2)
* iv. Create AEO page/post template (Task 5.3)
* v. Create content calendar (Task 5.4)

## Completed — Session 2026-06-18
* ✅ xii. Created `content-plan/aeo-page-template.md` — full AEO page structure with 9 sections, metadata table, and pre-publish quality checklist (Task 5.3)
* ✅ xiii. Created `content-plan/content-calendar.md` — inventory of 26 published pages and 15-page priority AEO build queue with monthly review schedule (Task 5.4)
* ✅ xiv. Published AEO page: NRC vs. Agreement State — Who Issues Your RAM License in New England? (/nrc-vs-agreement-state-new-england) — Licensing cluster, Priority 1
* ✅ xv. Published AEO page: Massachusetts Radioactive Material License Checklist (/massachusetts-radioactive-material-license-checklist) — Licensing cluster, Priority 3
* ✅ xvi. Published AEO page: Radioactive Material License Amendment: When and How to File (/radioactive-material-license-amendment-when-and-how-to-file) — Licensing cluster, Priority 4
* ✅ xvii. Published AEO page: NRC Inspection Records Checklist: What to Have Ready (/nrc-inspection-records-checklist) — Audits cluster, Priority 6

## Phase 5 task status update
* 5.3 AEO page/post template — ✅ Done (content-plan/aeo-page-template.md committed)
* 5.4 Content calendar — ✅ Done (content-plan/content-calendar.md committed)

## Completed — Session 2026-06-18 (continued)
* ✅ xviii. Published AEO page: Package Receipt Survey Requirements for Radioactive Material (/package-receipt-survey-requirements-for-radioactive-material) — Audits/Compliance cluster, Priority 7
* ✅ xix. Published AEO page: How Often Are Radiation Surveys Required? (/how-often-are-radiation-surveys-required) — Compliance cluster, Priority 8
* ✅ xx. Published AEO page: Decay-in-Storage Recordkeeping Requirements (/decay-in-storage-recordkeeping-requirements) — Compliance cluster, Priority 9
* ✅ xxi. Published AEO page: NRC Form 313 Checklist: What to Include in Your License Application (/nrc-form-313-checklist-what-to-include-in-your-license-application) — Licensing cluster, Priority 10
* ✅ xxii. Published AEO page: Radiation Safety Program Annual Review Checklist (/radiation-safety-program-annual-review-checklist) — Compliance cluster, Priority 11
* ✅ xxiii. Published AEO page: Radioactive Material License Reciprocity in New England (/radioactive-material-license-reciprocity-in-new-england) — Licensing cluster, Priority 5

## Immediate next actions
* i. Monthly analytics review (first review due 2026-07-18)
* ii. Review mobile layout and CTA visibility (Task 1.8)
* iii. Update About page content (Task 4.2)
* ✅ iv. Added internal links: Related Resources sections updated on Radioactive Material License Consulting, Radiation Safety Audits, and RSO Consulting service pages — linking to all 9 published AEO pages
* ✅ v. Built and published AEO pages: Priorities 12-15 (10 CFR Part 37, Nuclear Medicine License Additions, Radiation Shielding Evaluation, RSO Responsibilities)

## Completed — Session 2026-06-19
* ✅ xxiv. Published AEO page: 10 CFR Part 37: Requirements for Category 1 and Category 2 Radioactive Material (/10-cfr-part-37-requirements-for-category-1-and-category-2-radioactive-material) — Compliance cluster, Priority 12
* ✅ xxv. Published AEO page: Radioactive Material License Additions for Nuclear Medicine: Lu-177, I-131, and Ga-68 (/radioactive-material-license-additions-for-nuclear-medicine-lu-177-i-131-and-ga-68) — Licensing cluster, Priority 13
* ✅ xxvi. Published AEO page: Radiation Shielding Evaluation: When Is One Required? (/radiation-shielding-evaluation-when-is-one-required) — Technical cluster, Priority 14
* ✅ xxvii. Published AEO page: RSO Responsibilities: What Does a Radiation Safety Officer Actually Do? (/rso-responsibilities-what-does-a-radiation-safety-officer-actually-do) — RSO Support cluster, Priority 15

## Immediate next actions
* i. Monthly analytics review (first review due 2026-07-18)
* ii. Review mobile layout and CTA visibility (Task 1.8)
* iii. Update About page content (Task 4.2)
* iv. Build next AEO pages from content calendar priority queue (Priorities 16+)
* v. Add internal links on new AEO pages to related service pages as needed

## Completed — Session 2026-06-19 (continued)
* ✅ xxviii. Published AEO page: Connecticut Radioactive Material License: NRC Agreement State Transition Guide (/connecticut-radioactive-material-license) — Licensing cluster, Priority 2 (previously skipped)
* ✅ xxix. Published AEO page: Rhode Island Radioactive Material License: Who Regulates RAM in Rhode Island? (/rhode-island-radioactive-material-license) — Licensing cluster, Priority 16
* ✅ xxx. Published AEO page: Maine Radioactive Material License: NRC Regulates RAM in Maine (/maine-radioactive-material-license) — Licensing cluster, Priority 17
* ✅ xxxi. Published AEO page: New Hampshire Radioactive Material License: NRC Regulates RAM in New Hampshire (/new-hampshire-radioactive-material-license) — Licensing cluster, Priority 18
* ✅ xxxii. Published AEO page: Vermont Radioactive Material License: NRC Regulates RAM in Vermont (/vermont-radioactive-material-license) — Licensing cluster, Priority 19
* ✅ xxxiii. Published AEO page: What Is an Authorized User on a Radioactive Material License? (/authorized-user-radioactive-material-license) — Licensing cluster, Priority 20
* ✅ xxxiv. Updated content-plan/content-calendar.md — all 20 priorities marked Published, added Priorities 21-25 to build queue

## Immediate next actions
* i. Monthly analytics review (first review due 2026-07-18)
* ii. Review mobile layout and CTA visibility (Task 1.8)
* iii. Update About page content (Task 4.2)
* iv. Build next AEO pages from content calendar priority queue (Priorities 21+)
* v. Add internal links on state license pages to related service pages (Radioactive Material License Consulting, RSO Consulting, NRC vs. Agreement State page)
* 
## Completed — Session 2026-06-19 (AEO build: Priorities 21-25)
* ✅ xxxv. Published AEO page: What Is a Broad Scope Radioactive Material License? (/broad-scope-radioactive-material-license) — Licensing cluster, Priority 21
* ✅ xxxvi. Published AEO page: Radioactive Material License Termination: How to Close Out a License (/radioactive-material-license-termination) — Licensing cluster, Priority 22
* ✅ xxxvii. Published AEO page: NRC License Renewal: How to Renew a Radioactive Material License (/nrc-radioactive-material-license-renewal) — Licensing cluster, Priority 23
* ✅ xxxviii. Published AEO page: Radiation Dose Limits for Radiation Workers: 10 CFR Part 20 Summary (/radiation-dose-limits-radiation-workers) — Compliance cluster, Priority 24
* ✅ xxxix. Published AEO page: Radiation Exposure Monitoring: When Is Dosimetry Required? (/radiation-exposure-monitoring-dosimetry-requirements) — Compliance cluster, Priority 25
* ✅ xl. Updated Related Resources on all 5 state license pages (RI, ME, NH, VT, CT) — added RSO Consulting and NRC License Renewal links
* ✅ xli. Updated content-plan/content-calendar.md — all 25 priorities marked Published

## Immediate next actions
* i. Monthly analytics review (first review due 2026-07-18)
* ii. Review mobile layout and CTA visibility (Task 1.8)
* iii. Update About page content (Task 4.2)
* iv. Define and plan next AEO build priorities (Priorities 26+) based on search demand and content gaps
* 
## Completed — Session 2026-06-20
* ✅ xlii. Mobile layout and CTA visibility QA completed (Task 1.8) — hero CTA "Schedule a Free Consultation" → /contact verified; "Submit a Project Inquiry" → /request-a-quote/ verified; mobile preview shows full-width button and readable layout
* ✅ xliii. About page updated (Task 4.2) — added internal links to all 6 service pages and NRC vs. Agreement State AEO page; added "Ready to Work Together?" CTA section with Submit a Project Inquiry and View Our Services buttons
* ✅ xliv. Published AEO page: Radiation Safety Officer Qualifications: NRC and Agreement State Requirements (/radiation-safety-officer-qualifications-nrc-and-agreement-state-requirements) — RSO Support cluster, Priority 26
* ✅ xlv. Published AEO page: How to Write a Radiation Safety Program: Required Elements and Best Practices (/how-to-write-a-radiation-safety-program-required-elements-and-best-practices) — Compliance cluster, Priority 27
* ✅ xlvi. Published AEO page: Radioactive Waste Disposal: Options and Requirements for NRC Licensees (/radioactive-waste-disposal-options-and-requirements-for-nrc-licensees) — Compliance cluster, Priority 28
* ✅ xlvii. Published AEO page: Medical Radioactive Material License Requirements: I-131, Tc-99m, and PET Isotopes (/medical-radioactive-material-license-requirements-i-131-tc-99m-and-pet-isotopes) — Licensing cluster, Priority 29
* ✅ xlviii. Published AEO page: NRC Inspection Process: What to Expect During an NRC Inspection (/nrc-inspection-process-what-to-expect-during-an-nrc-inspection) — Audits cluster, Priority 30

## Phase 1 task status update
* 1.8 Mobile layout and CTA visibility — ✅ Done

## Phase 4 task status update
* 4.2 About page — ✅ Done (internal links added, CTA section added)

## Immediate next actions
* i. Monthly analytics review (first review due 2026-07-18)
* ii. Update content-plan/content-calendar.md — add Priorities 26-30 and mark Published
* iii. Add internal links on new AEO pages (26-30) to related service pages as needed
* iv. Define Priorities 31+ based on remaining content gaps and search demand
