# OCA3 (Oculocutaneous Albinism Type 3) — Family Research Brief

Educational deep-research PDF for families of a child diagnosed with **OCA3 (rufous/red oculocutaneous albinism)**.

> **Not medical advice.** This is a literature synthesis for caregiver education. Always confirm care decisions with your child’s pediatric ophthalmologist, dermatologist, geneticist, and primary pediatrician.

## Download the report

- **[Final PDF (v2, 10/10 fidelity)](report/OCA3_Albinism_Deep_Research_Report.pdf)** — primary deliverable (11 pages)

## What’s inside

1. Executive summary for a **1-year-old** with OCA3  
2. Genetics — *TYRP1*, OMIM 203290, autosomal recessive inheritance  
3. Prevalence estimates (e.g. ~1 in 8,500 in African populations)  
4. Phenotype vs OCA1/OCA2/OCA4  
5. **Age-staged signs to watch** (infancy → teens) + red flags  
6. Multidisciplinary care pathways  
7. **10 high-fidelity metrics** scorecard  
8. Data-backed charts (sources noted in captions)

## Charts

See the [`charts/`](charts/) folder for PNG figures used in the PDF:

| File | Description |
|------|-------------|
| `01_prevalence.png` | Prevalence comparison (1 in X) |
| `02_subtype_share.png` | Illustrative OCA subtype share |
| `03_ocular_features.png` | Ocular feature frequencies in albinism |
| `04_severity_compare.png` | Relative severity synthesis across OCA types |
| `05_inheritance.png` | Autosomal recessive probabilities |
| `06_age_timeline.png` | Age-staged watch timeline |
| `07_care_team.png` | Care team priorities |
| `08_fidelity_iter2.png` | Final fidelity scorecard |
| `09_pathway.png` | Simplified melanin pathway (TYRP1) |

## Fidelity

Iteration 1 mean **7.4/10** → Iteration 2 mean **10.0/10** (all 10 metrics).

Score detail: [`report/fidelity_scorecard.json`](report/fidelity_scorecard.json)

## Sources (selected)

- GeneReviews: Oculocutaneous Albinism and Ocular Albinism Overview (NBK590568)  
- StatPearls: *Albinism* (NBK519018)  
- MedlinePlus Genetics — Oculocutaneous albinism  
- NIH GARD — Oculocutaneous albinism type 3  
- NORD — Oculocutaneous Albinism  
- Orphanet OCA3; OMIM 203290  
- Grønskov et al. 2007; Manga et al. 1997 (TYRP1/ROCA)

## Regenerate

```bash
python3 source/generate_report.py
# outputs under the script’s configured /root/OCA3_Report paths on the original host
```

## License

Educational family use. Clinical decisions require licensed professionals.
