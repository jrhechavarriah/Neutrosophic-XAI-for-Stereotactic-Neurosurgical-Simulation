# Neutrosophic-XAI-for-Stereotactic-Neurosurgical-Simulation

Reproducible Python code for the Frontiers manuscript.  
This repository contains the full simulation pipeline used to generate the synthetic dataset, all statistical analyses, and all figures and tables reported in the article.

## Contents
- `neutrosophic_xai_stereotactic_neurosurgical_simulation.py` — main script
- Auto-generated outputs saved in `neutrosophic_outputs/`
- Synthetic dataset and statistics (CSV + PNG)

## How to Run
```
pip install numpy pandas matplotlib scipy scikit-posthocs
python neutrosophic_xai_stereotactic_neurosurgical_simulation.py
```

## Reproducibility
Running the script regenerates 100% of the results presented in the manuscript, including:
- Synthetic trainee dataset  
- Neutrosophic T–I–F membership values  
- Competence scores  
- Figures (pipeline, boxplots, decision boundaries, scatterplots, membership functions, 3D surface & heatmap)  
- Tables (descriptive statistics, normality tests, Kruskal–Wallis, Dunn post hoc)

## Citation
**Hechavarría-Hernández, J.R. (2025). Neutrosophic XAI Simulation Code Supporting the Framework for Modeling Uncertainty in Stereotactic Simulation. Zenodo. https://doi.org/10.5281/zenodo.17904989**

## License
Code: MIT  
Generated outputs: CC-BY 4.0
