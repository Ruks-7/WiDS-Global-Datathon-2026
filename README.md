# WiDS Global Datathon 2026

This repository contains datasets, notebooks, and submission files for work on the **WiDS Global Datathon 2026** challenge.

## Repository contents

- `Train & Test Data/`
  - `train.csv` – training dataset
  - `test.csv` – test dataset
  - `metaData.csv` – feature and metadata reference
  - `sample_submission.csv` – sample submission format
- `WiDS Datathon 2026.ipynb` and versioned notebooks (`Version_*.ipynb`) – experiments and modeling workflows
- `RSF Submission.csv` – generated submission file

## Getting started

1. Open the notebooks in Jupyter or VS Code.
2. Load data from the `Train & Test Data/` directory.
3. Run notebook cells to reproduce preprocessing, training, and prediction steps.
4. Export predictions in the same format as `sample_submission.csv` for submission.

## Notes

- Keep large data files out of version control when possible.
- Use versioned notebooks to track modeling iterations.
