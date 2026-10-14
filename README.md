# AI-Driven Prioritization System for Early Alzheimer's Diagnostic Pathways

> **Status:** 🟡 Initial Setup — Scaffolding in progress

---

## 📌 Project Overview

Alzheimer's disease (AD) is a progressive neurodegenerative disorder that affects millions of people worldwide. Early and accurate diagnosis is critical for slowing disease progression and improving patient outcomes. However, existing diagnostic pathways are often reactive, fragmented, and resource-intensive — leading to delayed referrals and missed early-intervention windows.

This project aims to develop an **AI-driven clinical decision-support system** that prioritizes patients along early Alzheimer's diagnostic pathways. By integrating multimodal clinical data (cognitive assessments, imaging biomarkers, genetic risk factors, and patient history), the system will generate risk-stratified prioritization scores to assist clinicians in identifying high-risk individuals earlier and more consistently.

---

## 🎯 Research Objectives

1. **Review and synthesize** existing literature on AI-based approaches to Alzheimer's detection and diagnostic pathway optimization.
2. **Identify clinically relevant biomarkers and features** from multimodal data sources (neuroimaging, cognitive tests, EHR data) that are predictive of early-stage AD.
3. **Design and evaluate ML models** (e.g., gradient boosting, graph neural networks, or transformer-based architectures) for patient risk stratification and pathway prioritization.
4. **Develop an interpretable scoring framework** that provides explainable outputs (SHAP, LIME) suitable for clinical adoption.
5. **Prototype a full-stack application** that exposes the prioritization system via a clinician-facing dashboard and a RESTful API.

---

## 🛠️ Planned Technology Stack

| Layer | Technology | Purpose |
|---|---|---|
| **Frontend** | React, TypeScript, Recharts / D3.js | Clinician dashboard, risk score visualization |
| **Backend** | Python, FastAPI | REST API, business logic, auth |
| **ML / AI** | scikit-learn, PyTorch, XGBoost, SHAP | Risk scoring models, explainability |
| **Data** | ADNI, OASIS datasets (local only), Pandas, NumPy | Feature engineering, preprocessing |
| **Database** | PostgreSQL (planned) | Patient records, audit logs |
| **Experiment Tracking** | MLflow (planned) | Model versioning and metrics |
| **Containerization** | Docker, Docker Compose (planned) | Reproducible environments |
| **Version Control** | Git + GitHub | Source control |

---

## 📂 Repository Structure

```
alzheimer-diagnostic-pathways/
├── frontend/          # React UI — clinician-facing dashboard (planned)
├── backend/           # FastAPI server — REST API and business logic (planned)
├── ml/                # ML models, training scripts, evaluation notebooks (planned)
├── research/          # Literature notes, paper summaries, research references
├── docs/              # Architecture diagrams, API specs, project reports
├── .gitignore         # Exclusions for Python, Node, datasets, model artifacts
├── .gitattributes     # Git line-ending normalization
└── README.md          # This file
```

---

## ⚠️ Data & Dataset Policy

- **Restricted or licensed datasets** (e.g., ADNI, OASIS) must **never** be committed to this repository.
- Place local datasets under `datasets/` (gitignored) or use a registered data registry (DVC / cloud storage).
- Small, non-sensitive reference files (e.g., scoring rubrics, lookup tables as CSV) may be committed if they contain no patient data.

---

## 🚀 Getting Started

> ⚙️ Setup instructions will be added once the application scaffolding is complete.

---

## 📄 License

To be determined. This project is currently in initial setup phase.

---

*This project is developed as an AI-driven research mini-project exploring clinical decision support for early Alzheimer's diagnostics.*
