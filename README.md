# 🏛️ Architectural Style Classification

## 📄 Abstract

This research explores architectural styles from the late Ottoman and early Republican periods using advanced neural network architectures. The study aims to classify architects and visualize their relationships, introducing a curated dataset customized for architectural intricacies. Rigorous analysis of four key convolutional neural network (CNN) models—baseline, VGG, ResNet, and EfficientNet—reveals EfficientNet as the most effective model. EfficientNet achieves high accuracy on both Architects-Top and Architects-All datasets. Beyond classification, the research employs t-SNE dimension reduction to unveil hidden connections between architects, providing a deeper understanding of their distinctive styles. For additional details, please refer to the project [report](https://github.com/ebylmz/architectural-style-classification/tree/main/doc/report.pdf).

## 🌐 Research Objectives
The primary goal is to understand the evolution of architectural styles during the specified historical periods. The study delves into the distinctive styles of architects who played key roles in shaping the First and Second National Architectural Movements.

## 📊 Datasets and Models on Hugging Face
![Dataset Preview](https://github.com/ebylmz/architectural-style-classification/blob/main/doc/dataset.png)

- **Architects-All Dataset:** [Hugging Face - Architects-All Dataset](https://huggingface.co/datasets/ebylmz/architects)
- **Architects-Top Dataset:** [Hugging Face - Architects-Top Dataset](https://huggingface.co/datasets/ebylmz/architects-top)
- **Trained Models:** [Hugging Face - Trained Models](https://huggingface.co/ebylmz/architects-models)

## 🏆 Achievements
- Architects-Top Dataset Accuracy: 84.65%
- Architects-All Dataset Accuracy: 74.08%
- 0.43 silhouette score for the clustering
  
![Model Top Clustering](https://github.com/ebylmz/architectural-style-classification/blob/main/doc/model_top_clustering.png)

## 📚 Source Code
All code is available in the Jupyter notebook [classify_arch.ipynb](https://github.com/ebylmz/architectural-style-classification/blob/main/notebooks/classify_arch.ipynb).

## 🔮 Future Work
1. **Enhance the Dataset:** Integrate more architectural datasets to improve generalization.
2. **Explore Advanced Architectures:** Investigate models with Transformer and attention mechanisms for further innovation.
3. **Generative AI and Practical Application:** Apply the trained model to support architects in design processes while exploring connections with generative AI.
