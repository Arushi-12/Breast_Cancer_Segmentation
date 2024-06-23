# Breast Cancer Segmentation using Ensemble Learning

This project improves breast cancer image segmentation through a multi-step approach involving data preprocessing, classification, and ensemble-based segmentation. The dataset was preprocessed and classified using the VGG model into tumorous and non-tumorous images. Five segmentation models—UNet, Attention UNet, Residual UNet, SegNet, and DeepLab—were evaluated, with DeepLab showing the best performance.

Ensemble learning was used to combine multiple models, significantly improving results. The best ensemble, combining DeepLab and Attention UNet, achieved a Mean IoU of 0.876 and a Mean Dice coefficient of 0.932.

The dataset consists of 780 breast ultrasound images from 600 women aged 25 to 75, collected in 2018, categorized into normal, benign, and malignant.
