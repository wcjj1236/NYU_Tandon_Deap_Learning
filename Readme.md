# Deep Learning Midterm Project

This repository contains the code and resources for my Deep Learning midterm project, including both the training workflow and the end-to-end inference pipeline used to generate the final `submission.csv`.

## Repository Structure

- `notebook-midterm.ipynb`  
  End-to-end inference notebook for reproducing the final submission file (`submission.csv`).

- `train&plot.ipynb`  
  Training and plotting notebook for reproducing the model training process and related visualizations.

## External Files

Some model and data files are too large to be stored directly in this GitHub repository. They are provided through Google Drive links below.

### Google Drive Resources

- **Project folder**  
  [Google Drive Folder](https://drive.google.com/drive/folders/1IGBH0VLOBSJkwweHLeGk_NS0ohnATqsw?usp=drive_link)

- **Adapter file**  
  [Adapter Link](https://drive.google.com/file/d/1jjA8fkHpYrtjLiSdzyTG6ncxYfa91Qyk/view?usp=drive_link)

- **Base model file**  
  [Base Model Link](https://drive.google.com/file/d/1b5FkFIuhBHMqa1f-EqsKsYi6pREV1P2h/view?usp=drive_link)

Please download the required files from the links above before running the notebooks.

## Kaggle Notebook

The public Kaggle notebook associated with this project is available here:

- [Kaggle Notebook: notebook-midterm](https://www.kaggle.com/code/chenjunjiejaywang/notebook-midterm)

## Reproducibility

This repository is organized to support reproducibility of both training and inference:

- Use `train&plot.ipynb` to reproduce the training procedure and plots.
- Use `notebook-midterm.ipynb` to reproduce the final inference pipeline and generate `submission.csv`.

## Usage Instructions

### 1. Download external files
Download the required model/data files from the Google Drive links above.

### 2. Update file paths
Before running the notebooks, update the file paths in:

- `notebook-midterm.ipynb`
- `train&plot.ipynb`

The original paths should be replaced with the corresponding locations on your own machine, Google Drive, or Kaggle environment.

### 3. Run the notebooks
- Run `train&plot.ipynb` for training and plotting.
- Run `notebook-midterm.ipynb` for end-to-end inference and submission generation.

## Notes

- `notebook-midterm.ipynb` is intended for final submission reproduction.
- `train&plot.ipynb` is intended for training reproduction and visualization.
- Since the external resources are hosted on Google Drive, path modification is required before execution.
