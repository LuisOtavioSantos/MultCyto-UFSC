# MultiCyto-UFSC

## Unified Multi-Stain Cytopathology Segmentation

This repository provides code and resources for the paper **Unified Multi-Stain Analysis for Cytopathology Segmentation**, which investigates training a single instance segmentation model across three cytological stains: Papanicolaou, Feulgen, and AgNOR.

![Pipeline Diagram](images/Diagram.svg)

---

## Overview

- **Objective:** Train and evaluate unified deep learning models for cell structure segmentation in multi-stained cytology images.
- **Key Contributions:**
  - Unified multi-stain training strategy.
  - Benchmark of Mask R-CNN, Mask2Former, YOLO11n, and YOLO12n on cytopathology images.
  - Generalization analysis (AP50 / AP75) on combined datasets.

## Getting Started

- **Dependencies:**  
  Install requirements from `requirements.txt`:
  ```bash
  pip install -r requirements.txt
  ```


## Main Results

| Model       | AP75 (Combined) | AP50 (Combined) |
| ----------- | --------------- | --------------- |
| Mask R-CNN  | 0.381           | 0.433           |
| Mask2Former | **0.441**       | **0.512**       |
| YOLO11n     | 0.409           | 0.500           |
| YOLO12n     | 0.299           | 0.387           |


---
## Model Weights

Pretrained model weights are available here:
[Google Drive](https://drive.google.com/drive/folders/1y4od9U2hsqB_zjTSPSrC0Fl7vpkXUcPM?usp=sharing)

## Dataset

[UFSC Multi-Cyto: Multi-Stain Cytopathology Image Dataset - Mendeley Data](https://data.mendeley.com/datasets/b8bygdxr7r/1)


---

