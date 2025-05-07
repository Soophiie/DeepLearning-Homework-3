# Homework 3 — Instance Segmentation  
Visual Recognition using Deep Learning  
Sophie FU (313554802)

## Task Description

The goal of this assignment is to perform **instance segmentation** on a medical image dataset containing up to four types of cells.  
Each image comes with multiple binary masks (`class1.tif` to `class4.tif`), where each object instance is annotated with a unique integer ID.

The objective is to detect and segment each instance and submit predictions in **COCO format** using **Run-Length Encoding (RLE)** masks.

## How to install
Run this notebook in Google Colab. Before running, mount your Google Drive and ensure your dataset is under: /content/drive/MyDrive

Otherwise you should change the dataset_root path

## Requirements
This project was developed and run using:

- Python ≥ 3.8
- PyTorch ≥ 1.12
- torchvision ≥ 0.13
- OpenCV
- scikit-image
- matplotlib
- numpy
- tqdm
- Google Colab (GPU environment recommended)

Optional:
- `pycocotools` for mask encoding/decoding
- `biblatex` (for report compilation)

You can install the required packages via:

```bash
pip install torch torchvision opencv-python scikit-image matplotlib tqdm pycocotools
```


## Performance snapshot
<img width="700" alt="image" src="https://github.com/user-attachments/assets/945ea17c-e3f6-43e6-a1e3-406642ff4795" />
