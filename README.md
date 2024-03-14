# Anti-TB
![Visits Badge](https://img.shields.io/badge/dynamic/json?label=visits&query=$.message&color=blue&url=https://hits.dwyl.com/gu-yaowen/Anti-TB.json)

Codes and datasets for "Machine learning-led virtual screening indicates the anti-tuberculosis activity of aldoxorubicin and quarfloxin with verification by molecular docking, molecular dynamics simulations, and biological evaluations"

# Reference
If you make advantage of the MilGNet model or its modules proposed in our paper, please cite the following in your manuscript:

TBD

# Workflow Overview
![Anti-TB](https://github.com/gu-yaowen/Anti-TB/blob/master/workflow.png)

# Datasets
> ``ChEMBL_dataset.csv`` \
Our collected Anti-Mycobacterium tuberculosis bioactivity dataset from ChEMBL database.

> ``DrugBank_predicted.csv`` \
The estimated Anti-TB bioactivities of molecules in DrugBank database predcited by our ML and GNN models.

> ``DrPurHub_predicted.xlsx`` \
The estimated Anti-TB bioactivities of molecules in Drug Repurposing Hub database predcited by our ML and GNN models.

# Codes
> ``processing.ipynb`` \
To collect, clean, and preprocess our Anti-TB bioactivity dataset from source.

> ``inference.ipynb`` \
To train the ML models. Also conduct testing and inference results from trained ML and GNN models.
To train the GNN models, please refer our previous work [CurrMG](https://github.com/gu-yaowen/CurrMG).
