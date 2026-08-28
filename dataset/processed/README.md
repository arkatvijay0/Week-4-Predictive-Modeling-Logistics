
---

# `Dataset/Processed/README.md`

Copy this into the **Processed Dataset folder**:

```markdown
# Processed Dataset

## Overview

This folder contains the processed version of the logistics dataset used for predictive modeling.

The processed dataset is prepared from the original raw logistics dataset and is intended for machine learning analysis.

---

## Processing Steps

The data preparation workflow included:

1. Loading the raw dataset.
2. Inspecting dataset structure and data types.
3. Checking missing values.
4. Checking duplicate records.
5. Reviewing numerical and categorical variables.
6. Preparing the target variable.
7. Encoding categorical variables.
8. Preparing numerical features.
9. Identifying potential target leakage.
10. Removing leakage-prone predictors from the final modeling feature set.

---

## Target Variable

The prediction target is:

```text
risk_classification
