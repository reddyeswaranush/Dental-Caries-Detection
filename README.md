# 🦷 Dental Caries Detection using YOLOv8

This project focuses on detecting dental caries from intraoral dental images using deep learning–based object detection.

The aim is to build an automated system that can highlight potential carious regions and assist dentists in early diagnosis.

---

## Dataset

- Dataset: Roboflow Dental Caries Detection.v1i
- Format: YOLOv8
- Number of classes: 1  
- Class name: caries

All labels were converted into a single class for binary detection.

---

## Model Details

- Model: YOLOv8m
- Framework: Ultralytics YOLOv8
- Image size: 1024 × 1024
- Optimizer: AdamW
- Batch size: 12
- Epochs: 150
- Platform: Kaggle Notebook (GPU)

---

## Training Configuration

- Pretrained COCO weights
- Mosaic augmentation enabled
- High-resolution training for small lesion detection
- Single-class object detection

---

## Results

| Metric | Value |
|------|------|
| Precision | 0.74 |
| Recall | 0.59 |
| mAP@50 | **0.66** |
| mAP@50–95 | 0.28 |

---

## Sample Outputs

Prediction results and evaluation plots are available in the `results/` folder:

- Precision–Recall curve
- F1 curve
- Confusion matrix
- Sample predictions

---

## Project Structure
