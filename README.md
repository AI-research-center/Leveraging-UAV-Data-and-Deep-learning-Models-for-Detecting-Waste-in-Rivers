# Leveraging-UAV-Data-and-Deep-learning-Models-for-Detecting-Waste-in-Rivers
## River Waste Dataset – Bagmati & Bishnumati

This project focuses on environmental monitoring of two major rivers in Kathmandu, Nepal — **Bagmati** and **Bishnumati**. Using drone-captured aerial imagery, we have constructed a dataset aimed at detecting and segmenting river waste.
- 📄 Access the paper here::
  - 🔗 **[IEEE Access - Document 11021562](https://ieeexplore.ieee.org/document/11021562)**  

## Dataset Access
The dataset is available upon request. To gain access, please review and sign the [Terms of Usage](./TERMS_OF_USAGE.pdf) and email it to the corresponding author.

### How to Request Access:
1. Download and review the [Terms of Usage](./TERMS_OF_USAGE.pdf).
2. Sign the Terms of Usage.
3. Email the signed form to the corresponding author.
   - We encourage using your **official organization email** (e.g., university or research institute email) for verification purposes.
4. Once reviewed, access will be provided to the email address used for your request.

By submitting your request, you agree to the Terms outlined in the PDF document.


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
