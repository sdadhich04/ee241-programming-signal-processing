# EE 241 Programming Signal Processing Labs

Post-course portfolio curation of five EE 241 labs from Programming for Signal and Information Processing Applications at the University of Washington.

This repository collects notebook-based signal and information processing exercises spanning Python fundamentals, vectorized numerical computing, image processing, tabular data analysis, and graph/network analysis. The notebooks are organized by lab and include the small input files needed by the submitted code.

## Contents

| Lab | Focus | Main notebook |
| --- | --- | --- |
| 1 | Python basics, distance calculations, trigonometry tables, boolean logic, list slicing | `lab1/lab1_report.ipynb` |
| 2 | NumPy vectorization, triangular and sinusoidal waveform generation, audio synthesis | `lab2/lab2_report.ipynb` |
| 3 | Image thresholding, thumbnail/downsampling, image blending, rotation, 2D Gaussian visualization | `lab3/lab3_report.ipynb` |
| 4 | CSV parsing, confidence intervals, rolling mean/median filters, stock movement detection, debugging exercises | `lab4/lab4_report.ipynb` |
| 5 | Graph visualization, hub detection, vertex removal, directed graph analysis, C. elegans connectome data | `lab5/lab5_report.ipynb` |

## Running The Notebooks

Create a Python environment and install the notebook dependencies:

```powershell
python -m venv .venv
.\.venv\Scripts\Activate.ps1
pip install -r requirements.txt
jupyter lab
```

Open each lab from the repository root so relative paths to CSV, image, NumPy, Excel, PNG, and MP4 inputs resolve correctly.

## Data And Publication Notes

This repo includes small course-provided inputs because the notebooks read them directly. That makes the local project reproducible, but it also means the repo should stay private unless the course data sharing terms are confirmed or the inputs are replaced with shareable demo data.

The notebooks for Labs 3, 4, and 5 explicitly credit Sam Decker as a group member. Lab 2's notebook has a blank group-members field, so public attribution for that lab should be confirmed before publication.

For repository hygiene, display-only cells that referenced omitted course prompt screenshots were removed. A Colab drive-mount setup cell was also removed from Lab 2 so the notebooks use local relative paths. The student solution cells and runtime inputs are otherwise preserved.

No license is included. Until authorship and course-data permissions are settled, all rights remain reserved by the respective authors and data owners.
