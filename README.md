# GANESH title
Jupyter notebook (Statistical_analysis.ipynb) for performing the statistical analysis presented in "GANESH title".

## Contents
- **Data loading**: Reads in cleaned dataset used in this study.
- **MOS score**: Processes data and fits models with outcome variable = MOS score
- **Aberrant GMs**: Processes data and fits models with outcome variable = Aberrnat GMs (MOS < 20, 23)
- **Adverse outcome**: Processes data and fits models with outcome variable = Diagnosed disorder
- **Association between predictors**: Processes data and fits models with outcome variable = Diagnosed disorder
- **Summary of models**: Creates tables and plots summarising key modelling results

## Getting started
This notebook requires Python and several key libraries. It is recommended to use the provided `environment.yml` or `requirements.txt` files to create an environment with all necessary dependencies.
1. Clone the repository
```bash
git clone https://github.com/kpatsis97/GANESH_project.git
```
2. Create the conda environment:
```bash
conda env create -f environment.yaml
conda activate ganesh
```
Alternatively, install packages manually with:
```bash
pip install -r requirements.txt
```

