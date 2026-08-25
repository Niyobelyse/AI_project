# AI Project

Coursework repository for Assignment 1 (Python for AI Warm-Up) and Assignment 2 (Data Wrangling and Exploratory Analysis).

## Setup

### 1. Create and activate the virtual environment
This project's environment folder is named ai_projects.

```bash
python3 -m venv ai_projects
source ai_projects/bin/activate
```

### 2. Install dependencies
```bash
pip install -r requirements.txt
```

### 3. Run the smoke test
```bash
jupyter notebook notebooks/assignment1.ipynb
```
Run the first cell — it should print `all good`.

### 4. Open the assignment notebooks
Open `notebooks/assignment1.ipynb` or `notebooks/assignment2.ipynb` in Jupyter, VS Code, or Cursor and run all cells top to bottom (Kernel → Restart & Run All).

### 5. Environment variables
Copy `.env.example` to `.env` and fill in real values (none are required for this assignment).
```bash
cp .env.example .env
```

## Datasets

**Assignment 2 — UCI Heart Disease Data** (`data/raw/heart_disease_uci.csv`)
- Source: https://www.kaggle.com/datasets/redwankarimsony/heart-disease-data — a Kaggle republication of the UCI ML Repository's Heart Disease dataset (Cleveland, Hungary, Switzerland, and VA Long Beach cohorts).
- License: "Data files © Original Authors" — used with attribution, not redistributed as original work.
- 920 rows, mix of numeric (age, cholesterol, blood pressure, max heart rate) and categorical (sex, chest pain type, site) columns.

## Project structure
- `notebooks/` — assignment notebooks
- `src/` — reusable Python modules
- `data/raw/`, `data/processed/` — data storage (contents gitignored, folders tracked via `.gitkeep`)
- `reports/` — chart output, reports, and reflections
