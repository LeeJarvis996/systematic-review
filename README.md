# Systematic Review of Foundation Models for the Electrocardiogram: Technical Design, Reproducibility, and Performance

The primary objective of this systematic review is to examine the current landscape of foundation models developed for ECG analysis by synthesizing the training strategies, model architectures, adaptation techniques, and evaluation methodologies.  As a secondary objective, we aim to assess the reproducibility of ECG foundation models and how well they perform on downstream tasks.


---

## 1. Data Sources

### (1) [Web of Science (WoS)](https://clarivate.com/academia-government/scientific-and-academic-research/research-discovery-and-referencing/web-of-science/web-of-science-core-collection/)

Based on [JCR classification: Q1, 2024](https://jcr.clarivate.com/jcr/browse-categories), journals are selected from the following categories:

#### Computer Science
- [COMPUTER SCIENCE, ARTIFICIAL INTELLIGENCE] (52 journals)
- [MATHEMATICAL & COMPUTATIONAL BIOLOGY] (16 journals)
- [MEDICAL INFORMATICS] (12 journals)
- [COMPUTER SCIENCE, INTERDISCIPLINARY APPLICATIONS] (46 journals)

#### Engineering
- [ENGINEERING, ELECTRICAL & ELECTRONIC] (92 journals)
- [ENGINEERING, BIOMEDICAL] (31 journals)
- [MEDICAL LABORATORY TECHNOLOGY] (8 journals)
- [ENGINEERING, MULTIDISCIPLINARY] (43 journals)


#### Clinical Medicine
- (Duplicated) ENGINEERING, BIOMEDICAL (31 journals)
- (Duplicated) MEDICAL INFORMATICS (12 journals)
- (Duplicated) MEDICAL LABORATORY TECHNOLOGY (8 journals)
- [CARDIAC & CARDIOVASCULAR SYSTEMS] (59 journals)

#### Multidisciplinary
- [COMPUTER SCIENCE, INFORMATION SYSTEMS] (64 journals)
- (Duplicated) COMPUTER SCIENCE, INTERDISCIPLINARY APPLICATIONS
- (Duplicated) ENGINEERING, MULTIDISCIPLINARY (43 journals)
- [MULTIDISCIPLINARY SCIENCES] (33 journals)
- [SOCIAL SCIENCES, BIOMEDICAL] (12 journals)

---

### (2) [DBLP](https://dblp.org/)

Since CORE conference portal is supported by and linked to DBLP, we include only top-tier conferences rated A* by [CORE 2023](https://portal.core.edu.au/conf-ranks/?search=&by=all&source=CORE2023&sort=arank&page=1) (60 conferences), including:

> AAAI, AAMAS, ACL, ACMMM, ASE, ASPLOS, CAV, CCS, CHI, COLT, CRYPTO, CVPR, EC, ECCV, EMNLP, EuroCrypt, FOCS, FSE, HPCA, ICAPS, ICCV, ICDE, ICDM, ICLR, ICML, ICRA, ICSE, IJCAI, INFOCOM, IPSN, ISCA, ISMAR, KDD, KR, LICS, MOBICOM, NDSS, NeurIPS, OSDI, PERCOM, PLDI, PODC, PODS, POPL, RTSS, SENSYS, SIGCOMM, SIGGRAPH, SIGIR, SIGMETRICS, SIGMOD, SODA, SOSP, SP, STOC, UIST, USENIX-Security, VLDB, VR, WWW
---

### (3) [PubMed](https://pubmed.ncbi.nlm.nih.gov/advanced/)

We did not impose venue-based quality constraints for studies retrieved from PubMed, but instead manually reviewed their titles, abstracts, and full texts to ensure they satisfied all other eligibility criteria.

---

### (4) [Huggingface](https://huggingface.co/models?sort=trending&search=ECG)

To ensure the inclusion of timely developments in the field, we additionally identified studies by searching pretrained models released in two widely used model repositories: Hugging Face and Zenodo.

### (5) [Zenodo](https://zenodo.org/)


---


## 2. Search Query

#### WoS (682 papers): [Query and results](https://github.com/LeeJarvis996/awesome-ai-ecg/blob/main/query/journal_query.md)

#### DBLP (40 papers): [Query and results](https://github.com/LeeJarvis996/awesome-ai-ecg/blob/main/query/ai_conference_query.md)

#### PubMed (821 papers): [Query and results](https://github.com/LeeJarvis996/systematic-review-ecg-foundation-model/blob/main/query/pubmed_query.md)

#### Huggingface: Search for "ECG" models on huggingface's model. Results on 114 Models (2025-07-13).

#### Zenodo: Our query is 
>metadata.title:(pretrained AND (ECG OR electrocardiogram)) AND metadata.publication_date:[2018 TO 2025]. Results on 9 Models (2025-07-15).
---




