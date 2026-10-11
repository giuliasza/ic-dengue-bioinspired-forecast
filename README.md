# Bioinspired Hybrid Model for Dengue Outbreak Forecasting 🦟 🧬

![Python Version](https://img.shields.io/badge/python-3.10%2B-blue)
![License](https://img.shields.io/badge/license-MIT-green)
![Status](https://img.shields.io/badge/status-In%20Development-orange)

## 📌 Overview
This repository contains the source code and methodology for an Undergraduate Research Project (Iniciação Científica) developed at UNINASSAU (Recife, Brazil). 

The project proposes a **bio-inspired hybrid computational model** to predict dengue fever outbreaks in the Recife Metropolitan Region (RMR). It addresses the limitations of traditional epidemiological models by integrating:
1. **Climate Data:** Temperature, humidity, and precipitation (INMET).
2. **Epidemiological Data:** Notified dengue cases and historical outbreaks (SINAN/DataSUS).
3. **Genomic Surveillance:** Viral metadata, circulating serotypes (DENV 1-4), and sequence variability extracted via Biopython (NCBI Virus).

## 🧠 Methodology
To handle high dimensionality and temporal lags, the pipeline utilizes **Bioinspired Computational Intelligence** (e.g., Binary Particle Swarm Optimization - BPSO / Genetic Algorithms) for automated **Feature Selection**. The optimized feature subset is then fed into advanced Machine Learning classifiers (XGBoost, Random Forest, LSTM) to output early-warning outbreak predictions.

## 📂 Repository Structure
```text
ic-dengue-bioinspired-forecast/
│
├── data/               # Ignored by git. Raw and processed datasets (CSV, Parquet, FASTA)
├── docs/               # Scientific literature, diagrams, and IC project PDFs
├── notebooks/          # Jupyter notebooks for EDA, Biopython extraction, and prototyping
├── src/                # Python source code (scripts for API requests, PSO, and ML models)
├── .gitignore          # Prevents heavy data and credentials from being uploaded
├── requirements.txt    # Python dependencies (Pandas, Scikit-learn, Biopython, PySwarms)
└── README.md           # Project documentation
