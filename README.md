# Systematic Review on ECG & Foundation Models in AI and Bio/Medical Research

This project systematically investigates publications from **top-tier AI conferences** and **Q1 journals** in the intersection of artificial intelligence and biomedical signal analysis (especially ECG), focusing on **pretrained models, representation learning**, and **few/zero-shot paradigms** from **2018–2025**.

---

## 📚 Target Sources

### 🔬 AI & Bio/Medical Journals (JCR Q1, 2024)

Based on JCR classification, journals are selected from the following **Q1 categories**:

#### 🧠 Computer Science
- [COMPUTER SCIENCE, ARTIFICIAL INTELLIGENCE](./JCR/COMPUTER SCIENCE, ARTIFICIAL INTELLIGENCE.csv) (52 journals)
- [MATHEMATICAL & COMPUTATIONAL BIOLOGY](./JCR/MATHEMATICAL & COMPUTATIONAL BIOLOGY.csv) (16 journals)
- [MEDICAL INFORMATICS](./JCR/MEDICAL INFORMATICS.csv) (12 journals)
- [COMPUTER SCIENCE, INTERDISCIPLINARY APPLICATIONS](./JCR/COMPUTER SCIENCE, INTERDISCIPLINARY APPLICATIONS.csv) (46 journals)

#### ⚙️ Engineering
- ENGINEERING, ELECTRICAL & ELECTRONIC (92 journals)
- ENGINEERING, BIOMEDICAL (31 journals)
- MEDICAL LABORATORY TECHNOLOGY (8 journals)

#### 🧬 Biology & Biochemistry
- MATHEMATICAL & COMPUTATIONAL BIOLOGY (16 journals)
- BIOTECHNOLOGY & APPLIED MICROBIOLOGY (44 journals)

#### 🏥 Clinical Medicine
- ENGINEERING, BIOMEDICAL (31 journals)
- MEDICAL INFORMATICS (12 journals)
- MEDICAL LABORATORY TECHNOLOGY (8 journals)

---

### 🧠 CORE A* AI Conferences

We also include top-tier conferences rated A* by [CORE 2023](https://portal.core.edu.au/conf-ranks/?search=&by=all&source=CORE2023&sort=arank&page=1) (60 conferences), including:

> AAAI, NeurIPS, ICML, CVPR, ICCV, ACL, EMNLP, ICLR, IJCAI, ECCV, KDD, WWW, etc.

---

## 🔍 Search Query Design

### 📅 Time Range
`2018–2025`

### 📌 Keywords
We search for titles containing the following:

- **Target signal terms:** `ECG`, `electrocardiogram`
- **Target modeling terms:** `pretrain`, `pre-train`, `foundation-model`, `zero-shot`, `few-shot`, `representation`

### 💡 Sample Search Query (Pseudo-code)

```python
title: ("ECG" OR "electrocardiogram")
AND
title: ("pretrain" OR "pre-train" OR "foundation-model" OR "zero-shot" OR "few-shot" OR "representation")
AND
year: 2018 TO 2025
AND
venue: [
    AAAI, NeurIPS, ICML, ICLR, CVPR, ICCV, ACL, EMNLP, IJCAI, ...
]  # 60 CORE A* venues
