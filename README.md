# Advertisement Click Prediction

An Industry Oriented Mini Project on **Advertisement Click-Through Rate (CTR) Prediction and Recommendation**.

## Overview

This project is designed to predict the probability that a user will click on a particular advertisement by analyzing user behavior, browsing history, click records, and advertisement-related information.

The project report describes a preprocessing and feature-extraction pipeline followed by a **DeepFM (Deep Factorization Machine)** model for CTR prediction. Based on predicted CTR values, users whose CTR is above a selected threshold can be identified as target users for advertisement recommendation.

## Objectives

- Analyze user behavior and advertisement interaction data.
- Preprocess raw data and extract useful features.
- Predict advertisement click-through rate (CTR).
- Identify users with higher predicted click probability.
- Support more relevant advertisement targeting and recommendation.
- Visualize and evaluate model performance.

## Main Modules

1. **Dataset Upload** – load the advertisement/user dataset.
2. **Data Preprocessing** – clean and prepare the input data.
3. **Feature Extraction** – transform relevant user and advertisement attributes into model-ready features.
4. **CTR Prediction** – predict click probability using the proposed model.
5. **Recommendation** – identify target users based on predicted CTR.
6. **Performance Evaluation & Visualization** – evaluate and visualize results.
7. **New Data Prediction** – generate CTR predictions for new input data.

## Technology Stack

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- Jupyter Notebook / VS Code / PyCharm
- Optional: MySQL / SQLite

## Suggested Repository Structure

```text
Advertisement-Click-Prediction/
├── README.md
├── requirements.txt
├── .gitignore
├── src/
│   └── <your-project-code>
├── notebooks/
│   └── <your-notebook>.ipynb
├── screenshots/
│   └── <add-project-screenshots-here>
└── docs/
    └── project-report.pdf
```

## Getting Started

### 1. Clone the repository

```bash
git clone <your-github-repository-url>
cd Advertisement-Click-Prediction
```

### 2. Create a virtual environment

```bash
python -m venv venv
```

Activate it on Windows:

```bash
venv\Scripts\activate
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

### 4. Run the project

Add the actual project entry-point command here after placing your source code in `src/`.

Example:

```bash
python src/main.py
```

> The exact run command should be updated to match the actual implementation on your laptop.

## Project Report

The original academic project report is included under:

`docs/project-report.pdf`

## Important Note

The supplied academic report contains some later sections whose implementation details do not consistently match the Advertisement Click Prediction / DeepFM description. Therefore, the repository README intentionally follows the project's stated title, abstract, proposed system, modules, and software requirements, while avoiding claims about source-code behavior that cannot be verified from the report.

## Authors

- CH. Vyshnavi
- K. Pranitha
- K. Vasavi

**Guide:** Mr. P. Krishna Reddy, Assistant Professor  
**Institution:** CMR Institute of Technology  
**Academic Year:** 2025–26
