# 🔆 High-Dynamic-Range-Image-Reconstruction

🔗 🌐 **Open Project in Your Browser**: https://arrao10.github.io/High-Dynamic-Range-Image-Reconstruction/

### 📖 **Introduction**: 
**High Dynamic Range (HDR)** imaging originated in photography and computer graphics to overcome the limitations of standard imaging techniques. Early HDR methods involved manual blending of multiple exposures, but modern approaches use advanced algorithms and deep learning for automated enhancement. **Convolutional Neural Networks (CNNs)** with Deep Learning Techniques are used nowadays to learn the complex mapping between exposure inputs and automatically extracting and combining features, thereby reducing the image quality and making it suitable for real world applications in photography, surveillance, defense and computer vision.

### 🎯 **Problem Statement**:
To train a Deep Learning CNN model which combines images of the same scene with different exposure levels to create a composite High Dynamic Range (HDR) image with enhanced contrast, improved color depths, and greater detail and highlights.

### 🌟 **Impact**:
HDR image overcomes exposure limitations, capturing a more detailed and visually balanced image.

### 📂 **Dataset Details**: 
* **Total Images**: **400** photos captured using a mobile camera. <br>
* **Format**: All images are in **.jpg** format to maintain uniformity.
- **Synthetic Modification**:
  - **Underexposed images** → Darker with fewer pixel details.
  - **Overexposed images** → Brighter with increased pixel values.
  - Both are generated from the same Ground Truth images using **Python**
* **Resolution**: All images are uniformly resized to **384 × 384 pixels**.
* **Data Composition**: Ground Truth Images, Synthetically Modified Underexposed Images and Synthetically Modified Overexposed Images.

### 🧮 **Loss Functions Used**:
A combination of: **RGB-L1 Loss**, **Luminance-L1 Loss**, **Multi-Scale Structural Similarity Index Measure (MS-SSIM) Loss**, **Color Preservation (Chroma) Loss** and **Soft Histogram Matching Loss**.
