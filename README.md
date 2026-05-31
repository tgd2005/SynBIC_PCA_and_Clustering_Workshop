# SynBIC Bioinformatics Seminar: Introduction to PCA, Clustering and Data Analysis

This repo is for a Bioinformatics Seminar organised by Imperial College London's Synthetic Biology Society (SynBIC). The contents here are designed to be friendly to life sciences students who wish to learn useful analytical methods in PCA, Clustering and Downstream Analysis techniques, but may be daunted by the underlying mathematics.

For convenience, an access link for Google Colab is provided.

**Access notebook 00 here:**
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/tgd2005/SynBIC_PCA_and_Clustering_Workshop/blob/main/00_introduction_to_PCA.ipynb)

**Access notebook 01 here:**
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/tgd2005/SynBIC_PCA_and_Clustering_Workshop/blob/main/01_approaches_to_clustering.ipynb) --- NOTE: currently unfinished. Aiming to do so by Sunday.


## Quick start

This workshop is designed to run most easily in **Google Colab**, which requires no local installation.

1. Click the **Open in Colab** badge above.
2. Save a copy to your own Google Drive if prompted.
3. Follow the notebooks alongside the live presentation from this seminar.


# To run locally:
You can use the uv package with the default pip installation from python to quickly construct an UV environment.

```bash
git https://github.com/tgd2005/SynBIC_PCA_and_Clustering_Workshop
cd  SynBIC_PCA_and_Clustering_Workshop
pip install uv
uv sync
```

For Windows powershell:
```powershell
.\.venv\Scripts\Activate.ps1
```


Activate in CMD instead:
```cmd
.venv\Scripts\activate.bat
```
