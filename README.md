# LCDW - Localized Construction and Demolition Waste Dataset

> **Paper Title:** *LCDW: A Benchmark Dataset and Explainable Error Taxonomy for Segmentation in Cluttered Construction Waste Scenes*

---

## Overview

This repository contains the **LCDW (Localized Construction and Demolition Waste)** dataset, annotations, configuration files, and analysis code accompanying the paper. The LCDW dataset supports instance segmentation of CDW materials across 10 material classes.

**Note:** This repository currently contains sample images of the dataset. The full dataset, along with the model configuration files, trained checkpoint, detection error taxonomy code, and D-RISE saliency map generation code, will be made publicly available upon paper acceptance.

[Sample Dataset](https://drive.google.com/drive/folders/12xop4qWHE0VyaCYxD31KNy5o3cU5yvKY?usp=sharing)

## Dataset
---
### Dataset Structure

```
LCDW/
└── datasets/
    ├── Raw/
    │   ├── annotations/
    │   │   ├── train.json
    │   │   ├── val.json
    │   │   └── test.json
    │   └── images/
    │       ├── train/
    │       ├── val/
    │       └── test/
    └── Slice/
        ├── annotations/
        │   ├── train.json
        │   ├── val.json
        │   └── test.json
        └── images/
            ├── train/
            ├── val/
            └── test/
```
### Download

| Asset | Link |
|---|---|
| LCDW (_Raw_) Images + Annotations | *to be added* |
| LCDW (_Slice_) Images + Annotations | *to be added* |
| MaskDINO checkpoint | *to be added* |
| Detection Error Taxonomy Code | *to be added* |
| D-RISE Saliency Map Generation Code | *to be added* |

### CDW Material Classes (10)

| ID | Class |
|---|---|
| 0 | Concrete |
| 1 | Bricks |
| 2 | Mortar (Plaster) |
| 3 | Wood |
| 4 | Ceramic Tiles |
| 5 | Fill Dirt (Fines) |
| 6 | Soil |
| 7 | Asphalt |
| 8 | Plastic |
| 9 | General |

