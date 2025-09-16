# Core Instructions

Objective: explore the Pokémon dataset (Kaggle: Data of 1,025 Pokémons) and produce a creative, evidence-based PDF report supported by high-quality visualizations. Focus on data cleaning, descriptive statistics, feature engineering, and visual storytelling.


Dataset
Required dataset: Data of 1,025 Pokémons (Kaggle) (latest update includes 1,025 Pokémon).
External datasets: Optional. You may enhance your analysis with related data (e.g., type effectiveness, movesets, evolution chains).
If you use external data, include a Data Card in your PDF with:
Source
URL/citation
License
Access date
Key columns and limitations

Deliverables:
Google Colab notebook (clean, runnable, documented).
Final PDF report (well-structured, polished, and readable).

File naming:
ML_Pokemon_<Period>_<TeamName>_<Last1-Last2>.ipynb
ML_Pokemon_<Period>_<TeamName>_<Last1-Last2>.pdf

Required Notebook Sections

1. Setup & Data Hygiene (10 pts)
Import required packages.
Load the Pokémon dataset.
Handle missing/duplicate values.
Standardize column names if necessary
2. Exploratory Data Analysis (30 pts)
Summary statistics of HP, Attack, Defense, Sp. Atk, Sp. Def, Speed, Total.
Pokémon counts by generation and type (primary/secondary).
Correlation heatmap of numerical stats.
Comparisons: Legendary vs Non-Legendary Pokémon.
3. Feature Engineering (10 pts): Create ≥2 new features from the dataset. Example ideas:
Offensive Index: (Attack + Sp. Atk) / 2
Defensive Index: (Defense + Sp. Def) / 2
Speed-to-Power Ratio: Speed / Total
Era Index: Stats normalized within each generation
If external datasets are used, you can also engineer features from them.
4. Visual Analytics (30 pts): Produce at least 5 high-quality, labeled visuals with annotations. Example ideas:
Type frequency bar chart or treemap
Stat comparisons across generations (box/violin plots)
Radar charts for selected Pokémon comparisons
Scatterplots with meaningful annotations (e.g., Attack vs. Speed)
Distribution plots (e.g., histograms of Total stats per generation)
5. Reflection & Report (15 pts)
Your PDF report must include:
A clear research question (self-chosen).
Main findings supported by visuals.
At least one anomaly/outlier, and your hypothesis about it.
Limitations and future directions.
Creativity Options (pick ≥1): expand your creativity and explore other opportunities
Counterfactuals: What if Pokémon types were rebalanced?
Detecting power creep (stat inflation across generations).
Creating simple playstyle tags (sweeper, wall, balanced) based on thresholds.
Designing a “balanced trio” using only stats and types.
PDF Report Requirements
Title page with project title, authors (Wes Griffin, Isa Wesolowski), and period (3).
Executive summary (≤150 words).
Methods (datasets, cleaning, features).
Findings (visuals + narrative).
Limitations + future work.
References (and Data Card if external datasets used).
The PDF should read like a research paper, not just a collection of notebook screenshots.


Rubric (100 pts)
Data hygiene & documentation – 10
EDA depth & correctness – 30
Feature engineering – 10
Visuals & storytelling – 30
Reflection & insights – 15
Bonus (+5) for interactivity, innovative features, or creative dataset integration


# Dataset Information

This is a dataset of 1025 pokemons. This dataset contains the following data:

Pokemon's id
Pokemon's name
Pokemon's rank (whether it is legendary, mythical, baby or an ordinary pokemon)
Pokemon's generation
The pokemon from which this pokemon evolved from
It's primary and secondary type as type1 and type2
It's base stats
It's height (decimetres) and weight (hectograms)
It's abilities (Note: if a pokemon has multiple abilities such as overgrow and chlorophyll than they are separated by a space and if there is a space in the name of the ability it has been replaced by a hyphen for example a pokemon with abilities blaze and solar power it is given as blaze solar-power)
A little description of the pokemon in english (description of pokemons from 1009 is marked as "Not Available").
I have not included data about mega evolutions because I scraped this data for making a pokedex.


