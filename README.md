# LCDW — Localized Construction and Demolition Waste Dataset

> **Paper:** *[Title — to be added on acceptance]*
> **Journal:** Automation in Construction / Advanced Engineering Informatics

---

## Overview

This repository contains the **LCDW (Localized Construction and Demolition Waste)** dataset, annotations, configuration files, and analysis code accompanying the paper. The LCDW dataset supports instance segmentation of C&DW materials across 10 material classes, collected from multiple active demolition and construction sites in Chennai, India over a period of more than one year.

---

## Dataset

### Download

| Asset | Link |
|---|---|
| LCDW (Raw) — images + annotations | *to be added* |
| LCDW (Slice) — images + annotations | *to be added* |
| MaskDINO checkpoint (LCDWvF2) | *to be added* |

### Sample Images

*to be added*

### Classes (10)

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

### Dataset Variants

**LCDW (Raw)** — original full-resolution images (1920×1080), densely annotated. 136.17 average instances per image, Clutter Index 99.4.

**LCDW (Slice)** — images tiled into 640×640 non-overlapping slices. Packing density 32.4%. This variant is used for all experiments in the paper.

### Annotation Format

Annotations are in **COCO JSON** format with polygon segmentation masks.

### Dataset Structure

```
datasets/
└── LCDW/
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

---

## Citation

If you use the LCDW dataset or this code, please cite:

```bibtex
@article{jaiswal2025lcdw,
  title   = {[Title — to be added]},
  author  = {Jaiswal, Ashwani and [co-authors]},
  journal = {Automation in Construction},
  year    = {2025},
  note    = {Under review}
}
```

---

## Contact

Ashwani Jaiswal — Indian Institute of Technology Madras
