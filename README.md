# Explainable Trust-Aware VANET Routing

## Title

**An Explainable Trust-Aware Secure Routing Framework for VANETs Using XGBoost-Based Intrusion Detection and ABC Optimization**

## Overview

This repository presents an explainable trust-aware secure routing framework for Vehicular Ad Hoc Networks (VANETs) by integrating XGBoost-based intrusion detection, SHAP explainability, dynamic trust generation, and Artificial Bee Colony (ABC) optimization. The framework identifies malicious communication behavior, generates interpretable trust scores, and selects secure communication routes in dynamic wireless environments.

---

## Dataset

### CICIoT2023

* Total Samples: 5,491,971
* Total Features: 47
* Attack Samples: 5,362,433
* Benign Samples: 129,538
* Attack Classes: 33

Dataset Source:

https://www.kaggle.com/datasets/himadri07/ciciot2023

---

## Repository Structure

```text
.
├── trust_aware_vanet_framework.py
├── trust_aware_vanet_framework.ipynb
├── README.md
└── requirements.txt
```

---

## Methodology

The proposed framework consists of the following stages:

1. Data Preprocessing and Balancing
2. XGBoost-Based Intrusion Detection
3. SHAP Explainability Analysis
4. Dynamic Trust Score Generation
5. Graph-Based VANET Routing
6. Artificial Bee Colony (ABC) Optimization
7. Routing Performance Evaluation

### Framework Workflow

```text
CICIoT2023 Dataset
        │
        ▼
Data Preprocessing
        │
        ▼
XGBoost Intrusion Detection
        │
        ▼
SHAP Explainability
        │
        ▼
Trust Score Generation
        │
        ▼
Trust-Aware VANET Routing
        │
        ▼
ABC Optimization
        │
        ▼
Optimal Secure Route Selection
```

---

## Experimental Results

### Intrusion Detection Performance

| Metric    | Value  |
| --------- | ------ |
| Accuracy  | 99.70% |
| Precision | 99.93% |
| Recall    | 99.48% |
| F1-Score  | 99.70% |
| ROC-AUC   | 99.97% |

### Cross-Validation

| Metric             | Value   |
| ------------------ | ------- |
| Mean Accuracy      | 99.68%  |
| Standard Deviation | 0.0268% |

### Best Secure Route

```text
Route:
[8, 30, 23, 46, 41]
```

| Metric                | Value  |
| --------------------- | ------ |
| Trust Score           | 0.84   |
| Packet Delivery Ratio | 0.381  |
| Packet Loss           | 0.619  |
| Throughput            | 389.12 |
| Delay                 | 4.76   |

---

## Installation

Create a Python environment and install dependencies:

```bash
pip install -r requirements.txt
```

---

## Usage

### Python Script

```bash
python trust_aware_vanet_framework.py
```

### Jupyter Notebook

```text
trust_aware_vanet_framework.ipynb
```

Run all cells sequentially.

---

## Generated Outputs

The implementation generates:

* Confusion Matrix
* ROC Curve
* Precision–Recall Curve
* SHAP Summary Plot
* SHAP Feature Importance Plot
* PDR Comparison
* Throughput Comparison
* Delay Comparison
* Routing Performance Radar Chart

---

## Reproducibility

All experiments can be reproduced using the provided Python script or Jupyter notebook. The implementation includes:

* Dataset preprocessing
* Class balancing
* XGBoost model training
* SHAP explainability analysis
* Trust score computation
* Graph-based VANET routing
* ABC route optimization
* Routing performance evaluation

---

## Code Availability

The complete implementation used in this study is publicly available in this repository to support reproducibility and future research.

---

## Data Availability

The CICIoT2023 dataset is publicly available from the official Kaggle repository. Data preprocessing and experimental workflows are provided within the source code.

---

## Citation

If you use this repository, please cite:

**An Explainable Trust-Aware Secure Routing Framework for VANETs Using XGBoost-Based Intrusion Detection and ABC Optimization**

---

## Disclaimer

This repository implements a graph-based VANET routing framework using NetworkX and machine learning-driven trust evaluation. The reported results are based on CICIoT2023 traffic data and software-based routing simulations.
