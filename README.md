# SECCM–SEM/EBSD correlative dataset (316L pitting): CA preprocessing + descriptor extraction

This repository provides a **reproducible Jupyter workflow** to preprocess **SECCM chronoamperometry (CA)** signals and extract electrochemical **descriptors/features**, designed for **correlative analysis with SEM and EBSD** in **316L stainless steel pitting** studies.

## What you get
- A single, runnable notebook that:
  - loads SECCM CA traces
  - performs preprocessing / signal handling
  - extracts descriptor tables used in the study
  - supports footprint-area normalization (via `selected_oval_pixels.csv`)
  - optionally links to SEM/EBSD correlative inputs

## Repository structure
- `preprocessing_seccm_ca_descriptors.ipynb` — main notebook
- `data/` — **put the downloaded dataset files here** (see `data/README.md`)
- `outputs/` — generated results (created automatically; ignored by git)

## Dataset
- **Zenodo DOI:** _to be added_
- Download the dataset from Zenodo and place the files into `./data/` (Option A below).

## Quick start
1) Clone/download this repository.
2) Download the dataset files from **Zenodo**.
3) Copy the dataset files into `./data/` (see `data/README.md` for the required filenames).
4) Open and run `preprocessing_seccm_ca_descriptors.ipynb`.

## Data location options
**Option A (default, recommended):** place files in `./data/`

**Option B (advanced):** set `SECCM_DATA_DIR` to the folder containing the files  
- Windows (PowerShell): `setx SECCM_DATA_DIR "C:\path\to\data"`
- macOS/Linux (bash): `export SECCM_DATA_DIR="/path/to/data"`

## Citation
If you use this code or dataset, please cite:
- the associated paper (once published)
- the Zenodo dataset (DOI above)
- optionally the software release DOI (if you enable GitHub→Zenodo archiving for releases)

## License
- **Code:** MIT License (see `LICENSE`)
- **Data:** licensed and archived via the Zenodo dataset record
