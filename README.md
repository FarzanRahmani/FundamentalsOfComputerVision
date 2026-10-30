# Fundamentals of Computer Vision

Practical notebooks, assignment material, and project experiments from my sixth-semester B.Sc. Computer Vision course at Iran University of Science and Technology, taught by Dr. Mohammadreza Mohammadi. Author: Farzan Rahmani.

## Repository Guide

| Path | Contents |
| --- | --- |
| `HW0/` | Introductory image/video exercises and supporting assets |
| `HW1/`–`HW5/` | Question-specific computer-vision notebooks and assignment materials |
| `HW6/` | Additional vision notebooks, including `ss_notebook.ipynb` |
| `HW7/` | Detection notebook, practical question notebook, and image-label files |
| `project/` | Tile-image analysis experiments preserved as `CV_Project1_Tile*.ipynb` iterations |

The project notebooks use OpenCV, NumPy, image inputs, and JSON annotations. Multiple numbered versions preserve different experiments; consult their cells and accompanying material to choose the relevant version.

## Environment and Usage

Use Python with Jupyter or Google Colab. A starting environment for the classical image-processing notebooks is:

```sh
python -m pip install jupyterlab numpy matplotlib opencv-python
python -m jupyterlab
```

Dependencies vary across assignments. Read the selected notebook's import and setup cells before installing additional libraries, especially for detection or neural-network experiments.

1. Read the matching assignment instructions and locate the required image, video, or annotation files.
2. Open the selected notebook and review its data-loading cells. Some notebooks fetch data from Google Drive or assume hosted-runtime paths.
3. Update local paths in your working copy or reproduce the original hosted environment.
4. Run cells in order and compare the visual outputs with the written analysis.

Preserve image/label relationships when moving data. Large datasets, pretrained weights, or linked Drive assets may need to be obtained separately. A GPU may be needed for neural-model training, while the classical OpenCV exercises can be explored on a CPU.

## Notes and License

This repository is an educational archive, with saved notebook outputs and intermediate experiments rather than a single installable package. Original explanations may be in Persian. See [LICENSE](LICENSE) for license terms and respect the terms of external datasets and models.
