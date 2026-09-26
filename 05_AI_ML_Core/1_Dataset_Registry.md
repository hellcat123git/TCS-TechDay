---
tags: [dataset, registry]
last_updated: 2026-09-26
---
# 📊 Dataset Registry

**Purpose:** Tracks all datasets used for training, validation, and testing.

## Dataset: [Dataset Name]
- **Source:** [URL or Internal Path]
- **Size:** [e.g., 50GB, 1M rows]
- **Type:** [e.g., Image, Text, Tabular]
- **Description:** Brief description of what the data represents.

### Preprocessing Steps Applied
1. [e.g., Tokenization using BPE]
2. [e.g., Normalized pixel values to 0-1]

### Splits
- **Train:** 80% (Path: `data/processed/train.csv`)
- **Val:** 10% (Path: `data/processed/val.csv`)
- **Test:** 10% (Path: `data/processed/test.csv`)

### Data Lineage & Quirks
> [!warning] Known Issues
> Note any biases, missing values, or anomalies in the dataset here so the modeling team is aware.

## Related Context
- Used by models in: [[2_Model_Architecture]]
- Results logged in: [[3_Experiment_Tracker]]
