# Pediatric Radiology Academic Productivity Percentile Calculator

## Overview

This calculator provides academic productivity benchmarking for pediatric radiologists in the United States. It allows faculty members to compare their scholarly metrics against peers at similar career stages and academic ranks.

**Database:** 903 pediatric radiology faculty members from U.S. academic medical centers

**Data Source:** Scopus bibliometric database

---

## Features

### Two Ways to Use

1. **Enter Metrics Tab** – Input your own publication data to see your percentile ranking
2. **Find by Name Tab** – Search for any faculty member in the database to view their metrics

### Filtering Options

- **Academic Rank:** Professor, Associate Professor, Assistant Professor, Instructor
- **Academic Age:** Filter by years since first publication (e.g., 0-10 years, 11-20 years)
- Compare against all faculty or a specific peer group

---

## Metrics Explained

### Traditional Metrics

| Metric | Description |
|--------|-------------|
| **H-index** | Author has *h* papers with at least *h* citations each |
| **Total Publications** | Lifetime publication count in Scopus |
| **Total Citations** | Sum of all citations received |
| **First-Author Papers** | Publications where the individual is listed first |
| **Last-Author Papers** | Publications where the individual is listed last (typically indicates senior/mentorship role) |

---

## The RY Metric (Revised Yousem Metric)

### Why a New Metric?

Traditional metrics like h-index and total publications treat all authorships equally. However, in academic medicine:

- **First authorship** typically indicates the person who did the primary work
- **Last authorship** typically indicates the senior mentor or principal investigator
- **Middle authorship** often reflects collaborative contributions but less direct leadership

A faculty member with 50 first/last author papers demonstrates different scholarly impact than someone with 50 middle-author papers, yet traditional metrics score them identically.

### The Formula

```
RY = Weighted Citations + (10 × Weighted Publications)
```

Where:
- **First/Last author papers** are weighted at **5×**
- **Middle author papers** are weighted at **1×**

### Calculation Details

```
Weighted Publications = (First-Author Pubs × 5) + (Last-Author Pubs × 5) + (Middle-Author Pubs × 1)

Weighted Citations = (First-Author Citations × 5) + (Last-Author Citations × 5) + (Middle-Author Citations × 1)

RY = Weighted Citations + (10 × Weighted Publications)
```

### Example

| Author | First-Auth Pubs | Last-Auth Pubs | Middle-Auth Pubs | Total Pubs | RY Calculation |
|--------|-----------------|----------------|------------------|------------|----------------|
| **Dr. A** | 30 | 20 | 10 | 60 | Much higher RY (research leader) |
| **Dr. B** | 5 | 5 | 50 | 60 | Lower RY (collaborative contributor) |

Both have 60 total publications, but the RY Metric distinguishes Dr. A as having a stronger independent research portfolio.

### Interpretation

The RY Metric helps identify:
- **Research leaders** who drive projects as first or senior author
- **Career trajectory** — rising faculty building first-author portfolios
- **Mentorship activity** — senior faculty accumulating last-author papers

---

## Data Collection Methodology

1. **Faculty Identification:** Pediatric radiology faculty identified from U.S. academic medical center websites
2. **Scopus Matching:** Each faculty member matched to their Scopus author profile using name + institution + middle initial disambiguation
3. **Publication Analysis:** All publications retrieved and categorized by authorship position
4. **H-index Collection:** Retrieved via Scopus author profiles
5. **Quality Control:** Manual verification of ambiguous matches

---

## Academic Rank Definitions

| Rank | Typical Experience |
|------|-------------------|
| **Professor** | Senior faculty, typically 15+ years |
| **Associate Professor** | Mid-career, typically 8-15 years |
| **Assistant Professor** | Early career, typically 3-8 years |
| **Instructor** | Entry level, typically 0-3 years |

---

## Limitations

- Data reflects a point-in-time snapshot; metrics change as new publications appear
- Scopus coverage may miss some publications (especially older works or non-indexed journals)
- Author disambiguation relies on name matching algorithms; some errors possible
- Self-citations are included in citation counts (consistent with standard h-index calculation)

---

## Citation

If referencing this calculator or the RY Metric in academic work:

> Yousem DM. Pediatric Radiology Academic Productivity Percentile Calculator. Johns Hopkins University School of Medicine. Available at: https://dyousem1.github.io/

---

## Related Calculators

- [Neuroradiology Calculator](https://dyousem1.github.io/) (purple theme)
- [MSK Radiology Calculator](https://dyousem1.github.io/) (green theme)
- [Breast Imaging Calculator](https://dyousem1.github.io/) (pink theme)
- [Nuclear Medicine Calculator](https://dyousem1.github.io/) (brown theme)

---

## Contact

**David M. Yousem, MD, MBA**  
Johns Hopkins University School of Medicine  
Department of Radiology

---

*Last updated: December 2024*
