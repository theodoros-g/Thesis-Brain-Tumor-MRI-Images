# Thesis-Brain-Tumor-MRI-Images
Comparative study of CNN architectures (VGG16, ResNet50, EfficientNetB0, and a custom CNN) for brain tumor classification on MRI scans, integrating Grad-CAM explainability to evaluate diagnostic relevance and model interpretability.

About this Project

This repository contains the code and experiments developed as part of a Master’s Thesis in the Business Analytics and Data Science program at the University of Macedonia (Thessaloniki, Greece).
The study investigates the use of Convolutional Neural Networks (CNNs) for the automatic classification of brain tumors (glioma, meningioma, pituitary tumor, and no-tumor) based on MRI scans.

The project evaluates and compares four different CNN architectures:

VGG16, ResNet50, and EfficientNetB0, all leveraging transfer learning from ImageNet, and a Custom CNN, designed and trained from scratch to serve as a baseline model.

The objective of this work is to assess how architecture depth, transfer learning, and data augmentation techniques affect classification performance and interpretability in a medical imaging context.
To enhance explainability, the Grad-CAM (Gradient-weighted Class Activation Mapping) method was integrated, allowing visual interpretation of each model’s decision-making process.

Overall, this project aims to balance accuracy, interpretability, and computational efficiency, providing insights into how CNNs can support trustworthy AI applications in medical diagnostics.
