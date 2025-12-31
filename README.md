# Semi-Supervised and Self-Supervised Object Detection for License Plate Recognition

**Course:** CSE 475 - Machine Learning

**Semester:** Fall 2025

**University:** East West University

## 📌 Project Overview

This project investigates label-efficient object detection for Automatic License Plate Recognition (ALPR). We benchmark **YOLOv12** against **Semi-Supervised Learning (Pseudo-Labeling)** and **Self-Supervised Learning (SimCLR, BYOL)** strategies to improve performance in data-scarce regimes (20% labeled data).

## 📊 Key Results

| **Model Strategy** | **Training Data** | **`mAP@0.5`** |
|---|---|---|
| **Baseline (YOLOv12n)** | 100% Labeled | **0.9765** |
| **Semi-SL (Pseudo-Labeling)** | 20% Labeled + Pseudo | 0.9656 |
| **Self-SL (SimCLR)** | Unlabeled Pre-train + 20% Fine-tune | 0.9609 |
| **Self-SL (BYOL)** | Unlabeled Pre-train + 20% Fine-tune | **0.9632** |

## 📂 Repository Structure

* `notebooks/`: Contains all experimental code (Baseline, Semi-SL, Self-SL).

* `results/`: Training curves and inference visualizations.

## 📓 Kaggle Notebooks
### Baseline Models
- [YOLOv12n Baseline](https://www.kaggle.com/code/sadikshahriar/license-plate-detection-yolov12-xai)
- [YOLOv11n Baseline](https://www.kaggle.com/code/mdmoonrahmannayem/license-plate-detection-yolov11-xai)
- [YOLOv10n Baseline](https://www.kaggle.com/code/tasnimjabir/license-plate-recognition-yolov10n)

### Semi-Supervised Learning
- [Pseudo-Labeling Pipeline](https://www.kaggle.com/code/sadikshahriar/cse-475-ssl-pseudo-labeling-license-plate)

### Self-Supervised Learning
- [SimCLR Pre-training](https://www.kaggle.com/code/sadikshahriar/phase-1-self-supervised-learning-simclr)
- [SimCLR Fine-tuning](https://www.kaggle.com/code/sadikshahriar/phase-2-fine-tuning-simclr)
- [BYOL Pre-training](https://www.kaggle.com/code/sadikshahriar/byol-pre-training)
- [BYOL Fine-tuning](https://www.kaggle.com/code/sadikshahriar/byol-fine-tuning)

## 🔗 Dataset

[Roboflow Universe: License Plate Recognition Dataset](https://universe.roboflow.com/roboflow-universe-projects/license-plate-recognition-rxg4e)

