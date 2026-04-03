# Deep Learning Midterm Project

This repository contains the code and resources for my Deep Learning midterm project, including the Kaggle notebook for offline submission generation, the Colab notebook for training and analysis, and the external files required for reproduction.

## Repository Structure

- `README.md`  
  Project overview, resource links, and reproduction instructions.

- `notebook-midterm.ipynb`  
  The only notebook stored directly in this GitHub repository. This is the **Kaggle notebook**, which directly loads the two model files and runs **offline inference** to generate `submission.csv`.

## Notebook Access

### Kaggle notebook in this repository
The only notebook attached in this GitHub repository is the Kaggle notebook:

- `notebook-midterm.ipynb`

This notebook is intended for the final **offline inference** pipeline. It directly loads the two model files and generates `submission.csv`.

### Colab notebook
The Colab notebook is provided separately through Google Colab:

- **Colab notebook**  
  [Open in Google Colab](https://colab.research.google.com/drive/1w3AXkJwu3ZnaeWbGtuU1njG8hMipCb8k?usp=drive_link)

The Colab notebook can read data from the **data folder**, train the model, generate submission outputs, and produce the final plots.

## External Files

Some model and data files are too large to be stored directly in this GitHub repository. They are provided through Google Drive links below.

### Google Drive Resources

- **Data folder**  
  [Google Drive Folder](https://drive.google.com/drive/folders/1IGBH0VLOBSJkwweHLeGk_NS0ohnATqsw?usp=drive_link)

- **Adapter file**  
  [Adapter Link](https://drive.google.com/file/d/1jjA8fkHpYrtjLiSdzyTG6ncxYfa91Qyk/view?usp=drive_link)

- **Base model file**  
  [Base Model Link](https://drive.google.com/file/d/1b5FkFIuhBHMqa1f-EqsKsYi6pREV1P2h/view?usp=drive_link)

Please download or mount the required files from the links above before running the notebooks.

## Reproducibility

This project is organized to support reproducibility across both training and inference:

- The **Kaggle notebook** in this repository is used for final offline inference and submission generation.
- The **Colab notebook** is used for reading data from the data folder, training the model, generating submission results, and producing plots.
- The **Google Drive resources** provide the large external files required for reproduction.

## Usage Instructions

### 1. Access the required files
Download or mount the model/data files from the Google Drive links above.

### 2. Choose the notebook based on your goal

- Use `notebook-midterm.ipynb` if you want to reproduce the final **offline Kaggle inference** pipeline and generate `submission.csv`.
- Use the **Colab notebook** if you want to reproduce the **training process**, generate submission outputs, and create plots.

### 3. Update file paths if needed
Before running the notebooks, update the file paths so that they match your own environment, such as Google Drive, local storage, or Kaggle input folders.

## Notes

- The only notebook directly attached in this GitHub repository is the **Kaggle notebook**.
- The Kaggle notebook is designed to directly load the two model files and perform **offline inference** for generating `submission.csv`.
- The Colab notebook is designed for a more complete workflow, including reading data from the **data folder**, training, submission generation, and plotting.
- External resources are hosted on Google Drive because of file size limits.
