# Assignment 1

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

### 4. Open the assignment notebook
Open `notebooks/assignment1.ipynb` in Jupyter, VS Code, or Cursor and run all cells top to bottom (Kernel → Restart & Run All).

### 5. Environment variables
Copy `.env.example` to `.env` and fill in real values (none are required for this assignment).
```bash
cp .env.example .env
```

## Project structure
- `notebooks/` — assignment notebooks
- `src/` — reusable Python modules
- `data/raw/`, `data/processed/` — data storage (contents gitignored, folders tracked via `.gitkeep`)
- `reports/` — chart output and reflection
