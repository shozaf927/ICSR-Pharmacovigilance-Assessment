# Individual Case Safety Report (ICSR): End-to-End Pharmacovigilance Assessment

A practical training project simulating Drug Safety Associate case processing: intake, validity, Day 0, MedDRA/WHODrug coding, seriousness, severity, expectedness, WHO-UMC/Naranjo causality, reporting decisions, narrative, follow-up and QC.

> Educational simulation only. All patient details and clinical facts are fictional. Not a real ICSR, medical advice or regulatory submission. Verify current regulations, product-specific RSI, licensed dictionaries and company SOPs before operational use.

## Learning objectives
1. Validate the four minimum ICSR criteria.
2. Establish Day 0 and preserve source chronology.
3. Prepare a structured case narrative.
4. Apply MedDRA and WHO Drug Dictionary coding principles.
5. Distinguish seriousness from severity and expectedness.
6. Perform WHO-UMC and Naranjo causality assessments.
7. Separate post-marketing ICSR reporting from clinical-trial SUSAR reporting.
8. Apply India-specific MAH timelines and regional rules.
9. Perform follow-up and quality control.

## Repository structure
- `docs/01-icsr-fundamentals.md` — definition, validity, Day 0 and lifecycle
- `docs/02-intake-triage-and-data-entry.md` — intake, triage, duplicate search and data capture
- `docs/03-medical-and-drug-coding.md` — MedDRA and WHODrug
- `docs/04-seriousness-severity-expectedness.md` — three independent assessments
- `docs/05-causality-assessment.md` — WHO-UMC and worked Naranjo score
- `docs/06-reporting-and-regulatory-compliance.md` — India, ICH and SUSAR pathways
- `docs/07-case-processing-qc-and-follow-up.md` — narrative, follow-up and QC
- `case-study/fictional-anaphylaxis-case.md` — synthetic source case
- `case-study/completed-icsr-assessment.md` — completed DSA assessment
- `tools/icsr-processing-worksheet.md` — reusable worksheet
- `tools/decision-tree.md` — processing flow
- `REFERENCES.md` — primary and official references
- `DISCLAIMER.md` — educational and privacy disclaimer

## Fictional case summary
A 34-year-old woman develops anaphylaxis approximately 15 minutes after a reported first oral dose of amoxicillin/clavulanate 625 mg. Findings include urticaria, lip/tongue swelling, wheezing, dyspnoea, BP 78/46 mmHg and SpO2 89%. She receives emergency treatment and is admitted for observation.

| Assessment | Training conclusion |
|---|---|
| Validity | Valid (four minimum criteria present) |
| Seriousness | Serious: life-threatening features and inpatient admission reported |
| Clinical intensity | Severe; no CTCAE grade assigned |
| Expectedness | Assumed expected only for this exercise; verify actual local RSI in real cases |
| WHO-UMC | Possible (provisional) |
| Naranjo | 5 — Probable |
| India MAH route | Serious post-marketing case; CDSCO guidance cited here specifies 15 calendar days |
| SUSAR | Not applicable; this is not a clinical-trial case |

## Critical distinctions
- An AE does not require established causality; an ADR implies at least suspected causality under the applicable definition.
- Seriousness is a regulatory outcome/action classification; severity is clinical intensity.
- Expectedness is assessed against the applicable product-specific RSI, not generic knowledge.
- SUSAR is a clinical-trial category, not a synonym for every serious post-marketing ICSR.
- WHO-UMC and Naranjo support judgement; neither replaces medical review or regulatory reportability assessment.

## Recommended study sequence
Read the seven guides, examine the fictional source case, complete the worksheet independently, then compare with the completed assessment. Never upload identifiable patient data or confidential safety records to a public repository.