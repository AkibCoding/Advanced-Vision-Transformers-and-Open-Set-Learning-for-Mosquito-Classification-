# Advanced-Vision-Transformers-and-Open-Set-Learning-for-Mosquito-Classification-
A dataset of 10 classes of mosquito trained on Resnet50, Xception, ViT, MobileViT, CVT-13, Swin-S and Swin-B. And openmax impementation on 5 of the best models

# Introduction
The classification of mosquito species is an important task in controlling and preventing mosquito-borne diseases. This study focuses on the application of various deep learning models for mosquito classification.

## Literature Review
Recent advancements in deep learning have shown promising results in image classification tasks. Transformer-based models, such as Vision Transformers (ViT) and Swin Transformers, have demonstrated superior performance compared to traditional convolutional neural networks (CNNs).

## Methodology
This section describes the dataset, preprocessing techniques, and models used in this study. The models include ResNet50, Xception, ViT, Swin-B, Swin-S, CVT-13, and MobileViT.

## Results
The performance of each model is evaluated based on various metrics, including accuracy, precision, recall, F1 score, and ROC-AUC.

| Model        | Training Accuracy | Validation Accuracy | Precision | Recall | F1 Score | ROC-AUC |
|--------------|-------------------|---------------------|-----------|--------|----------|---------|
| Resnet50     | 0.964             | 0.960               | 0.960     | 0.960  | 0.960    | 0.980   |
| Xception     | 0.984             | 0.983               | 0.983     | 0.983  | 0.983    | 0.991   |
| ViT Base     | 0.993             | 0.998               | 0.998     | 0.998  | 0.998    | 1.000   |
| Swin-B       | 0.990             | 1.000               | 1.000     | 1.000  | 1.000    | 1.000   |
| Swin-S       | 0.998             | 0.998               | 0.998     | 0.998  | 0.998    | 1.000   |
| CVT-13       | 0.954             | 0.950               | 0.950     | 0.950  | 0.950    | 0.976   |
| MobileViT    | 0.974             | 0.972               | 0.972     | 0.972  | 0.972    | 0.986   |

## Discussion
This section discusses the results of the experiments, focusing on the performance of different models and the impact of the OpenMax technique.

## Conclusion
This study presents a comprehensive analysis of different models for classifying mosquito species. Transformer-based models, particularly Swin-B and Xception, outperformed other models in terms of accuracy and robustness.
