# SEO/AEO Review — 2026-09-14

## Executive summary
Accuracy remediation remains higher priority than publishing Priority 31. Several material issues are still live, and the NRC's EO 14300 tracker has a new rulemaking status that makes multiple July posts stale.

## Regulatory accuracy findings

### P0 — DOE/ALARA article remains unsupported
The homepage still promotes **“DOE Removed ALARA in January 2026. Now the NRC Is Following.”** Current DOE Occupational Radiation Protection Program guidance continues to state that occupational doses governed by 10 CFR 835 are required to be ALARA. No primary DOE source was found supporting the article's claim that DOE removed ALARA in January 2026.

Manual WordPress action:
- Remove or substantially reframe the DOE-removal claim.
- Add a visible correction/update note dated 2026-09-14.
- Prefer consolidation into one authoritative NRC radiation-protection-rulemaking article.

Primary source: https://www.energy.gov/ehss/occupational-radiation-protection-program-10-cfr-835

### P0 — NRC radiation-protection rulemaking status changed
The NRC's current EO 14300 tracker now lists **Reforming and Modernizing the NRC's Radiation Protection Framework (NRC-2025-1140)** in **Final** phase with a scheduled publication date of **2027-02-17**. This means site language saying the final rule is “expected November 2026” is stale. The rule is not yet a published final rule, so current requirements still apply.

Manual WordPress action:
- Remove expired “comments through August 31, 2026” calls to action.
- Replace “final rule expected November 2026” with dated status language such as: “As of September 14, 2026, NRC lists this rulemaking in Final phase, with final-rule publication scheduled for February 17, 2027. Current regulations remain in effect until a final rule is published and becomes effective.”
- Apply this update to the main ALARA/radiation-protection posts and any related tracker pages.

Primary source: https://www.nrc.gov/about-nrc/governing-laws/advance-act/wholesale-revision-regs

### P0 — Medical-use rulemaking timeline is stale
The live medical-use article says the final rule is expected in November 2026. NRC's current EO 14300 tracker lists **Reducing Barriers to Medical Use Licensing (NRC-2025-1237)** in Final phase with scheduled publication on **2027-03-31**.

Manual WordPress action:
- Replace the November 2026 forecast with the current NRC tracker status and 2027-03-31 scheduled publication date.
- Keep the page explicit that existing Part 35 requirements remain in effect until a final rule is published and effective.

Primary source: https://www.nrc.gov/about-nrc/governing-laws/advance-act/wholesale-revision-regs

### P0 — Package receipt page remains materially inaccurate
The live page still says a receipt survey must include visual inspection, surface and 1-meter dose-rate measurements, and a removable-contamination wipe test as a general package-receipt requirement. 10 CFR 20.1906(b) instead has distinct triggers:
- contamination monitoring for labeled packages, except packages containing only gas or special-form material;
- radiation-level monitoring for labeled packages only when quantity exceeds the Type A quantity;
- both contamination and radiation-level monitoring when package integrity appears degraded.

The live page also gives 22,000 dpm/100 cm² beta/gamma and 2,200 dpm/100 cm² alpha as notification thresholds. Current 49 CFR 173.443 Table 9 lists non-fixed contamination limits of 240 dpm/cm² for beta/gamma and low-toxicity alpha emitters and 24 dpm/cm² for other alpha emitters (with the rule's specified wipe methodology). 10 CFR 20.1906(d) points notification decisions to 10 CFR 71.87(i) and 71.47 rather than to the site's simplified universal values.

Manual WordPress action:
- Rewrite “What Must the Survey Include?” around the actual 20.1906(b)(1)-(3) triggers.
- Remove the universal “wipe required for Yellow-II/Yellow-III” statement.
- Rework action-level language so it cites the applicable Part 71 / transport limits and package condition.

Primary sources:
- https://www.law.cornell.edu/cfr/text/10/20.1906
- https://www.ecfr.gov/current/title-49/subtitle-B/chapter-I/subchapter-C/part-173/subpart-I/section-173.443

### P0 — Agreement State copy is still wrong on two live pages
The RSO Qualifications page still says only Massachusetts and Connecticut are Agreement States in New England. The New England consulting page still describes Massachusetts as an Agreement State and CT/RI/NH/VT/ME as NRC-regulated states. NRC's current Agreement State list includes all six New England states: CT, ME, MA, NH, RI, and VT.

Preferred replacement:
> All six New England states — Connecticut, Maine, Massachusetts, New Hampshire, Rhode Island, and Vermont — are NRC Agreement States for agreement material. NRC retains authority over reactors, federal agencies, and certain other facilities and materials.

Primary sources:
- https://www.nrc.gov/agreement-states
- https://www.nrc.gov/agreement-states/connecticut

### P1 — Radiation Safety Program Development overstates 10 CFR 20.1101
The live Program Development page says it designs “ALARA programs that satisfy 10 CFR 20.1101 requirements including written ALARA goals, investigation levels, dose trending procedures, and annual review processes.” Section 20.1101 requires a documented radiation protection program, practical ALARA procedures/engineering controls, and at least annual review, but it does not itself universally require written ALARA goals or investigation levels.

Manual WordPress action:
- Change to: “We develop ALARA program elements appropriate to the license type and regulatory guidance, including dose trending, investigation levels where appropriate, and the annual radiation-protection-program review required by 10 CFR 20.1101(c).”

Primary source: https://www.law.cornell.edu/cfr/text/10/20.1101

### P1 — RSO Consulting cites the wrong requirement for management reports
The live RSO Consulting page says periodic-review reports are “provided to management as required by 10 CFR 35.24(b).” Section 35.24(b) addresses management appointment of the RSO and the RSO's responsibility for implementing the program; it does not create a general requirement to provide periodic review reports to management.

Manual WordPress action:
- Remove “as required by 10 CFR 35.24(b)” from the periodic-review paragraph, or cite the actual applicable program-review/license-condition requirement for the specific license type.

Primary source: https://www.nrc.gov/materials/miau/med-use-toolkit/auth-individuals

## Live-site SEO/QA findings
- `/services/` and `/services-2/` remain live and substantially overlap. Consolidate to one service hub, preferably `/services/`, then redirect/retire `/services-2/` and normalize internal links.
- Both service pages still advertise a **free initial consultation**, conflicting with the repository's validation-MVP guardrail. Replace with **Submit a Project Inquiry** or **Request a Quote**.
- `/radiation-safety-consulting-new-england/` also still offers a free consultation.
- The Contact page is now aligned with validation-safe wording and explicitly avoids a service/response guarantee.
- Older March content still contains “schedule a free consultation” language; use a site-wide search in WordPress for that phrase during cleanup.

## Analytics
Authenticated Google Search Console, Bing Webmaster Tools, and WordPress/Jetpack performance data were not accessible in this run. No impressions, clicks, CTR, average position, coverage/indexing counts, top queries, or landing-page metrics are reported because they could not be verified.

## Content priority decision
Do **not** publish Priority 31 yet. The highest-value sequence is:
1. Fix the DOE/ALARA article.
2. Update NRC-2025-1140 and NRC-2025-1237 timeline/status language.
3. Correct the package-receipt page.
4. Correct both Agreement State pages.
5. Fix the two newly identified citation/requirements issues on Program Development and RSO Consulting.
6. Consolidate `/services-2/` and remove remaining free-consultation CTAs.
7. Use authenticated analytics to select the next AEO page.

If analytics remain unavailable after remediation, keep **Sealed Source Leak Test Requirements and Records** as the provisional Priority 31, followed by survey-meter calibration and radioactive-material inventory/recordkeeping.
