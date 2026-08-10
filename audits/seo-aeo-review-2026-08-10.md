# SEO/AEO Review — 2026-08-10

## Executive summary
This run found two material regulatory/content issues and several validation-MVP copy issues that should be corrected before publishing additional AEO pages. Authenticated Google Search Console, Bing Webmaster Tools, and WordPress/Jetpack metrics were not accessible in this run, so no traffic, CTR, ranking, or coverage metrics are reported.

## 1. Regulatory accuracy audit

### A. RSO Qualifications page — Agreement State statement is outdated
Live URL: `/radiation-safety-officer-qualifications-nrc-and-agreement-state-requirements/`

Current live copy says: “In New England, Massachusetts and Connecticut are Agreement States.”

Replace that paragraph with:

> All six New England states — Connecticut, Maine, Massachusetts, New Hampshire, Rhode Island, and Vermont — are NRC Agreement States for agreement material. Most non-federal applicants in these states apply through the applicable state radiation control program rather than directly to the NRC. NRC retains authority over commercial nuclear reactors, research reactors, fuel-cycle facilities, federal agencies, and certain other retained areas or materials. RSO qualification details still vary by license type, state rule, license condition, and applicable guidance.

Official basis checked 2026-08-10:
- NRC Agreement States list: https://www.nrc.gov/agreement-states
- Connecticut: https://www.nrc.gov/agreement-states/connecticut
- Maine: https://www.nrc.gov/agreement-states/maine.html
- Massachusetts: https://www.nrc.gov/agreement-states/massachusetts.html
- New Hampshire: https://www.nrc.gov/agreement-states/new-hampshire
- Rhode Island: https://www.nrc.gov/agreement-states/rhode-island
- Vermont: https://www.nrc.gov/agreement-states/vermont

### B. Package Receipt Survey Requirements page — monitoring and notification language needs correction
Live URL: `/package-receipt-survey-requirements-for-radioactive-material/`

Current live copy overstates 10 CFR 20.1906 by implying every radioactive-material package requires a visual inspection, external surface and 1-meter dose measurements, and a wipe test. It also gives fixed wipe action levels of 22,000 dpm/100 cm² beta/gamma and 2,200 dpm/100 cm² alpha, which do not match the current transport contamination limits/method in 49 CFR 173.443 Table 9.

Recommended replacement core copy:

### What monitoring does 10 CFR 20.1906 require?

10 CFR 20.1906 does **not** require the same survey on every incoming radioactive-material package. The required monitoring depends on the package label, quantity, form of material, and condition of the package.

For an NRC licensee:

- A package bearing a Radioactive White-I, Yellow-II, or Yellow-III label must be monitored for **external radioactive contamination**, unless it contains only radioactive material in gaseous or special form as defined in 10 CFR 71.4.
- A labeled package must be monitored for **external radiation levels** unless the quantity is less than or equal to the applicable Type A quantity.
- Any package known to contain radioactive material must be monitored for contamination and radiation levels if there is evidence that package integrity may have degraded, such as crushing, wetness, or other damage.
- Required monitoring must be completed as soon as practical, but no later than 3 hours after receipt during normal working hours, or within 3 hours after the start of the next working day when received after hours.

A visual condition check is good practice and may be required by site procedures, but it should not be described as a separate universal monitoring requirement imposed by 10 CFR 20.1906(b).

### When is notification required?

Under 10 CFR 20.1906(d), an NRC licensee must immediately notify the final delivery carrier and the NRC Headquarters Operations Center when removable surface contamination exceeds the applicable limits referenced by 10 CFR 71.87(i), or when external radiation levels exceed the applicable limits in 10 CFR 71.47.

Do not reduce this to one universal “surface and 1-meter” threshold because transport limits differ for ordinary and exclusive-use shipments. For ordinary packages under 10 CFR 71.47(a), the external package surface limit is 2 mSv/h (200 mrem/h) and the transport index may not exceed 10. Applicable exclusive-use limits differ and should be evaluated under 10 CFR 71.47(b).

For transport contamination, current 49 CFR 173.443 Table 9 lists non-fixed external contamination limits of 240 dpm/cm² for beta/gamma emitters and low-toxicity alpha emitters and 24 dpm/cm² for other alpha emitters, using the measurement provisions in that section. Licensees should evaluate actual survey results using the applicable regulatory method and their license/procedure requirements rather than a simplified dpm/100 cm² number.

### Records

10 CFR 20.2103 requires records of surveys and calibrations required by 10 CFR 20.1501 and 20.1906(b) to be retained for 3 years. A facility procedure may require additional fields such as package ID, radionuclide/activity, instrument information, dose-rate results, wipe results, and corrective actions, but those fields should be presented as recommended/typical documentation rather than each being individually mandated by 10 CFR 20.2103.

