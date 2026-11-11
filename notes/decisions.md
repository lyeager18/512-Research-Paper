# Research decisions log

Short entries: date, decision, reason.

## 2026-11-11
- **Waves 3-5 only.** Wave 3 (about 2010-2012) is the pre-BRI baseline; Waves 4-5 are the post-period. Wave 6 excluded: COVID-19 overlap confounds the post-period and AidData commitments end in 2021.
- **Outcomes.** H1: Core Topic A (economic evaluation), the only item present in all three waves. H2: China items (good/harm, influence) plus Core Topic M (trust in government). Wave 3's "impressions of China" item may not be comparable with Waves 4-5; to confirm in codebooks.
- **Donut zone.** Exclude respondents 25-50 km from a project to limit spillover contamination; test 10/25/50 km cutoffs as robustness.
- **Estimator.** Staggered DiD with Callaway-Sant'Anna or Sun-Abraham, plus event-study plots.
- **Project definition.** AidData covers all Chinese finance since 2000. To decide: post-2013 projects only, or all projects with a post-2013 robustness check.
- **Respondent locations.** Built from ABS technical-report sampling frames (province, district, commune). Wave 3 and Wave 4 Vietnam reports show mostly different communes each wave, so treatment is defined at district or province level where samples overlap.
- **Laos dropped.** Not confirmed in the ABS waves used.

## Open questions
- Do the public ABS files include subnational identifiers?
- Are all six countries in each of Waves 3-5?
- Enough respondents within 25 km of completed extraction projects?
