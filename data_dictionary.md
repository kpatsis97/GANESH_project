# Data Dictionary

This file describes the variables expected by `Statistical_analysis.ipynb`. The dataset (`GANESH_clean.csv`) is not publicly available due to data sharing restrictions. Researchers wishing to replicate this analysis should prepare a dataset with the following columns.

| Variable | Description | Type | Values / Range |
|---|---|---|---|
| `Sex` | Biological sex of the infant | Categorical | `M` = Male, `F` = Female |
| `Cast_code_extract` | Caste classification of the family | Ordinal | `SC/ST` < `OBC` < `GENERAL`; `NaN` = missing |
| `Preterm` | Whether the infant was born preterm (< 37 weeks gestation) | Boolean | `True`, `False`; `NaN` = missing |
| `medical_pregnancy_problem` | Whether a medical problem was reported during pregnancy | Categorical | `No problem`, `Problem`; `NaN` = missing |
| `c_section` | Whether the infant was delivered by caesarean section | Boolean | `True`, `False`; `NaN` = missing |
| `institution_delivery` | Whether the birth took place at a medical institution | Boolean | `True`, `False`; `NaN` = missing |
| `malnourished` | Whether the infant was classified as undernourished | Boolean | `True`, `False` |
| `Birth_weight_below_2_5kg` | Whether birth weight was below 2.5 kg (low birth weight threshold) | Boolean | `True`, `False`; `NaN` = missing |
| `Final_MOS_score` | Continuous Movement Optimality Score (MOS) reflecting quality of general movements | Numeric | Range: 6 – 28; `NaN` = missing |
| `Aberrant_GM_MOS_below20` | Binary indicator of aberrant general movements using MOS threshold < 20 | Binary | `1` = Aberrant, `0` = Normal |
| `Aberrant_GM_MOS_below23` | Binary indicator of aberrant general movements using MOS threshold < 23 | Binary | `1` = Aberrant, `0` = Normal |
| `Diagnosed_disorder` | Whether the infant was classified as having an adverse outcome | Binary | `1` = Diagnosed, `0` = No diagnosis; `NaN` = missing |

## Notes
- `NaN` indicates missing data throughout the dataset.
- `Aberrant_GM_MOS_below20` and `Aberrant_GM_MOS_below23` are derived from classification of writhing movements, fidgety movements and `Final_MOS_score` using two different clinical thresholds.
