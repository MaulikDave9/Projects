**Computer Vision Application: Multi-class Image Classification on Fruits-360 Dataset**

Accurately classifying fruits and vegetables based on visual features like size, color, and shape has practical applications in agriculture and retail industries. This project implements deep learning techniques using CNN (baseline and enhanced variants) and Vision Transformer (ViT) models trained on the comprehensive Fruits-360 dataset (232 classes of high-quality fruit, vegetable, nut, and seed images). The CNN achieves ~94% and ViT ~98% test accuracy.

**Overview of Steps**

1. **Data Preparation**
   - Download Fruits-360 dataset from Kaggle to Colab (100x100 pixel images)
   - Explore dataset structure with folders organized by species/sub-types
   - Set up Training (~122K images) and Testing (~40.7K images) datasets

2. **Model Development**
   - Baseline CNN model
   - Enhanced CNN model
   - Vision Transformer (ViT) model

3. **Model Evaluation**
   - CNN: ~94% test accuracy
   - Vision Transformer: ~98% test accuracy

**Impact and Applications**
Digital agriculture benefits from automated fruit/vegetable classification for quality grading, sorting, and monitoring. This technology reduces labor costs, post-harvest losses, and improves supply chain efficiency while creating higher market value through better inventory management.

**Dataset**
Publicly available on Kaggle: Fruits-360 Dataset

**Technologies**
 -Development Environment: Colab Pro (L4 GPU)
 -Frameworks: TensorFlow, Keras, PyTorch

**Results**

| Model	            | Test Accuracy |
|-------------------|---------------|
| Baseline CNN      |	~97%          |
| Enhanced CNN      | ~94%          |
| Vision Transformer|	~98%          |

The models demonstrate strong generalization, robustness, and state-of-the-art performance on the real-world Fruits-360 test dataset.
