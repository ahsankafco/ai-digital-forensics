# AI-Driven Digital Forensics
### A Systematic Review of Capabilities, Limitations, and Research Challenges

**An interactive research platform for exploring artificial intelligence in digital forensic investigations.**

[![Website](https://img.shields.io/badge/Website-Live-2ea44f?style=flat-square)](https://ahsankafco.github.io/ai-digital-forensics/)
[![Publication](https://img.shields.io/badge/Publication-MDPI%20Digital-blue?style=flat-square)](https://doi.org/10.3390/digital6040094)
[![License: CC BY 4.0](https://img.shields.io/badge/Article%20License-CC%20BY%204.0-lightgrey?style=flat-square)](https://creativecommons.org/licenses/by/4.0/)

---

## Overview

**AI-Driven Digital Forensics** is an academic research companion website developed to communicate and explore the findings of the peer-reviewed systematic review:

*AI-Driven Digital Forensics: A Systematic Review of Capabilities, Limitations, and Research Challenges.*

Published in *Digital* (2026), the study examines how artificial intelligence (AI) and machine learning (ML) support digital forensic investigations, identifies limitations affecting their reliability, and outlines research priorities for trustworthy and legally defensible forensic AI.

This website transforms the review's findings into an accessible, interactive research resource for researchers, forensic investigators, cybersecurity professionals, educators, and students.

**Live Website:** https://ahsankafco.github.io/ai-digital-forensics/

**Official Publication:** https://doi.org/10.3390/digital6040094

## Research Highlights

The systematic review provides a structured synthesis of AI/ML applications across major digital forensic domains.

| Research Component | Scope |
|---|---|
| Literature synthesis | 76 peer-reviewed studies |
| Forensic task assessment | 16 representative task groups |
| Assessment framework | 6 maturity dimensions |
| Evidence audit | 96 task-dimension ratings |
| Methodology | PRISMA-informed systematic review |
| Sensitivity analysis | Alternative weights, thresholds, and ratings |

The research evaluates reported capabilities alongside dataset availability, validation practices, reproducibility, explainability, adversarial robustness, and forensic admissibility considerations.

## Research Evidence Explorer

The website includes an interactive **Research Evidence Explorer** that allows visitors to examine and compare the literature-informed maturity assessments presented in the published study.

### Features

- Interactive exploration of 16 forensic task groups.
- Search and filtering by task and maturity classification.
- Comparison of six assessment dimensions.
- Visualization of task maturity scores and classifications.
- Evidence-based explanations of limitations and research gaps.
- Links to the authoritative peer-reviewed publication.
- Responsive interface with a distinctive digital forensic visual design.

### Task Maturity Framework

The framework assesses AI-assisted forensic tasks using six dimensions:

1. **Observability:** Accessibility of relevant forensic artifacts.
2. **Labelability:** Availability of reliable ground-truth labels.
3. **Stationarity:** Stability of patterns across environments and time.
4. **Time-to-Insight:** Practical efficiency of investigative analysis.
5. **Explainability:** Interpretability and justification of AI-assisted findings.
6. **Adversarial Robustness:** Resistance to deliberate manipulation.

Each dimension receives an ordinal assessment of 0 (unfavorable), 1 (conditional), or 2 (favorable), based on the reviewed evidence and specified task conditions.

### Baseline Classification Results

| Classification | Task Groups |
|---|---:|
| Comparatively mature | 3 |
| Conditionally applicable | 12 |
| Currently constrained | 1 |
| **Total** | **16** |

These classifications represent literature-informed author judgments. They are not independently validated measures of operational readiness, complete automation, or legal admissibility.

For complete assessment criteria, supporting evidence, and qualifications, consult Sections 3.1–3.6 and Tables 7–14 of the published article.

## Research Coverage

The systematic review examines AI applications in:

- File identification and carving
- Malware and memory forensics
- Network and intrusion forensics
- Cloud and IoT/IIoT forensics
- Blockchain and cryptocurrency investigations
- Mobile device and social media forensics
- Multimedia and biometric analysis
- Vehicle and drone forensics
- Timeline reconstruction and evidence correlation
- Document and communication forensics
- Explainable AI, adversarial robustness, and forensic evidence reliability

The website presents selected findings from these areas and provides research-oriented explanations and frequently asked questions.

## Research Contributions

The published study makes three principal contributions:

**1. Cross-domain literature synthesis**

A comparative assessment connecting forensic tasks, AI/ML methods, reported findings, and application-specific limitations.

**2. Six-dimensional task maturity framework**

A structured approach to assessing practical AI assistance using explicit ordinal criteria, an evidence audit, and sensitivity analysis.

**3. Research agenda for trustworthy forensic AI**

Research priorities addressing representative datasets, external validation, reproducibility, explainability, adversarial testing, operational evaluation, and accountable human–AI collaboration.

## Website Technology

The website is implemented as a static, responsive research platform hosted using GitHub Pages.

Its design emphasizes:

- Accessible research communication
- Interactive evidence exploration
- Responsive layouts
- Search-engine-readable content
- Structured publication information
- Direct links to authoritative research sources

### Repository Structure

```text
ai-digital-forensics/
├── index.html
├── README.md
├── robots.txt
├── sitemap.xml
└── google-site-verification.html
```

*The Google verification filename in the actual repository is account-specific and should be preserved unchanged.*

## Getting Started

### View Online

Visit:

https://ahsankafco.github.io/ai-digital-forensics/

### Run Locally

Clone the repository:

```bash
git clone https://github.com/ahsankafco/ai-digital-forensics.git
cd ai-digital-forensics
```

Open `index.html` in a modern web browser.

No backend service is required for the static website.

## Publication and Citation

If this research supports your academic work, please cite the original peer-reviewed publication:

**Islam, A.U.; Shashidhar, N.K.; Islam, A.R.; Perera, W.S.** AI-Driven Digital Forensics: A Systematic Review of Capabilities, Limitations, and Research Challenges. *Digital* **2026**, *6*, 94.

https://doi.org/10.3390/digital6040094

### BibTeX

```bibtex
@article{islam2026aidriven,
  title   = {AI-Driven Digital Forensics:
             A Systematic Review of Capabilities,
             Limitations, and Research Challenges},
  author  = {Islam, Ahsan Ul and
             Shashidhar, Narasimha K. and
             Islam, ABM Rezbaul and
             Perera, Wadduwage Shanika},
  journal = {Digital},
  volume  = {6},
  number  = {4},
  pages   = {94},
  year    = {2026},
  doi     = {10.3390/digital6040094},
  url     = {https://doi.org/10.3390/digital6040094}
}
```

## Authors

**Ahsan Ul Islam**  
**Narasimha K. Shashidhar**  
**ABM Rezbaul Islam**  
**Wadduwage Shanika Perera**

Department of Computer Science  
Sam Houston State University  
Huntsville, Texas, USA

### Research Profiles

- [Google Scholar](https://scholar.google.com/citations?user=2Gn79w0AAAAJ)
- [ORCID](https://orcid.org/0009-0000-9525-4772)
- [Research Website](https://ahsankafco.github.io/ai-digital-forensics/)

## Research Integrity and Disclaimer

This website is an independent companion resource for the published systematic review.

Its interactive content summarizes and visualizes selected research findings. It does not replace the peer-reviewed publication.

The task maturity ratings are literature-informed ordinal assessments, not independently calibrated performance measurements. Their interpretation depends on the task conditions, supporting evidence, and limitations documented in the article.

AI-assisted forensic findings require appropriate human verification, evidence preservation, and consideration of applicable legal requirements.

## Licensing

The original journal article is published open access under the **Creative Commons Attribution 4.0 International (CC BY 4.0)** license.

The license for the website's original source code and design has not been separately specified. The article's CC BY license should not automatically be interpreted as applying to all repository code.

## Contact

For academic collaboration, research discussions, or questions concerning the publication:

**Ahsan Ul Islam**  
Ph.D. Researcher, Digital and Cyber Forensic Science  
Sam Houston State University

Email: axi034@shsu.edu

---

**Advancing trustworthy, explainable, and evidence-driven artificial intelligence for digital forensic investigations.**
