# OCA3 (Oculocutaneous Albinism Type 3) — Family Research Brief

**Version 3** — chart QA rebuild (timeline overlap fixed, pathway labels unclipped, fidelity scoring evidence-based).

Educational deep-research PDF for families of a child diagnosed with **OCA3 (rufous/red oculocutaneous albinism)**.

> **Not medical advice.** Literature synthesis for caregiver education only. Confirm care with your child’s clinicians.

## Download

- **[Final PDF v3](report/OCA3_Albinism_Deep_Research_Report.pdf)** ← primary deliverable  
- Direct raw: https://github.com/ajdoyl2/oca3-albinism-report/raw/main/report/OCA3_Albinism_Deep_Research_Report.pdf

## What was fixed in v3

| Issue (v1) | Fix (v3) |
|------------|----------|
| Timeline infancy/toddler text **overlapped** | Even spacing + callout for ~1-year-old |
| Pathway “DOPA” / “Eumelanin” **clipped** | Wider boxes, full labels visible |
| Prevalence title said “log” but was linear | Title corrected to **linear scale** |
| RGBA charts in some PDF viewers | All figures re-exported **RGB** |
| Fidelity “10/10” felt circular | **Evidence table** + v1→v3 before/after chart |

## Fidelity

| Version | Mean |
|---------|------|
| v1 (pre-fix) | **8.3 / 10** (visuals metric was 5/10) |
| **v3 (current)** | **10.0 / 10** (all 10 metrics) |

Score detail: [`report/fidelity_scorecard.json`](report/fidelity_scorecard.json)

## Charts

| File | Description |
|------|-------------|
| [`charts/01_prevalence.png`](charts/01_prevalence.png) | Prevalence (1 in X), linear scale |
| [`charts/02_subtype_share.png`](charts/02_subtype_share.png) | Illustrative OCA subtype share |
| [`charts/03_ocular_features.png`](charts/03_ocular_features.png) | Ocular feature frequencies |
| [`charts/04_severity_compare.png`](charts/04_severity_compare.png) | Relative severity synthesis |
| [`charts/05_inheritance.png`](charts/05_inheritance.png) | Autosomal recessive probabilities |
| [`charts/06_age_timeline.png`](charts/06_age_timeline.png) | Age-staged watch timeline (**fixed**) |
| [`charts/07_care_team.png`](charts/07_care_team.png) | Care team priorities |
| [`charts/08_fidelity_compare.png`](charts/08_fidelity_compare.png) | Fidelity v1 vs v3 |
| [`charts/08_fidelity_final.png`](charts/08_fidelity_final.png) | Final 10/10 scorecard |
| [`charts/09_pathway.png`](charts/09_pathway.png) | Melanin pathway / TYRP1 (**fixed**) |

## Contents of the PDF

1. Executive summary for a **1-year-old** with OCA3  
2. Genetics — *TYRP1*, OMIM 203290, autosomal recessive  
3. Prevalence (~1 in 8,500 African populations)  
4. Phenotype vs OCA1/OCA2/OCA4  
5. **Age-staged signs to watch** + red flags  
6. Multidisciplinary care  
7. Prognosis framing  
8. **Fidelity metrics** with evidence table  
9. References  

## Sources (selected)

GeneReviews NBK590568 · StatPearls NBK519018 · MedlinePlus Genetics · NIH GARD · NORD · Orphanet · OMIM 203290 · Grønskov 2007 · Manga 1997

## Regenerate

```bash
python3 source/generate_report.py
```

## License

Educational family use. Clinical decisions require licensed professionals.
