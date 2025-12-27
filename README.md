
**BFC-Net**

Overview
--------
BFC-Net is a small research workspace for developing and experimenting with the BFC-Net model. The repository provides a Jupyter notebook for preprocessing, training, and evaluation experiments, plus a `requirements.txt` file listing the needed Python packages.

Project definition
------------------
- **Goal:** Provide a reproducible starting point for experiments that use the BFC-Net architecture (replace with your exact task, e.g., "brain functional connectivity classification", "image segmentation", etc.).
- **Contents:** an interactive `notebook.ipynb` that demonstrates data loading, preprocessing, model setup, and evaluation. Use the notebook as the canonical example to reproduce results.

Datasets
--------
This project requires three datasets. If you already have local copies, place them under `data/<DATASET_NAME>/` with `Image-train`, `GT-train`, `Image-test`, `GT-test` subfolders.

- **ORSSD**
   - Short name: ORSSD
   - Description: Optical Remote Sensing Salient Object Detection dataset (common benchmark for salient object detection on optical remote-sensing images).
   - Search / download:
      - Kaggle search results: https://www.kaggle.com/search?q=ORSSD
      - GitHub search results: https://github.com/search?q=ORSSD+dataset

- **EORSSD**
   - Short name: EORSSD (extended ORSSD)
   - Description: Extended version of ORSSD with additional annotated examples.
   - Search / download:
      - Kaggle search results: https://www.kaggle.com/search?q=EORSSD
      - GitHub search results: https://github.com/search?q=EORSSD+dataset

- **ORSI-4199**
   - Short name: ORSI-4199
   - Description: A dataset of optical remote sensing images with salient object annotations (often referenced as ORSI or ORSI-4199 in SOD literature).
   - Search / download:
      - Kaggle search results: https://www.kaggle.com/search?q=ORSI-4199
      - GitHub search results: https://github.com/search?q=ORSI-4199+dataset

How to add your dataset
-----------------------
1. Download the dataset ZIP or archive from one of the links above (or your own dataset URL).
2. Unpack into a `data/` subdirectory at the repository root, preserving the structure expected by the notebook (e.g., `data/primary/`, `data/supplementary/`).

Quick setup
-----------
1. Create and activate a virtual environment (recommended):

   python -m venv .venv
   .venv\Scripts\activate   (on Windows)

2. Install dependencies:

   pip install -r requirements.txt

Running the notebook
--------------------
1. Start Jupyter Notebook or JupyterLab:

   jupyter notebook

2. Open `notebook.ipynb` and run the cells. Make sure the `data/` folder contains the required dataset files before running training cells.

Repository structure
--------------------
- `notebook.ipynb` — primary entry point for experiments and examples.
- `requirements.txt` — dependency manifest.
- `data/` — suggested location for downloaded datasets (create this folder manually).

Contributing
------------
Contributions are welcome. Please open issues or pull requests with focused changes.

License
-------
No license is included in this repository. If you plan to share or distribute this work, add a `LICENSE` file with your chosen license.

Contact
-------
For questions, contact the repository owner or open an issue in the project.
