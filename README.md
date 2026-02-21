# Stories Coffee — POS Sales & Profitability Analysis (2025 + Jan 2026)
**Executive Summary (PDF):** `reports/Stories Coffee executive summary.pdf`
## Business Problem
Stories Coffee wants to understand what drives **revenue and profit** across branches and product groups, and what actions can improve overall performance.

## Deliverables (what to read first)
- **Executive Summary (PDF, ≤ 2 pages):** `reports/Stories Coffee executive summary.pdf`
- **Main analysis notebook:** `notebooks/` (run the EDA notebooks)

## What’s in this repo
- `reports/` — executive summary + figures used in findings
- `notebooks/` — EDA and analysis notebooks
- `scripts/` — optional reproducible run scripts (if used)
- `src/` — helper functions (if used)
- `data/` — **not committed** (see `data/RAW_DATA_INSTRUCTIONS.txt`)

## Methodology (high level)
1. **Clean & standardize** POS exports (remove repeated headers/footers, fix types, normalize names).
2. **Build KPIs** (revenue, cost, profit, margin %, quantity/volume).
3. **Analyze drivers** by branch and product group (identify top contributors + low-margin areas).
4. **Visualize & summarize** results in `reports/figures/` and the executive summary PDF.

## Key findings & visuals
See the full findings and charts in:
- `reports/Stories Coffee executive summary.pdf`
- `reports/figures/`

## How to reproduce (local)
### 1) Setup environment
```bash
python -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt