# ENHANCING-SUGARCANE-LEAF-DISEASE-PREDICTION-MODEL-USING-DENSENET
Deep learning-based system using DenseNet201 to detect sugarcane leaf diseases with 91% accuracy. Includes web app for real-time predictions to support precision agriculture.

# Sugarcane Leaf Disease Detection using DenseNet201  

## Overview  
Sugarcane crops are vulnerable to leaf diseases that can reduce yield and crop quality. This project presents a **deep learning-based detection system** using **DenseNet201**, achieving **91% accuracy** in classifying healthy vs. diseased leaves. The solution is deployed as a **cloud-hosted web application**, enabling real-time disease diagnosis for farmers and agricultural researchers.  

## Features  
- **Automated disease detection:** Classifies sugarcane leaves as healthy or diseased.  
- **Advanced preprocessing:** Uses CLAHE and homomorphic filters to enhance image quality.  
- **Automated segmentation:** Focuses on infected regions for improved accuracy.  
- **High-performance model:** DenseNet201 for efficient and accurate feature extraction.  
- **Data augmentation:** Improves model robustness and prevents overfitting.  
- **Web application:** Upload leaf images for instant predictions via a user-friendly interface.  
- **Cloud deployment:** Scalable and easily accessible for real-world use.  

## Tech Stack  
- **Deep Learning Framework:** TensorFlow / Keras  
- **Model Architecture:** DenseNet201  
- **Image Processing:** CLAHE, homomorphic filtering, segmentation  
- **Web Framework:** Flask / Django (specify your framework)  
- **Deployment:** Cloud server (AWS, Azure, or GCP — specify if applicable)  
- **Programming Language:** Python  

## System Workflow  
1. **Data Collection:** Gather healthy and diseased sugarcane leaf images.  
2. **Image Preprocessing:**  
   - Apply CLAHE and homomorphic filtering for contrast and lighting correction.  
   - Perform automated segmentation to highlight diseased regions.  
3. **Model Training:**  
   - Train DenseNet201 with augmented dataset.  
   - Achieve ~91% accuracy in classification.  
4. **Deployment:**  
   - Integrate trained model into a web app.  
   - Host application on a cloud server for scalability.  
5. **Prediction:**  
   - Users upload leaf images.  
   - System provides real-time disease detection results.  

## Results  
- **Classification Accuracy:** 91%  
- **Fast Inference:** Optimized for real-time use in the field.  
- **Outperforms traditional methods** in both speed and accuracy.  

## Applications  
- Early detection of sugarcane leaf diseases.  
- Timely intervention and treatment planning.  
- Improved crop yield and quality.  
- Supports precision agriculture and sustainable farming practices.  

## Future Improvements  
- Expand to detect multiple disease types.  
- Add support for mobile applications.  
- Enhance explainability with heatmaps (Grad-CAM).  
- Integrate with IoT-based farm monitoring systems.  
