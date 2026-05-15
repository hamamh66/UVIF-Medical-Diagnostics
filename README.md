# UVIF-DQA: Variational Diagnostic Intelligence for Trustworthy Educational Question Answering

## Overview

This repository provides the official implementation and reproducible experimental framework for:

> **UVIF-DQA: Variational Diagnostic Intelligence and Reliability-Aware Evidence Selection for Trustworthy Educational Question Answering**

The proposed framework introduces a reliability-aware diagnostic reasoning architecture grounded in the Unified Variational Intelligence Framework (UVIF).

## Key Contributions

- Reliability-aware educational QA
- Variational evidence selection
- Calibration-aware confidence modeling
- Selective prediction analysis
- Evidence stability evaluation
- Public benchmark reproducibility using SciQ

## Dataset

```python
from datasets import load_dataset
dataset = load_dataset("allenai/sciq")
```

## Installation

```bash
pip install -r requirements.txt
```

## Citation

```bibtex
@misc{Hamam2026UVIFFDQA,
  author       = {Habib Hamam and Fatma Mallek and Sghaier Guizani and Zeyad Alghamdi},
  title        = {UVIF-DQA: Variational Diagnostic Intelligence and Reliability-Aware Evidence Selection for Trustworthy Educational Question Answering},
  year         = {2026},
  howpublished = {https://github.com/hamamh66/UVIF-DQA}
}
```
