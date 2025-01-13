This repository contains the implementation of a two-stage deep learning (DL) framework for diabetic retinopathy (DR) detection and classification. The study leverages state-of-the-art convolutional neural networks (CNNs) to enhance diagnostic accuracy and efficiency in clinical settings.

🚀 Objective
To investigate the effectiveness of various CNN architectures for:

Binary classification: Distinguishing between healthy and DR-affected retinas.
Multi-class classification: Grading the severity levels of DR.
🧠 Methodology
Two-Stage Deep Learning Framework:
Stage 1: Binary Classification
Identifies whether a retina is healthy or DR-affected.
CNNs used:
DenseNet121
DenseNet169
DenseNet201
ResNet50
ResNet101
EfficientNet B0
EfficientNet B7
Inception V3
Stage 2: Multi-Class Classification
Grades the severity levels of DR for affected retinas.
Model ensembling techniques were applied to further improve prediction accuracy.
Evaluation Metric:
Accuracy was the primary metric to assess performance across all models.
📊 Results
Binary Classification:
EfficientNet B0 achieved 99.56% accuracy.
EfficientNet B7 achieved 99.53% accuracy.
Multi-Class Classification:
Model ensembling led to a significant accuracy of 98.74%.
✅ Conclusion
The proposed two-stage DL framework demonstrates the potential of CNNs in:

Ensuring accurate and efficient DR diagnosis.
Optimizing resources in clinical diagnostics.
Improving patient outcomes through early and precise detection.
