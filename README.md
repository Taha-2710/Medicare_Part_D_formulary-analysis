# Medicare_Part_D_formulary-analysis
 📋 Formulary Policy & Restriction Tagging Project – Medicare Part D 2025  
**Clinical Policy Analysis · ST/PA Tagging · Market Access Insight**

## 📌 Project Objective

This project simulates a real-world policy analyst or healthcare data specialist’s role by analyzing the **2025 Medicare Part D drug formulary**. The primary focus is on identifying and tagging drug access restrictions like:

- **Step Therapy (ST)**
- **Prior Authorization (PA)**
- **Quantity Limits (QL)**

The project mimics responsibilities found in pharma market access, US healthcare, and commercial insurance workflows — capturing restrictions with high accuracy, applying documentation standards, and highlighting areas for value-add analysis.

## 🎯 Role-Aligned Responsibilities

✔️ Analyzed drug-level policy restrictions across 1.3M+ entries  
✔️ Identified **ST/PA/QL flags** and validated them by tier and plan  
✔️ Engineered a custom **Access Score** to quantify access friction  
✔️ Mapped clinical drug identifiers (`RXCUI`, `NDC`) to drug names  
✔️ Flagged records for multi-layered restrictions (e.g., PA + QL, or PA + ST)  
✔️ Ensured high accuracy in tagging, structure, and documentation  
✔️ Prepared output for export and verification across plans

## 📂 Dataset Overview

- `basic drugs formulary file 20250630.txt` – Primary dataset (pipe-separated)
- `RXNCONSO.RRF` – RxNorm concept mapping for drug names

**Total Records**: 1.3M+  
**Fields Tagged**:
- `FORMULARY_ID`, `TIER_LEVEL_VALUE`, `RXCUI`, `NDC`
- `PRIOR_AUTHORIZATION_YN`, `STEP_THERAPY_YN`, `QUANTITY_LIMIT_YN`

## 🧠 Key Insights

| Metric | Value |
|--------|-------|
| Drugs requiring PA | **27.22%** |
| Drugs with QL | **37.84%** |
| Drugs requiring ST | **1.11%** |
| Drugs with both PA + QL | **16.86%** |
| Most restricted drugs | Trikafta, Kisqali, Lenvima |
| Most restrictive tier | Tier 5 (specialty drugs) |

## ⚙️ Technical Tools Used

| Tool | Purpose |
|------|---------|
| **Python** | Data processing & analysis |
| **Pandas** | Tagging, grouping, merging |
| **Seaborn/Matplotlib** | Visualizing restriction patterns |
| **RxNorm (RXCUI)** | Drug name normalization |
| **Excel/CSV Exports** | Clean outputs for review or automation pipelines |

## 📊 Sample Visuals

- **Stacked bar charts** for top restricted drugs  
- **Tier-level distribution plots**  
- **Heatmap of ST/PA/QL per tier**  
- **Access score table by drug and formulary**


By following structured workflows, applying logical rules, and capturing ST/PA/QL flags accurately, it demonstrates readiness to work in **healthcare data operations, pharma access teams, or payer-focused analytics**.

## 📤 Outputs

- `cleaned_formulary_dataset.csv` – Filtered, mapped, restriction-tagged
- `Access_Score_by_Drug.csv` – Ranked drug access score
- `Plan_Restrictiveness_by_FORMULARY_ID.csv` – Average restriction score per plan

## 👨‍💼 Author

**Mohd Taha Ahmad**  
Data Analyst | Formulary & Policy Analysis Enthusiast  
🔍 Specializing in clinical restriction tagging and US healthcare data  
📫 [LinkedIn](https://www.linkedin.com/) • [GitHub](https://github.com/)
"""

