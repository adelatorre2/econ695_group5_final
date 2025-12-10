cat > README.md << 'EOF'
# ECON 695 Final Project – Group 5

This repository contains the code and report for our ECON 695 final project.

## Structure

- `data/` – input data (original CSV from Alice + any derived data).
- `code/` – Jupyter notebooks and Python helper scripts.
- `report/` – LaTeX source, figures, and compiled PDF.
- `env/` – environment/requirements files for reproducibility.

## Workflow

1. Do analysis in `code/` (new notebook per major task).
2. Export cleaned figures/tables to `report/figures/`.
3. Write the paper in `report/main.tex` (or `econ695_group5_final.tex`),
   referencing figures from `report/figures/`.
4. Commit and push frequently, using branches for new features/sections.
EOF