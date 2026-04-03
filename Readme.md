# NYU Tandon Deep Learning Midterm: Text-to-SVG Generation

This repository contains my code for the NYU Tandon Deep Learning midterm Kaggle competition on text-to-SVG generation.

## Repository Contents

- `notebook-midterm.ipynb`  
  Final **offline end-to-end inference notebook**.  
  This notebook loads the base model and adapter, runs generation on the test set, and writes `submission.csv`.

- `train&plot.ipynb`  
  Training and analysis notebook.  
  This notebook contains the model training pipeline, logging, and plotting code used for experiments and report figures.

## Public Kaggle Notebook

The final Kaggle notebook is public here:

- Kaggle notebook: [notebook-midterm](https://www.kaggle.com/code/chenjunjiejaywang/notebook-midterm)

## Model Weights

To make reproduction easier, I provide both the **adapter** and the **base model** through Google Drive.

- Adapter weights: [Google Drive link](https://drive.google.com/file/d/1jjA8fkHpYrtjLiSdzyTG6ncxYfa91Qyk/view?usp=drive_link)
- Base model: [Google Drive link](https://drive.google.com/file/d/1b5FkFIuhBHMqa1f-EqsKsYi6pREV1P2h/view?usp=drive_link)

## Recommended Folder Structure

After downloading the data and model files, a convenient local structure is:

```text
project_root/
├── notebook-midterm.ipynb
├── train&plot.ipynb
├── data/
│   ├── train.csv
│   ├── test.csv
│   └── sample_submission.csv
├── weights/
│   ├── adapter/
│   └── base_model/
└── outputs/
