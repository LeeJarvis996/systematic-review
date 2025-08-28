# Systematic Review on ECG & Foundation Models in AI and Bio/Medical Research

This project systematically investigates publications from **top-tier AI conferences** and **Q1 journals** in the intersection of artificial intelligence and biomedical signal analysis (especially ECG), focusing on **pretrained models, representation learning**, and **few/zero-shot paradigms** from **2018–2025**.

---

## Data Sources

### 1. [Web of Science (WoS)](https://clarivate.com/academia-government/scientific-and-academic-research/research-discovery-and-referencing/web-of-science/web-of-science-core-collection/)

Based on [JCR classification: Q1, 2024](https://jcr.clarivate.com/jcr/browse-categories), journals are selected from the following categories:

#### Computer Science
- [COMPUTER SCIENCE, ARTIFICIAL INTELLIGENCE](https://github.com/LeeJarvis996/awesome-ai-ecg/blob/main/JCR/COMPUTER%20SCIENCE%2C%20ARTIFICIAL%20INTELLIGENCE.csv) (52 journals)
- [MATHEMATICAL & COMPUTATIONAL BIOLOGY](https://github.com/LeeJarvis996/awesome-ai-ecg/blob/main/JCR/MATHEMATICAL%20%26%20COMPUTATIONAL%20BIOLOGY.csv) (16 journals)
- [MEDICAL INFORMATICS](https://github.com/LeeJarvis996/awesome-ai-ecg/blob/main/JCR/MEDICAL%20INFORMATICS.csv) (12 journals)
- [COMPUTER SCIENCE, INTERDISCIPLINARY APPLICATIONS](https://github.com/LeeJarvis996/awesome-ai-ecg/blob/main/JCR/COMPUTER%20SCIENCE%2C%20INTERDISCIPLINARY%20APPLICATIONS.csv) (46 journals)

#### Engineering
- [ENGINEERING, ELECTRICAL & ELECTRONIC](https://github.com/LeeJarvis996/awesome-ai-ecg/blob/main/JCR/ENGINEERING%2C%20ELECTRICAL%20%26%20ELECTRONIC.csv) (92 journals)
- [ENGINEERING, BIOMEDICAL](https://github.com/LeeJarvis996/awesome-ai-ecg/blob/main/JCR/ENGINEERING%2C%20BIOMEDICAL.csv) (31 journals)
- [MEDICAL LABORATORY TECHNOLOGY](https://github.com/LeeJarvis996/awesome-ai-ecg/blob/main/JCR/MEDICAL%20LABORATORY%20TECHNOLOGY.csv) (8 journals)
- [ENGINEERING, MULTIDISCIPLINARY](https://github.com/LeeJarvis996/awesome-ai-ecg/blob/main/JCR/ENGINEERING%2C%20MULTIDISCIPLINARY.csv) (43 journals)


#### Clinical Medicine
- (Duplicated) ENGINEERING, BIOMEDICAL (31 journals)
- (Duplicated) MEDICAL INFORMATICS (12 journals)
- (Duplicated) MEDICAL LABORATORY TECHNOLOGY (8 journals)
- [CARDIAC & CARDIOVASCULAR SYSTEMS](https://github.com/LeeJarvis996/awesome-ai-ecg/blob/main/JCR/CARDIAC%20%26%20CARDIOVASCULAR%20SYSTEMS.csv) (59 journals)

#### Multidisciplinary
- [COMPUTER SCIENCE, INFORMATION SYSTEMS](https://github.com/LeeJarvis996/awesome-ai-ecg/blob/main/JCR/COMPUTER%20SCIENCE%2C%20INFORMATION%20SYSTEMS.csv) (64 journals)
- (Duplicated) COMPUTER SCIENCE, INTERDISCIPLINARY APPLICATIONS
- (Duplicated) ENGINEERING, MULTIDISCIPLINARY (43 journals)
- [MULTIDISCIPLINARY SCIENCES](https://github.com/LeeJarvis996/awesome-ai-ecg/blob/main/JCR/MULTIDISCIPLINARY%20SCIENCES.csv) (33 journals)
- [SOCIAL SCIENCES, BIOMEDICAL](https://github.com/LeeJarvis996/awesome-ai-ecg/blob/main/JCR/SOCIAL%20SCIENCES%2C%20BIOMEDICAL.csv) (12 journals)

---

### 2. [DBLP](https://dblp.org/)

Since CORE conference portal is supported by and linked to DBLP, we include only top-tier conferences rated A* by [CORE 2023](https://portal.core.edu.au/conf-ranks/?search=&by=all&source=CORE2023&sort=arank&page=1) (60 conferences), including:

> AAAI, AAMAS, ACL, ACMMM, ASE, ASPLOS, CAV, CCS, CHI, COLT, CRYPTO, CVPR, EC, ECCV, EMNLP, EuroCrypt, FOCS, FSE, HPCA, ICAPS, ICCV, ICDE, ICDM, ICLR, ICML, ICRA, ICSE, IJCAI, INFOCOM, IPSN, ISCA, ISMAR, KDD, KR, LICS, MOBICOM, NDSS, NeurIPS, OSDI, PERCOM, PLDI, PODC, PODS, POPL, RTSS, SENSYS, SIGCOMM, SIGGRAPH, SIGIR, SIGMETRICS, SIGMOD, SODA, SOSP, SP, STOC, UIST, USENIX-Security, VLDB, VR, WWW
---

### 3. [PubMed](https://pubmed.ncbi.nlm.nih.gov/advanced/)

We did not impose venue-based quality constraints for studies retrieved from PubMed, but instead manually reviewed their titles, abstracts, and full texts to ensure they satisfied all other eligibility criteria.

---

## Search Query

#### WoS: [Query and results](https://github.com/LeeJarvis996/awesome-ai-ecg/blob/main/query/journal_query.md)

#### DBLP: [Query and results](https://github.com/LeeJarvis996/awesome-ai-ecg/blob/main/query/ai_conference_query.md)

### PubMed: [Query and results] (https://github.com/LeeJarvis996/systematic-review-ecg-foundation-model/blob/main/query/pubmed_query.md)

---

## Huggingface

Search for "ECG" models on [huggingface's model](https://huggingface.co/models?sort=trending&search=ECG). Results on 114 Models (2025-07-13).


##Zenodo

On [Zenodol](https://zenodo.org/), our query is 

>metadata.title:(pretrained AND (ECG OR electrocardiogram)) AND metadata.publication_date:[2018 TO 2025]

Results on 9 Models (2025-07-15).



