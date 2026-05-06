# GANESH title
This repository contains the Jupyter notebook (`Statistical_analysis.ipynb`) used to perform the statistical analyses presented in "GANESH title".

## Data Availability
The dataset (`GANESH_clean.csv`) referenced in the notebook is not publicly available due to data sharing restrictions. To run the notebook, you will need to supply your own dataset in the same format. A data dictionary describing the expected variables and structure is provided in `data_dictionary.md`.

## Contents
- **Data loading**: Reads in the cleaned dataset used in this study.
- **MOS score**: Processes data and fits models with outcome variable = MOS score.
- **Aberrant GMs**: Processes data and fits models with outcome variable = Aberrant GMs (MOS < 20, 23).
- **Adverse outcome**: Processes data and fits models with outcome variable = Diagnosed disorder.
- **Association between predictors**: Examines relationships between predictor variables.
- **Summary of models**: Generates tables and figures summarising key modelling results.

## Getting Started

### Requirements
This notebook requires Python and several key libraries. It is recommended to use the provided `environment.yml` file to reproduce the exact environment used in this study.

### Installation
1. Clone the repository:
```bash
git clone https://github.com/kpatsis97/GANESH_project.git
cd GANESH_project
```
2. Create and activate the conda environment:
```bash
conda env create -f environment.yml
conda activate ganesh
```
Alternatively, install dependencies manually with:
```bash
pip install -r requirements.txt
```