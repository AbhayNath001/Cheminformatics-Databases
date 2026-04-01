# MMP-12 Inhibitor Dataset v1.0.0

## 📌 Overview

This repository provides a curated dataset of small-molecule inhibitors targeting **Matrix metalloproteinase-12 (MMP-12)**. The dataset is intended for cheminformatics, QSAR modeling, machine learning, and drug discovery research.

---

## 📊 Dataset Description

For the present study, a total of **500 compounds** with reported inhibitory activity (IC50) against MMP-12 were retrieved from the ChEMBL database.

### 🔍 Data Curation

The dataset was carefully curated using the following criteria:

* Removal of duplicate entries
* Exclusion of stereoisomers
* Removal of salts
* Exclusion of compounds with IC50 values reported as ranges (e.g., “>”, “<”, “≤”, “≥”)
* Removal of entries lacking valid SMILES notation

After preprocessing, the dataset was reduced to **481 unique compounds**.

---

## 🧪 Data Format

* File format: **SDF (Structure Data File)**
* Number of compounds: **481**
* Each entry contains:

  * Molecular structure (SMILES / 2D structure)
  * Experimental activity values (IC50 / pIC50)

The curated dataset was converted into a **single SDF file**, which can be directly used for:

* Molecular fingerprint generation
* QSAR modeling
* Machine learning applications

---

## 📁 Repository Structure

```
├── MMP_12_dataset.sdf
├── README.md
```

---

## 📌 Citation Requirement

If you use this dataset in your research, you **MUST** cite it:

Follow the citation: https://github.com/AbhayNath001/Cheminformatics-Databases/blob/main/README.md

---

## ⚖️ License

This dataset is licensed under the **Creative Commons Attribution 4.0 International (CC BY 4.0)** license.

You are free to use, modify, and distribute the data for any purpose, provided that proper attribution is given.

---

## ⚠️ Disclaimer

This dataset is provided “as is” without warranty of any kind. The authors are not responsible for any misuse or misinterpretation of the data.

---

## 📬 Contact

<table>
<tr>
<td width="65%">

### 👤 Research Profile

**Name:** Abhay Nath
**Affiliation:** AI-ML Research Scientist

**📧 Email:** [dr.abhaynath001@gmail.com](mailto:dr.abhaynath001@gmail.com)
**🔗 GitHub:** https://github.com/AbhayNath001
**🎓 LinkedIn:** https://www.linkedin.com/in/abhaynath001/ 

**🧪 Research Areas:**

* Artificial Intelligence
* Machine Learning
* Deep Learning
* Computer Vision
* Generative AI
* MedTech

</td>

<td width="35%" align="center">

<img src="https://raw.githubusercontent.com/AbhayNath001/AbhayNath001/main/Passport%20Size%20Image%20(1).jpg" width="160" style="border:2px solid #e0e0e0; border-radius:12px; padding:6px;" />

<br><br>

<i>Abhay Nath | Kolkata, West Bengal, India</i>

</td>
</tr>
</table>

---
