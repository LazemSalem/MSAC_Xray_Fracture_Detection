

# Smart Bone Fracture Detection Using MSAC-Xray

Official implementation of the research paper: **"Smart Bone Fracture Detection Using MSAC-Xray: Multi-Stage Adaptive Contrast Enhancement for Bone Fracture Classification in Degraded X-Ray Images via Transfer Learning"**.

## 📌 Overview
Emergency and resource-limited clinical X-ray images often suffer from noise, motion blur, and uneven illumination, which obscure fine fracture lines and degrade deep learning performance. To overcome this, **MSAC-Xray** introduces a four-stage adaptive preprocessing pipeline:
1. **Gaussian Background Correction:** Corrects uneven lighting and removes dark background shadows.
2. **MAD-Based Noise Estimation:** Dynamically calculates noise levels to set optimal enhancement parameters.
3. **Adaptive CLAHE:** Enhances local contrast to reveal subtle fracture lines.
4. **Bilateral Filtering:** Smooths residual noise while preserving sharp bone edges.

## 🚀 Quick Run in Google Colab
You can test and reproduce the complete pipeline directly in your browser:
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](أضف_رابط_ملف_الكود_هنا)

## 🧠 Evaluated Deep Learning Backbones
- **DenseNet121**
- **ResNet50**
- **MobileNetV2**

## 📊 Repository Structure
- `MSAC_Xray_Fracture_Detection.ipynb`: Complete Python pipeline containing synthetic data generation, MSAC-Xray preprocessing, model training, and performance evaluation.

## 📄 Citation
If you use this code or methodology in your research, please cite:
> Lazm Milad Salem (2026). Smart Bone Fracture Detection Using MSAC-Xray. College of Computer Technology, Tripoli, Libya.
