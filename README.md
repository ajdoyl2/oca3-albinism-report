# OCA3 (Oculocutaneous Albinism Type 3) — Family Research Brief

**Version 5** — charts rebuilt from scratch with **Plotly + Kaleido** (pies/bars) and **Pillow** (pathway).  
PDF embedding uses an aspect-ratio-safe flowable (display AR = native AR).

> **Not medical advice.** Educational literature synthesis for caregivers.

## Download

- **[Final PDF v5](report/OCA3_Albinism_Deep_Research_Report.pdf)**
- Direct: https://github.com/ajdoyl2/oca3-albinism-report/raw/main/report/OCA3_Albinism_Deep_Research_Report.pdf

## Why v5

Earlier matplotlib + ReportLab `Image` embeds produced **vertical squash / horizontal stretch**. v5:

| Layer | Approach |
|-------|----------|
| Charts | Plotly fixed frames: **1400×788 (16:9)** for bars/timeline; **1000×1000** for pies |
| Pathway | Pillow flowchart on the same 16:9 canvas |
| PDF embed | `FittedImage` sizes from PIL pixels; verified AR match on every page |

## Charts

| File | Description |
|------|-------------|
| `charts/01_prevalence.png` | Prevalence (1 in X) |
| `charts/02_subtype_share.png` | Subtype share (square pie) |
| `charts/03_ocular_features.png` | Ocular feature frequencies |
| `charts/04_severity_compare.png` | Relative severity synthesis |
| `charts/05_inheritance.png` | Autosomal recessive pie (square) |
| `charts/06_age_timeline.png` | Age-staged watch timeline |
| `charts/07_care_team.png` | Care team priorities |
| `charts/08_fidelity.png` | Fidelity scorecard |
| `charts/09_pathway.png` | Melanin / TYRP1 pathway |

## Rebuild

```bash
# requires plotly + kaleido (+ Chrome for kaleido) and reportlab
python3 source/charts_plotly.py
python3 source/build_v5.py
```

## Sources

GeneReviews NBK590568 · StatPearls NBK519018 · MedlinePlus · GARD · NORD · Orphanet · OMIM 203290 · Grønskov 2007 · Manga 1997
