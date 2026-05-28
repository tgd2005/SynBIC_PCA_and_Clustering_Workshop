# SynBIC Bioinformatics Seminar: Introduction to PCA, Clustering and Data Analysis

This repo is for a Bioinformatics Seminar organised by Imperial College London's Synthetic Biology Society (SynBIC). The contents here are designed to be friendly to life sciences students who wish to learn useful analytical methods in PCA, Clustering and Downstream Analysis techniques, but may be daunted by the underlying mathematics.

**Access notebook 00 here:**
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://github.com/tgd2005/SynBIC_PCA_and_Clustering_Workshop/blob/main/00_introduction_to_PCA.ipynb)

**Access notebook 01 here:**
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)]([YOUR_NOTEBOOK_LINK_HERE](https://github.com/tgd2005/SynBIC_PCA_and_Clustering_Workshop/blob/main/00_introduction_to_PCA.ipynb))

## Quick start

This workshop is designed to run most easily in **Google Colab**, which requires no local installation.

1. Click the **Open in Colab** badge above.
2. Save a copy to your own Google Drive if prompted.
3. Follow the notebooks alongside the live presentation from this seminar.


## Setting up a virtual environment formally
___
If Conda is available, you can use:

```bash
conda env create -f pca_env.yml
conda activate pca-workshop
```

If you Conda is not set up, use Python 3.12 + venv (recommended fallback on Windows):

```powershell
# Check Python 3.12 is installed
py -3.12 --version

# Create virtual environment
py -3.12 -m venv .venv

# Activate (using PowerShell)
.\.venv\Scripts\Activate.ps1

# Install workshop dependencies
python -m pip install --upgrade pip
pip install -r requirements.txt
```

Activate in CMD instead:

```cmd
.venv\Scripts\activate.bat
```
