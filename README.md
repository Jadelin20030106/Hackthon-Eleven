# Hackathon - Eleven

## Project Overview

This project implements a two-stage recommendation system (Recall → Rerank) designed to improve Top-K ranking quality.

The pipeline combines multi-source candidate generation, feature engineering, and supervised reranking (LGBM / XGBoost) to enhance personalization under realistic exposure constraints.

Original datasets are not included due to confidentiality.

---

## Repository Structure

- `Hackthon_Eleven_Group10.ipynb`  
  Main notebook containing recall, feature engineering, model training, and evaluation pipeline.

- `Dashboard/`  
  Power BI dashboard for performance visualization and KPI analysis.

- `demo/`  
  Simple interface to simulate web-side recommendation display and visualize user-level Top-K results.

- `requirements.txt`  
  Python dependencies for reproducing the environment.

- `README.md`  
  Project description.
