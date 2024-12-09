# High Cost-Effect is All You Need to Prevent Wildfires

## Overview
This project addresses the lack of an affordable, high-performance model for rapid wildfire detection from images. By developing a cost-effective and lightweight computer vision model compatible with existing CCTV infrastructure, we aim to enhance early warning capabilities and resource accessibility in wildfire-prone areas.

## Motivation
Wildfires, intensified by climate change, pose severe risks to ecosystems, public health, and economies. Early and accurate detection can significantly mitigate these damages. However, current advanced detection systems are often expensive and complex. Our solution focuses on delivering a scalable, low-cost model that ensures reliable wildfire detection even in regions with limited resources or outdated camera systems.

## Dataset
We utilize a dataset of 2,700 aerial and ground-based RGB images sourced from public domain platforms. These images, categorized into fire (1,047) and no-fire (1,653), are split into training (70%), validation (15%), and testing (15%). The wide range of resolutions, forest types, and geographical conditions ensures robustness and adaptability of the resulting model.

## Methodology
1. **Model Selection:** Choose a low-parameter, high-accuracy architecture.
2. **Hyperparameter Tuning:** Optimize learning rate, regularization, and layer depth.
3. **Backbone Training:** Employ a pre-trained backbone for feature extraction, adapting it to varying environmental conditions.
4. **Validation:** Test under diverse real-world scenarios—different weather, times of day, and angles—ensuring stability, accuracy, and cost-effectiveness.

---

![Wildfire Detection Concept](https://user-images.githubusercontent.com/your-username/your-repo/assets/wildfire_detection_example.jpg)
