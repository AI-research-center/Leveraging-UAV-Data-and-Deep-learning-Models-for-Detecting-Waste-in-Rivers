# Leveraging-UAV-Data-and-Deep-learning-Models-for-Detecting-Waste-in-Rivers
## River Waste Dataset – Bagmati & Bishnumati

This project focuses on environmental monitoring of two major rivers in Kathmandu, Nepal — **Bagmati** and **Bishnumati**. Using drone-captured aerial imagery, we have constructed a dataset aimed at detecting and segmenting river waste.

- The dataset is publicly available here:  
  🔗 **[Google Drive – River Waste Dataset](https://drive.google.com/drive/folders/1LEkgIOoVGfa1YEH7OT3BmpEzrozNPNeo)**

### 📁 Dataset Structure

The dataset is organized by river name, with each folder containing:
- `image/` — raw drone images
- `label/` — object detection annotations (e.g., bounding boxes)
- `mask/` — segmentation masks for waste regions
'''
river/ 
├── bagmati/
│ ├── image/
│ ├── label/
│ └── mask/
├── bishnumati/
│ ├── image/
│ ├── label/
│ └── mask/
'''
