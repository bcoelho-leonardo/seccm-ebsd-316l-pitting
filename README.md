# SECCM–EBSD 316L pitting: preprocessing + descriptors

This repository contains a Jupyter notebook to preprocess SECCM chronoamperometry (CA) signals and extract electrochemical descriptors used in a correlative SECCM–SEM/EBSD workflow for 316L stainless steel pitting studies.

## Contents
- `preprocessing_seccm_ca_descriptors.ipynb` — main notebook
- `data/` — place downloaded input files here (see `data/README.md`)
- `outputs/` — generated results (created automatically)

## Quick start
1) Clone/download this repository.
2) Download the dataset files (see the dataset link in the paper / Zenodo).
3) Copy the files into `./data/`
4) Open and run:
   - `preprocessing_seccm_ca_descriptors.ipynb`

## Data location (two options)
- Option A (default): put files in `./data/`
- Option B: set an environment variable `SECCM_DATA_DIR` pointing to the folder that contains the files.

## License
MIT (code). Data license follows the dataset repository.
