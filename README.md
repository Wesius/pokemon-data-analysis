# Pokémon Data Analysis

EDA and visual storytelling on the [Data of 1,025 Pokémon](https://www.kaggle.com/) Kaggle dataset — culminating in a written paper and class presentation.

Part of my Advanced Machine Learning class portfolio (Ransom Everglades, 2025–26).

## What I explored

- **Type strength** — which types have the highest mean total stats? Offensive vs. defensive centroids.
- **Power creep** — has stat inflation occurred across generations? (violin + mean+CI plots)
- **Egg steps vs. base stats** — does it take more steps to hatch a stronger Pokémon? Per-stat correlations + heatmaps.
- **Body size** — height/weight vs. stat lines, including PCA.
- **Legendary classification** — quick logistic-regression and random-forest classifiers for Legendary status, with confusion matrices.
- **Dream team** — engineered "role" tags (sweeper, wall, mixed, etc.) and built a radar-chart "best of class" team.

## Deliverables

- `paper/main.pdf` — written report (LaTeX source: `main.tex`)
- `pres/presentation.pdf` — class presentation (LaTeX source: `presentation.tex`)
- `main.ipynb` — full analysis notebook
- `output/` — all generated figures and the engineered CSV (`pokemon_engineered.csv`, `dream_team.csv`)
- `INSTRUCTIONS.md` — original assignment prompt

## How to reproduce

1. Download the Pokémon dataset from Kaggle to the project root as `pokemon.csv`.
2. `uv sync`
3. Run `main.ipynb` end-to-end (Jupyter or VS Code).

The notebook regenerates everything in `output/`.
