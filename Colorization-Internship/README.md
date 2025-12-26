# Colorization Internship Project

## **Project Overview**
This project is an extension of my NullClass training project, implementing advanced image colorization techniques. The unified pipeline includes:

1. Artistic Style Transfer
2. Historical Photo Colorization
3. Conditional (User-Controlled) Colorization
4. Dataset Augmentation
5. Semantic Segmentation Colorization
6. Real-Time Video Colorization

All tasks are implemented in **Google Colab**, leveraging PyTorch, OpenCV, and Deep Learning architectures like U-Net and DeepLabV3.

---

## **Problem Statement**
Grayscale images lose rich color information. The goal is to **automatically generate realistic or stylized color images**, preserve historical accuracy, allow user-guided hints, and process live video streams.

---

## **Dataset**
- **Natural Images:** 50+ images from Picsum (grayscale + color)
- **Historical Images:** 1920s and WWII archival images
- **Augmented Images:** Rotations, flips, brightness, noise applied

> *Note: Large datasets can be downloaded using provided scripts in the notebook.*

---

## **Methodology**
- **Task 1:** U-Net + AdaIN for artistic style transfer
- **Task 2:** Fine-tune U-Net for historical photo colorization
- **Task 3:** Conditional colorization using user-provided color hints
- **Task 4:** Dataset augmentation to improve model performance
- **Task 5:** Semantic segmentation via DeepLabV3 for targeted colorization
- **Task 6:** Real-time video frame colorization using optimized pipelines

---

## **Installation**
```bash
# Clone the repo
git clone <your-repo-link>
cd Colorization-Internship

# Install dependencies
pip install -r requirements.txt
