# Semi-Supervised and Self-Supervised Object Detection for License Plate Recognition

**Course:** CSE 475 - Machine Learning

**Semester:** Fall 2025

**University:** East West University

## 📌 Project Overview

This project investigates label-efficient object detection for Automatic License Plate Recognition (ALPR). We benchmark **YOLOv12** against **Semi-Supervised Learning (Pseudo-Labeling)** and **Self-Supervised Learning (SimCLR, BYOL)** strategies to improve performance in data-scarce regimes (20% labeled data).

## 👥 Group Members

| **Name** | **ID** |
|---|---|
| Md. Sadik Shahriar | 2023-2-60-103 |
| Jannatul Ferdous Nabila | 2022-3-60-198 |
| Md Moon Rahman Nayem | 2022-3-60-210 |
| Tasnim Jabir | 2022-3-60-283 |

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

## 🔗 Dataset

[Roboflow Universe: License Plate Recognition Dataset](https://universe.roboflow.com/roboflow-universe-projects/license-plate-recognition-rxg4e)

