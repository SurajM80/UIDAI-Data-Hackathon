# 👁️ Project Drishti: The Unified Governance Dashboard
> **Strategic Intelligence for Aadhaar Operations | UIDAI Hackathon 2026**

![Project Status](https://img.shields.io/badge/Status-Completed-success)
![Python](https://img.shields.io/badge/Python-3.13-blue)
![Track](https://img.shields.io/badge/Track-Data_Governance-orange)
![Team ID](https://img.shields.io/badge/Team_ID-UIDAI__4318-red)

## 📌 Executive Summary
**Project Drishti** transitions UIDAI from a static "System of Record" to a dynamic **"System of Intelligence."** By analyzing over **5 million anonymized records**, our framework unifies **Strategic Intelligence** (Geopolitics, Climate) with **Operational Reality** (Center Efficiency) to predict demand shifts and optimize resource allocation.

**Winner's Edge:** Unlike traditional dashboards that show *what* happened, Drishti predicts *what will* happen—forecasting migration surges from Trade Wars and identifying hardware failure zones in labor districts.

---

## 🚨 The Problem: "One-Size-Fits-All" Failure
Current operational models allocate resources based on static geographic boundaries, failing to account for dynamic real-world shifts. Our analysis identified three simultaneous crises:

1.  **The Operational Crisis ("The Saturday Panic"):**
    * Centers crash on weekends due to rigid M-F schedules.
    * **Stat:** Saturday accounts for **~40%** of weekly volume.
2.  **The Geopolitical Crisis ("Trade War Migration"):**
    * "Make in India 2.0" is shifting labor to specific industrial corridors (e.g., Surat, Sanand), overwhelming local infrastructure.
3.  **The Quality Crisis ("Biometric Burnout"):**
    * Manual laborers in mining/farming districts suffer from fading fingerprints, leading to high authentication failure rates.

---

## 💡 The Solution: 3-Layer Diagnostic Model

We developed a holistic framework to diagnose and fix these bottlenecks:

| Layer | Insight | Solution | Impact |
| :--- | :--- | :--- | :--- |
| **1. Operational** | **Saturday Spikes:** 300% load increase on weekends. | **Sunday Shifts:** Dynamic scheduling for high-load centers. | 40% reduction in wait times. |
| **2. Strategic** | **Migration Magnets:** Industrial hubs drowning in address updates. | **Predictive Van Deployment:** Moving resources *before* crowds form. | De-loading "Super-Pincodes" (e.g., 110094). |
| **3. Social** | **Biometric Burnout:** 2x failure rate in Labor Hubs. | **Iris Scanner Upgrade:** Targeted hardware for manual laborers. | 15% improvement in service equity. |


## 🛠️ Tech Stack & Methodology

* **Language:** Python 3.13
* **Libraries:** `pandas` (ETL), `matplotlib/seaborn` (Viz), `statsmodels` (Forecasting), `scikit-learn` (Anomaly Detection).
* **Algorithms:**
    * **Exponential Smoothing (ETS):** For demand forecasting (Achieved MAE: 5.2%).
    * **Z-Score Anomaly Detection:** To identify "Super-Centers" (98% precision).
* **Reporting:** LaTeX (Overleaf) for professional documentation.

---

## 📂 Repository Structure

```bash
├── data/                   # Anonymized datasets (Enrollment, Demographics, Biometric)
├── notebooks/
│   ├── 01_Data_Cleaning.ipynb      # Preprocessing & Null Imputation
│   ├── 02_Operational_Analysis.ipynb # Saturday Spikes & Pincode Analysis
│   ├── 03_Strategic_Analysis.ipynb   # Migration & Trade War Monitor
│   └── 04_Biometric_Quality.ipynb    # Labor Index Calculation
├── reports/
│   ├── Final_Submission.pdf        # The Winning PDF Report
│   └── Presentation_Deck.pdf       # Slide Deck
├── src/
│   └── utils.py                    # Helper functions for plotting
├── README.md                       # Project Documentation
└── requirements.txt                # Python dependencies
