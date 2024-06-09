# Dataset

## Table of Contents
- [Table of Contents](#table-of-contents)
- [Introduction](#introduction)
- [Dataset Structure](#dataset-structure)
- [Training Image and Model Tflite](#training-Image-and-model-tflite)
  - [Example Directory Structure](#example-directory-structure)





## Introduction

You can download the dataset using this link: [datasets.rar](https://storage.googleapis.com/sweple.appspot.com/datasets.rar) (40GB)

## Dataset Structure
The dataset is organized into the following main directories:
- `raw_data`: Contains the raw, unprocessed images and metadata files.

## Training Image and Model Tflite
Train model [image_model.ipynb](https://github.com/giziloid/model-gizilo/blob/master/dataset/image_model.ipynb) and here model Tflite [model.tflite](https://github.com/giziloid/model-gizilo/blob/master/dataset/model.tflite)
### Example Directory Structure

```bash
dataset
├── Train 
│   ├── product1
│   │   ├── image.jpg
│   │   └── ...
│   ├── product1
│   │   ├── image.jpg
│   │   └── ...
│   └── ...
└── Test
    ├── product
    │   ├── image.jpg
    │   └── ...
    ├── product1
    │   ├── image.jpg
    │   └── ...
    └── ...

```
