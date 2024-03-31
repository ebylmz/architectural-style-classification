# 🏛️ Architectural Style Classification

## 📄 Abstract

This study presents a versatile approach integrating various neural network architectures with a focus on classifying architectural works. To address the lack of suitable datasets in the literature, a custom dataset has been created and made publicly available. The study aims to determine the most effective model, taking into account fine details in architectural styles. In this context, a comparative analysis has been conducted on four different convolutional neural network (CNN) architectures, including a baseline model trained from scratch and models using transfer learning methods with VGG, ResNet, and EfficientNet architectures. Through experiments, the EfficientNet architecture was fine-tuned, achieving an accuracy of \%84.65 for 3 architects and \%74.08 for 16 architects. Additionally, the two obtained models were used as feature extractors to visualize relationships among architects in a 2D space using t-SNE dimension reduction technique. These promising results indicate that these techniques can significantly contribute to architectural style analysis and serve as valuable tools for creating innovative designs through the use of generative artificial intelligence. For additional details, please refer to the project [report](https://github.com/ebylmz/architectural-style-classification/tree/main/doc/report.pdf).

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

## 🎥 Video Explanation
[Watch the Video Explanation](https://youtu.be/Z_Q1FndZVKA)

## 📚 Source Code
All code is available in the Jupyter notebook [classify_arch.ipynb](https://github.com/ebylmz/architectural-style-classification/blob/main/notebooks/classify_arch.ipynb).

## 🔮 Future Work
1. **Enhance the Dataset:** Integrate more architectural datasets to improve generalization.
2. **Explore Advanced Architectures:** Investigate models with Transformer and attention mechanisms for further innovation.
3. **Generative AI and Practical Application:** Apply the trained model to support architects in design processes while exploring connections with generative AI.
