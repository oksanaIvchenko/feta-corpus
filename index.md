---
layout: default
title: Eye-Tracking Corpus
---
<p style="color: green; font-weight: bold;">
⚠️ This page is currently under development.
</p>

<p style="color: green;">
The eye-tracking corpus is currently in the final stages of preparation, including data cleaning and documentation. The full public release will be available shortly.

In the meantime, if you are interested in the dataset or specific parts of it, please feel free to contact me by email. Depending on the type of data you need, some resources may already be available and can potentially be shared upon request.
</p>
---


**FETA** (*French Eye-TrAcking Corpus*) is a French eye-tracking corpus designed to study reading behaviour across text types, text complexity, reader expertise, and text simplification.

The corpus contains word-level eye-tracking data collected from native French readers while they read texts from different domains and versions, including original and manually simplified texts.

---


The dataset includes:

- French texts from several domains;
- original and manually simplified text versions;
- eye-tracking measures collected during reading;
- word-level Areas of Interest (AOIs);
- participant metadata;
- information about text type and text version.

The data were collected using an eye-tracking experiment in which participants read texts presented screen by screen. Eye movements were recorded and exported at the word/AOI level.

---

## Corpus Overview

| Category | Description |
|---|---|
| Language | French |
| Data type | Eye-tracking reading data |
| Annotation level | Word-level AOI |
| Text domains | General, medical, clinical |
| Text versions | Original, simplified |
| Participant groups | General readers, speech and language therapy students |
| File format | TSV |
| Eye tracker | Tobii Pro Spectrum |
| Sampling rate | 600 Hz |

---

## Text Types

The corpus contains three main text domains:

| Text type | Description |
|---|---|
| `general` | General-domain texts |
| `medical` | Medical-domain texts |
| `clinical` | Clinical case texts |

Each text may appear in one of two versions:

| Version | Description |
|---|---|
| `original` | Original version of the text |
| `simplified` | Manually simplified version of the text |

The simplified versions were manually produced following plain-language and text simplification principles.

---

## Participant Groups

The corpus includes two participant groups:

| Group label | Description |
|---|---|
| `General` | Participants without medical or speech-language therapy training |
| `SpeechStudents` | Speech and language therapy students |

Participants were native French readers with normal or corrected-to-normal vision.

---

## Dataset Structure

The dataset is organized by experimental set and participant group.

Example structure:

FETA/
├── SET_1_A_general/
├── SET_1_A_orthophoniste/
├── SET_1_B_general/
├── SET_1_B_orthophoniste/
├── SET_2_A_general/
├── SET_2_A_orthophoniste/
├── SET_2_B_general/
└── SET_2_B_orthophoniste/


## Download

The FETA corpus is available as a compressed archive.

- [Download FETA Corpus v1.0](https://github.com/oksanaivchenko/feta-corpus/releases/download/v1.0/FETA_v1.0.zip)
- [Clinical case original sample TSV](sample_data/SET_2_B_general_participant8_clinical_original_226.tsv)

The archive contains the cleaned TSV files.

## Citation
@inproceedings{ivchenko-grabar-2026-feta,
  title = {Comparing Reading Behavior across Reader Expertise and Text Complexity: Insights from the French Eye-Tracking Corpus (FETA)},
  author = {Ivchenko, Oksana and Grabar, Natalia},
  booktitle = {Proceedings of the Fifteenth Language Resources and Evaluation Conference (LREC 2026)},
  pages = {6144--6154},
  publisher = {European Language Resources Association (ELRA)},
  year = {2026},
  doi = {10.63317/2xr5zj2u6h7p}
}
## Contact
For questions or access requests, please contact: - oksana.ivchenko.etu@univ-lille.fr
