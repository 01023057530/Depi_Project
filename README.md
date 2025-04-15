# Depi_Project 
# presentation via link: 
https://www.canva.com/design/DAGkh9gJ3kA/sjDrfkDbJhrGhWVzPZxMrQ/edit?utm_content=DAGkh9gJ3kA&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton

# 🗑️ Garbage Detection and Classification using YOLO

This project implements a real-time **Garbage Detection and Classification** system using the **YOLO (You Only Look Once)** object detection algorithm. The model identifies and classifies garbage into categories such as **Cardboard**, **Food Organics**, **Metal**, **Miscellaneous Trash**, **Paper**, **Plastic**, **Textile Trash**, **Cardboard**, and **Vegetation** to support waste sorting automation and environmental monitoring applications.

---
## 🚀 Dataset
https://www.kaggle.com/datasets/irkal123narayan456/realwaste-dataset?resource=download

---

## 🚀 Features

- Detects and classifies garbage in real-time.
- Trained on a custom dataset with labeled garbage types.
- Supports deployment on CPU, GPU, or edge devices.
- Visualizes bounding boxes and class labels.

---

## 🧠 Model Architecture

- **Model**: YOLOv5 (You can also use YOLOv7 or YOLOv8 based on your performance needs).
- **Framework**: Tensorflow, OpenCV, Sklearn, 
- **Classes**: 
  - `Cardboard` (e.g., food waste, leaves)
  - `Food Organics` (e.g., plastic bottles, paper)
  - `Glass` (e.g.,  bottles)
  - `Metal` (e.g., cans, aluminum foil)
  - `Miscellaneous Trash` (e.g., broken toys, ceramics)
  - `Paper` (e.g., newspapers, cardboard)
  - `Plastic` (e.g., bottles, food containers)
  - `Textile Trash` (e.g., old clothes, fabric scraps)
  - `Vegetation` (e.g., leaves, grass clippings)

 

---

## 📁 Folder Structure

data/
├── images/
│   ├── train/
│   ├── test/
│   └── val/

├── labels/
    ├── train/



    
    └── val/
