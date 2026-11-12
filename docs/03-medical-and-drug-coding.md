# Medical and Drug Coding

## MedDRA hierarchy
MedDRA is used to code adverse events, medical history, indications and other regulatory medical concepts. Its five levels are:
1. Lowest Level Term (LLT)
2. Preferred Term (PT)
3. High Level Term (HLT)
4. High Level Group Term (HLGT)
5. System Organ Class (SOC)

Select the most accurate current LLT for the reported concept; the LLT links to a PT. Preserve the clinical meaning. Do not upgrade a symptom to a diagnosis without source support.

## Coding principles
- Code what the reporter actually reported.
- Prefer a documented diagnosis when supported by source.
- Do not code a suspected diagnosis as confirmed if only symptoms were reported.
- Do not infer diagnoses from isolated lab values.
- Avoid redundant diagnosis-plus-symptom coding unless clinically meaningful or required by convention/SOP.
- Check current MedDRA version, term status, hierarchy and coding conventions.
- Never invent numeric MedDRA codes; verify exact LLT/PT and SOC in the licensed browser/version.

## Fictional case: candidate concepts for verification
| Verbatim/source concept | Candidate medical concept | Caution |
|---|---|---|
| Emergency physician documented “anaphylaxis” | Anaphylactic reaction | Verify exact current LLT/PT |
| Raised itchy wheals | Urticaria | Map verbatim precisely |
| Wheeze | Wheezing | Do not infer asthma |
| BP 78/46; documented hypotension | Hypotension | Retain value in narrative |
| Lip/tongue swelling | Angioedema | Confirm source wording |
| Difficulty breathing | Dyspnoea | Avoid unnecessary duplication |

This is a coding proposal, not a dictionary extract. Final codes must be verified in the licensed current MedDRA release.

## WHO Drug Dictionary
WHODrug standardises medicinal products and active ingredients. Capture exact brand, ingredient(s), strength, formulation, manufacturer, country, route, dose and combination-product representation according to local database conventions. Verify the current dictionary release; do not guess codes.

**Dictionary distinction:** MedDRA codes medical concepts; WHODrug standardises medicinal products. Neither replaces the clinical narrative.

## E2B(R3)
ICH E2B(R3) defines structured electronic ICSR data elements and message specifications. A narrative or CIOMS-I form does not by itself prove an E2B message is technically valid. Apply regional implementation guides and validation rules.