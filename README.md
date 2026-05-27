# RFM Segmentation & Retention Framework (Capstone Part 2)

This repository contains the standalone code and strategic documentation for Part 2 of the customer churn capstone project. It leverages customer attributes, order histories up to the snapshot date, support ticket metrics, and web engagement profiles to build an actionable 7-segment behavioral engine.

## 🛠️ Data Leakage & Engineering Safeguards
To comply with data governance regulations, the data engine strictly enforces the **2025-09-30 Snapshot Cutoff**. All rows in `orders.csv` occurring after this date are automatically filtered out and excluded from feature extraction, ensuring zero data leakage from the target window.

## 📁 Repository Mapping
* `rfm_segmentation.ipynb`: Jupyter pipeline orchestrating data parsing, cleaning, feature math, and segmentation assignment.
* `segments.csv`: The final system-wide output featuring core customer tracking indexes.
* `retention_strategy.md`: Deep business strategy, ROI justifications, and budget matrix.
* `manual_review_cases.md`: Deep manual review breakdown of 10 edge cases.