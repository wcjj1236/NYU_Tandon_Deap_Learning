# Deep Learning Final Project: Pixels to Predictions

This repository contains the code and resources for my Deep Learning final project. The repository is organized around the final Kaggle offline inference notebook, which directly loads the trained model files and generates the final `submission.csv`.

## Repository Structure

- `README.md`  
  Project overview, resource links, and reproduction instructions.

- `notebook-final.ipynb`  
  The notebook stored directly in this GitHub repository. This is the **Kaggle offline inference notebook** used for the final submission. It directly loads the pretrained base model and the fine-tuned LoRA adapter, runs offline inference on the Kaggle test set, and generates `submission.csv`.

## Notebook Access

### Kaggle offline inference notebook in this repository

The notebook attached in this GitHub repository is the final Kaggle offline inference notebook:

- `notebook-final.ipynb`

This notebook is intended for the final reproducible inference pipeline. It does **not** run the full ablation study or retrain the model. Instead, it directly loads the saved model files and generates the final Kaggle submission file.

The notebook is designed to run under Kaggle's offline setting by loading all required model files from Kaggle input datasets or manually uploaded external files.

## External Files

Some model and data files are too large to be stored directly in this GitHub repository. They are provided through Google Drive links below.

### Google Drive Resources

- **Data folder**  
  [Google Drive Folder](https://drive.google.com/drive/folders/1IGBH0VLOBSJkwweHLeGk_NS0ohnATqsw?usp=drive_link)

- **Fine-tuned LoRA adapter**  
  [Adapter Link](https://drive.google.com/file/d/1jjA8fkHpYrtjLiSdzyTG6ncxYfa91Qyk/view?usp=drive_link)

- **Base model**  
  [Base Model Link](https://drive.google.com/file/d/1b5FkFIuhBHMqa1f-EqsKsYi6pREV1P2h/view?usp=drive_link)

Please download or mount the required files from the links above before running the notebook.

## Reproducibility

This project is organized to support final submission reproducibility.

The GitHub repository focuses on the final Kaggle inference pipeline:

- The notebook in this repository is the **Kaggle offline inference notebook**.
- It loads the trained base model and LoRA adapter.
- It performs inference on the Kaggle test set.
- It generates the final `submission.csv`.
- It does not require rerunning the ablation study notebook.

The ablation and training notebooks were used during model development, hyperparameter tuning, and report generation, but they are not required for reproducing the final Kaggle submission from this repository.

## Usage Instructions

### 1. Prepare the required files

Download the required model files from the Google Drive links above, or upload them as Kaggle datasets.

The offline inference notebook expects access to:

- the base model directory,
- the fine-tuned LoRA adapter directory,
- the Kaggle competition test files,
- and the sample submission file.

### 2. Run the Kaggle offline inference notebook

Open and run:

```text
notebook-final.ipynb