Official basis checked 2026-08-10:
- NRC 10 CFR 20.1906: https://www.nrc.gov/reading-rm/doc-collections/cfr/part020/part020-1906.html
- eCFR 10 CFR 20.2103: https://www.ecfr.gov/current/title-10/chapter-I/part-20/subpart-L/section-20.2103
- NRC 10 CFR 71.47: https://www.nrc.gov/reading-rm/doc-collections/cfr/part071/part071-0047
- eCFR 49 CFR 173.443: https://www.ecfr.gov/current/title-49/subtitle-B/chapter-I/subchapter-C/part-173/subpart-I/section-173.443

## 2. Live-site QA and validation-MVP copy

### Homepage
Observed live:
- Hero CTA: **Schedule a Free Consultation**
- Main body CTA: **Submit a Project Inquiry**

Action: replace the hero CTA with **Submit a Project Inquiry** or **Request a Quote** so the site uses one validation-safe conversion model.

The homepage NRC License Consulting “Learn more” link currently targets `/radiation-license-consultant/`, while the indexed service page is `/radioactive-material-license-consulting/`. Confirm that the old target redirects correctly; otherwise update the homepage link.

### Contact page
Observed live copy includes:
- “We offer a free initial consultation with no obligation.”
- “We typically respond to all inquiries within one business day.”
- “Quick response – We respond to all inquiries within one business day.”

These contradict the repository’s validation-MVP guardrails.

Suggested replacement opening:

> Submit a project inquiry or general radiation-safety question. We review submissions to understand the need and may follow up when the request appears to be a good fit. Submitting a message does not create a consulting relationship or guarantee service or response time.

Suggested “What to Expect” bullets:
- **Submission review** — We review the information you provide to understand the request.
- **Possible follow-up** — We may contact you for additional information if the request appears to be a fit.
- **No obligation** — Submitting an inquiry does not commit either party to an engagement.
- **Project scope** — Any consulting work is defined separately in an agreed scope or proposal.

### RSO Consulting page
Observed live copy promises priority/immediate incident-response support for retainer clients. Until that operational capability is intentionally supported, replace with softer copy such as:

> Incident and corrective-action support may be included in a scoped RSO consulting engagement. Availability, response expectations, and regulatory-notification responsibilities should be defined in the engagement terms; the licensee remains responsible for maintaining required emergency arrangements and regulatory compliance.

### Radiation Safety Audits page
Observed live copy says most audits are completed within two to three weeks of engagement. Remove the turnaround promise. Suggested replacement:

> Scope, format, and timing are determined based on program complexity, records available for review, and whether the audit is remote or on site.

### Training and Surveys pages
Prefer **Submit a Training Inquiry** / **Request Survey Support** over “Schedule” language while the site remains a validation MVP.

## 3. Navigation/internal linking observations

- Primary navigation is simple: Home, About, Services, Training, Contact, Blog.
- The homepage successfully links to program development, audits, RSO consulting, training, and surveys pages during this review.
- The license-consulting homepage target needs redirect verification as noted above.
- New AEO pages should continue linking to one primary service page plus 2–4 closely related resources rather than creating isolated informational pages.

Priority internal links after corrections:
- Package receipt page → Radiation Surveys; RSO Consulting; NRC Inspection Records Checklist.
- RSO Qualifications → RSO Consulting; RAM License Consulting; License Amendment page.
- Sealed-source leak-test future page → Radiation Surveys; Radiation Safety Audits; RSO Consulting.

## 4. Analytics status

Authenticated Google Search Console, Bing Webmaster Tools, and WordPress/Jetpack analytics were not accessible from the available tools in this run. Therefore no impressions, clicks, CTR, average position, top-query, landing-page, crawl, or coverage metrics are reported.

Public search results do show multiple AEO/resource pages being discoverable, but this is not a substitute for Search Console indexing/coverage data.

## 5. Planning corrections still needed

`content-plan/content-calendar.md` should be corrected as follows:
- Priority 17 title → **Maine radioactive material license: Agreement State requirements and regulator**
- Priority 18 title → **New Hampshire radioactive material license: Agreement State requirements and regulator**
- Priority 19 title → **Vermont radioactive material license: Agreement State requirements and regulator**
- Repair malformed table cells in Priorities 22–25.

`TASKS.md` contains stale phase-table statuses that conflict with later completion notes (notably Bing Webmaster Tools and the lead tracker). Reconcile these during the next planning-file cleanup.

## 6. Priority order after this run

1. Publish the RSO Qualifications Agreement State correction.
2. Correct the Package Receipt Survey page before it earns additional search visibility.
3. Remove validation-MVP-incompatible promises from Home, Contact, RSO Consulting, Audits, Training, and Surveys.
4. Verify/repair the homepage license-consulting link target.
5. Clean up content-calendar titles/table formatting and stale TASKS statuses.
6. Review authenticated Search Console/Jetpack/Bing data when available and choose Priority 31+ from actual demand.
7. If analytics remain unavailable after remediation, draft **Sealed Source Leak Test Requirements and Records** as the next AEO page.
