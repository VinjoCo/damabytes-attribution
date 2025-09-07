# Damabytes Marketing Attribution Project

This repository contains an **anonymized dataset** and a **Jupyter Notebook** demonstrating different marketing attribution models using data science methods such as **Rule-Based Attribution, Markov Chains, and Shapley Values**.

---

## 📂 Repository Contents
- `anonymized_attribution.csv`  
  An anonymized multi-touch attribution dataset with the following columns:
  - `User_ID_Anon` → anonymized user IDs
  - `Timestamp` → interaction timestamp
  - `Step_Order` → step index in the user journey
  - `Channel` → marketing channel (Search Ads, Social Media, Referral, Display, Email, Direct)
  - `Conversion_Flag` → 1 if converted, 0 otherwise

- `damabytes_notebook.ipynb`  
  A Jupyter Notebook implementing:
  - Rule-based attribution (First, Last, Linear)
  - Markov chain attribution (removal effect method)
  - Shapley-value attribution (fair credit distribution)
  - Visualizations (bar charts, Sankey flows)

- `damabytes_attribution_project.zip`  
  Bundle containing the CSV, notebook, and visuals for convenience.

---

## 🚀 How to Use
1. Clone or download this repository:
   ```bash
   git clone https://github.com/<your-username>/<repo-name>.git
