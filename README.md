# Twins Facial Recognition Dataset and Evaluation Framework

This repository provides a comprehensive framework for evaluating face recognition models on identical twin verification tasks using a 10-fold cross-validation protocol.

## Overview

Twin face verification represents one of the most challenging scenarios in face recognition, as identical twins share nearly identical facial features. This dataset and evaluation framework enables rigorous testing of state-of-the-art face recognition models on twin discrimination tasks.

### Key Features
- **Celebrity twins dataset** with aligned face images
- **10-fold cross-validation** protocol with twin-disjoint folds
- **Comprehensive evaluation metrics** including per-twin analysis
- **Human evaluation toolkit** for blind testing
- **Support for multiple FR models** (ArcFace, AdaFace, MagFace, UniFace)

## Citation
If you find this dataset or evaluation framework helpful, please cite our paper:
```
@article{twins_face_recognition_2025,
  title={},
  author={},
  journal={},
  year={}
}
```

## Table of Contents
<!--ts-->
- [Environment Setup](#environment-setup)
- [Dataset Structure](#dataset-structure)
  * [Celebrity Twins Dataset](#celebrity-twins-dataset)
  * [Data Alignment](#data-alignment)
  * [Fold Generation](#fold-generation)
- [Human Evaluation](#human-evaluation)
  * [Generating Test PDFs](#generating-test-pdfs)
  * [Response Scale](#response-scale)
- [Model Evaluation](#model-evaluation)
  * [Testing Protocol](#testing-protocol)
  * [Per-Twin Analysis](#per-twin-analysis)
- [Dataset Statistics](#dataset-statistics)
- [Results](#results)
- [Acknowledgement](#acknowledgement)
- [License](#license)
<!--te-->
