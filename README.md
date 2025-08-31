🌿 Plant Disease Detection using Custom CNN, Hybrid Models, and Pre-trained CNNs

This project presents a comprehensive study of plant disease classification using deep learning and machine learning techniques. It explores baseline Custom CNNs, CNN feature extraction with classical ML classifiers, CNN with attention mechanisms, and transfer learning with pre-trained CNNs. The goal is to achieve high accuracy, balanced performance, and efficient inference for real-world agricultural applications.

📂 Dataset

The dataset used in this project is the publicly available PlantVillage dataset (Kaggle).

Dataset: PlantVillage – Crop Disease Recognition

Local Path Used: /kaggle/input/plantvillage-dataset/ or balanced subset /kaggle/working/plantvillage-balanced/

Classes: 38 crop–disease categories (e.g., Apple Scab, Grape Black Rot, Tomato Late Blight, etc.)

Balanced Dataset: 350 images per class (to reduce bias)

Dataset Split:

Train: 70%

Validation: 20%

Test: 10%

🧠 Model Architectures

We experimented with a range of architectures to identify the most effective approach for plant disease detection.

✅ Models Implemented

Baseline CNN: Custom CNN built from scratch as a performance baseline.

Hybrid CNN + ML Classifiers: CNN feature extraction with classifiers including SVM, kNN, Random Forest, and XGBoost.

CNN with Attention: Enhanced Custom CNN with attention layers for better interpretability.

Pre-trained CNNs (Transfer Learning):

ResNet50

VGG16

MobileNetV2

GoogLeNet

Custom CNN with Ensemble Stacking (Best Model): Combines multiple CNN outputs with ML meta-classifiers for superior accuracy.

📊 Results Summary

Best Accuracy: Custom CNN with Ensemble Stacking (~99%)

Pre-trained Models: Competitive results (95–97%) but slightly weaker than the ensemble.

Hybrid Models: Strong performance (~97–98%) with diverse classifiers.

Robustness: Ensemble + Attention achieved balanced performance across classes.

Grad-CAM: Used for model explainability and disease focus visualization.

🚀 Future Work

Real-time deployment on mobile devices for in-field plant disease detection.

Extending the system to handle multi-disease and multi-leaf input.

Integration with IoT-based smart agriculture platforms.
