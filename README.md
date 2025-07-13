# Systematic Review on ECG & Foundation Models in AI and Bio/Medical Research

This project systematically investigates publications from **top-tier AI conferences** and **Q1 journals** in the intersection of artificial intelligence and biomedical signal analysis (especially ECG), focusing on **pretrained models, representation learning**, and **few/zero-shot paradigms** from **2018–2025**.

---

## 📚 Target Sources

### 🔬 AI & Bio/Medical Journals (JCR Q1, 2024)

Based on JCR classification, journals are selected from the following **Q1 categories**:

#### 🧠 Computer Science
- [COMPUTER SCIENCE, ARTIFICIAL INTELLIGENCE](https://github.com/LeeJarvis996/awesome-ai-ecg/blob/main/JCR/COMPUTER%20SCIENCE%2C%20ARTIFICIAL%20INTELLIGENCE.csv) (52 journals)
- [MATHEMATICAL & COMPUTATIONAL BIOLOGY](https://github.com/LeeJarvis996/awesome-ai-ecg/blob/main/JCR/MATHEMATICAL%20%26%20COMPUTATIONAL%20BIOLOGY.csv) (16 journals)
- [MEDICAL INFORMATICS](https://github.com/LeeJarvis996/awesome-ai-ecg/blob/main/JCR/MEDICAL%20INFORMATICS.csv) (12 journals)
- [COMPUTER SCIENCE, INTERDISCIPLINARY APPLICATIONS](https://github.com/LeeJarvis996/awesome-ai-ecg/blob/main/JCR/COMPUTER%20SCIENCE%2C%20INTERDISCIPLINARY%20APPLICATIONS.csv) (46 journals)

#### ⚙️ Engineering
- [ENGINEERING, ELECTRICAL & ELECTRONIC](https://github.com/LeeJarvis996/awesome-ai-ecg/blob/main/JCR/ENGINEERING%2C%20ELECTRICAL%20%26%20ELECTRONIC.csv) (92 journals)
- [ENGINEERING, BIOMEDICAL](https://github.com/LeeJarvis996/awesome-ai-ecg/blob/main/JCR/ENGINEERING%2C%20BIOMEDICAL.csv) (31 journals)
- [MEDICAL LABORATORY TECHNOLOGY](https://github.com/LeeJarvis996/awesome-ai-ecg/blob/main/JCR/MEDICAL%20LABORATORY%20TECHNOLOGY.csv) (8 journals)

#### 🧬 Biology & Biochemistry
- [BIOTECHNOLOGY & APPLIED MICROBIOLOGY](https://github.com/LeeJarvis996/awesome-ai-ecg/blob/main/JCR/BIOTECHNOLOGY%20%26%20APPLIED%20MICROBIOLOGY.csv) (44 journals)
- (Duplicated) MATHEMATICAL & COMPUTATIONAL BIOLOGY (16 journals)


#### 🏥 Clinical Medicine
- (Duplicated) ENGINEERING, BIOMEDICAL (31 journals)
- (Duplicated) MEDICAL INFORMATICS (12 journals)
- (Duplicated) MEDICAL LABORATORY TECHNOLOGY (8 journals)

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
