# Deep Learning Midterm Project

This repository contains the code for my deep learning midterm project.

## Files

- `notebook-midterm.ipynb`  
  End-to-end inference notebook for generating `submission.csv`.

- `train&plot.ipynb`  
  Training notebook, including model training and plotting.

## Model / Data Access

Because the model/data files are too large to upload directly to GitHub, they are shared through Google Drive:

- Google Drive folder:  
  [Project Files on Google Drive](https://drive.google.com/drive/folders/1IGBH0VLOBSJkwweHLeGk_NS0ohnATqsw?usp=drive_link)

Please download the required files from the Google Drive folder before running the notebooks.

## Kaggle Notebook

The public Kaggle notebook for this project is available here:

- [Kaggle Notebook: notebook-midterm](https://www.kaggle.com/code/chenjunjiejaywang/notebook-midterm)

## How to Use

### 1. Download files from Google Drive
Download the required model/data files from the shared Google Drive folder.

### 2. Update local paths in the notebooks
Before running the notebooks, please update the file paths in:

- `notebook-midterm.ipynb`
- `train&plot.ipynb`

Replace the original paths with the locations on your own machine / Google Drive / Kaggle environment.

### 3. Run the notebooks
- Use `train&plot.ipynb` if you want to reproduce the training process.
- Use `notebook-midterm.ipynb` if you want to reproduce the final inference pipeline and generate `submission.csv`.

## Notes

- `notebook-midterm.ipynb` is intended for final end-to-end submission generation.
- `train&plot.ipynb` contains the training and visualization workflow.
- Since external files are stored in Google Drive, path modification is required before execution.
