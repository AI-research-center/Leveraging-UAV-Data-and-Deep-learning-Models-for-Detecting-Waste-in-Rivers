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
```
river/
├── bagmati/
│   ├── image/
│   ├── label/
│   └── mask/
├── bishnumati/
│   ├── image/
│   ├── label/
│   └── mask/
```
## 🏷️ Citation
If you find this useful in your research, please consider cite:
```
@ARTICLE{11021562,
  author={Man Pati, Bipun and Khadka, Bishnu and Thapa, Ukesh and Kumar Pal, Sujay and Sakya, Subarna and Shrestha, Anup and Joshi, Hemant and Pyakurel, Dhiraj and Chandra Roy, Prem},
  journal={IEEE Access}, 
  title={Leveraging UAV Data and Deep Learning Models for Detecting Waste in Rivers}, 
  year={2025},
  volume={13},
  number={},
  pages={99603-99627},
  keywords={Rivers;Object detection;Training;Transfer learning;Data models;Autonomous aerial vehicles;Accuracy;Measurement;Deep learning;Transformers;Deep learning;object detection;Nepali river;segmentation;comparison;transfer learning;uncrewed aerial vehicle (UAV);environmental monitoring;floating plastic;solid waste},
  doi={10.1109/ACCESS.2025.3576295}}

```
