# CHIWork 2026 Workshop — Submission Templates

**Workshop:** Interrogating GenAI Augmentation for CHIworkers: Strategies for Professional Autonomy and Accountability
**Date:** June 22, 2026 (Monday) — CHIWork 2026, Linz, Austria
**Workshop website:** [chiwork26-genai-accountability](https://haukecornell.github.io/chiwork26-genai-accountability/)

---

## Two submission tracks

### Track 1 — Position Papers (`track1-position-paper.tex`)

For researchers presenting an argument, critique, or finding related to GenAI use in HCI practice.

- **Length:** Up to 4 pages including references
- **Template:** `track1-position-paper.tex`
- **Format:** ACM sigconf (`\documentclass[sigconf]{acmart}`)
- **Review:** Light peer review by the organizing committee
- **Publication:** Submit to arXiv after acceptance (instructions on workshop website)
- **At the workshop:** 5-minute lightning talk + 3 slides

### Track 2 — AI Disclosure Statements (`track2-ai-disclosure.tex`)

For practitioners, industry professionals, and researchers who want to share a reflexive account of GenAI use in their daily HCI work. No research contribution required.

- **Length:** 1 page or a short paragraph — your choice
- **Template:** `track2-ai-disclosure.tex` (optional — any readable format accepted)
- **Pseudonymous submissions accepted**
- **At the workshop:** Publicly shared and discussed in working groups

---

## How to compile

Requires a TeX distribution with `acmart.cls` (included). Compile with:

```bash
pdflatex track1-position-paper
bibtex track1-position-paper
pdflatex track1-position-paper
pdflatex track1-position-paper
```

Or use [Overleaf](https://www.overleaf.com) — upload the contents of this repo as a new project.

---

## Files

| File | Purpose |
|------|---------|
| `track1-position-paper.tex` | Track 1 template |
| `track2-ai-disclosure.tex` | Track 2 template |
| `references.bib` | BibTeX file — workshop citation pre-filled |
| `acmart.cls` | ACM document class (required) |
| `ACM-Reference-Format.bst` | ACM bibliography style (required) |
| `acm-jdslogo.png` | Required by acmart.cls |
| `acmguide.pdf` | ACM author guide (reference only) |

---

## Workshop citation

The `references.bib` file includes a pre-populated entry for the workshop proposal (`\cite{sandhaus2026interrogating}`). Use this in your Track 1 paper to cite the workshop. The DOI/arXiv link will be updated once the proposal is published.

---

## Contact

- General: [hgs52@cornell.edu](mailto:hgs52@cornell.edu) (Hauke Sandhaus, Lead Facilitator)
- Paper review: [Pooja.Prajod@cwi.nl](mailto:Pooja.Prajod@cwi.nl) (Pooja Prajod, Paper Chair)
- Remote/hybrid: [malmutai@nd.edu](mailto:malmutai@nd.edu) (Mohammed Almutairi, Remote Track)
