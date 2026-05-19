# Repository Structure

This repository is organized to support scalable analytics engineering and data analysis projects.

## Top-Level Structure

| Folder | Purpose |
|---|---|
| projects/ | Individual analytics and data engineering projects |
| shared/ | Reusable utilities, helper functions, and templates |
| datasets/ | Shared datasets and reference data |

---

# Project Template Structure

Each project follows a consistent structure:

```text
example_project/
├── data/
│   ├── raw/
│   └── processed/
├── notebooks/
├── sql/
│   ├── staging/
│   ├── marts/
│   └── analysis/
├── scripts/
├── outputs/
├── docs/
├── tests/
└── README.md
```

## Folder Descriptions

### data/raw
Original source data files.

### data/processed
Cleaned or transformed datasets.

### notebooks
Jupyter notebooks for exploration and analysis.

### sql/staging
Initial SQL transformations and staging models.

### sql/marts
Business-facing analytical models and reporting layers.

### sql/analysis
Ad hoc analysis queries.

### scripts
Python scripts for ingestion, cleaning, and transformation.

### outputs
Charts, exports, and generated analytical assets.

### docs
Project-specific documentation.

### tests
Validation scripts and testing logic.

---

# Portfolio Goals

This repository is designed to support:

- SQL analytics projects
- Python data analysis
- DBT-style modelling
- notebook-based exploration
- reusable analytical workflows
- portfolio-ready project organization