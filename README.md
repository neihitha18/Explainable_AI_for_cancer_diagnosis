# Explainable_AI_for_Cancer_diagnosis
The project focuses on classifying benign and malignant cells using neural networks. As neural networks are often considered black box models, the emphasis is on interpreting the causality behind the classification. The goal is to create an explainable model, addressing the interpretability challenge associated with neural networks.

# Problem Statement
Identifying benign or malignant cells is crucial for early diagnosis. Neural networks excel in classification but lack interpretability, reducing trust in AI-driven medical decisions. Traditional models offer transparency but less accuracy. This project develops an explainable neural network that classifies cells accurately while revealing key features influencing predictions.

# Research Objectives:
1. To develop a neural network model for classifying benign and malignant cells.
2. To assess the model’s performance using standard evaluation metrics.
3. To explore and implement explainable AI techniques for interpreting model predictions.
4. To enhance model transparency by identifying causality influencing classification.

# Methodology
<img width="413" alt="image" src="https://github.com/neihitha18/Explainable_AI_for_Breastcancer_diagnosis/assets/60841944/070e0515-3202-4edb-9114-d9478cc92b81">

# Data Analysis and pre-processing: 
Dataset used: https://web.inf.ufpr.br/vri/databases/breast-cancer-histopathological-database-breakhis/
It consists of 7909 microscopic images of Benign and Malignant cells. 
The basic pre-processing, Image Augmentation, Imbalance class handling is done.

<img width="444" alt="image" src="https://github.com/neihitha18/Explainable_AI_for_Breastcancer_diagnosis/assets/60841944/5459c976-a88d-446b-b790-7a5b352d55b3">

# Data splitting
The data is split into train, validate and test data in the ratio of 60:20:20. 
<img width="443" alt="image" src="https://github.com/neihitha18/Explainable_AI_for_Breastcancer_diagnosis/assets/60841944/3044fe60-edde-402c-b200-e1360b7b0a95">

# Model Building and Evaluation
A customised Convolution Neural Networks, ResNet50V2 and InceptionV3 models are built, trained, validated and finally tested against the test data. The evaluation results are as follows 

<img width="305" alt="image" src="https://github.com/neihitha18/Explainable_AI_for_Breastcancer_diagnosis/assets/60841944/3eb493a1-da46-43b8-acab-4bb92dbdfe41">

# Exaplainable AI
As ResNet model has outperformed the other two models, it is used to build a Explainable model which is implemented using LIME [Local Interpretable Model-agnostic Explanations] technique.

# LIME Heatmap - Malignant Samples:
<img width="639" alt="image" src="https://github.com/neihitha18/Explainable_AI_for_Breastcancer_diagnosis/assets/60841944/dfe099af-b14c-4e33-9dad-a38f68d21262">

<img width="633" alt="image" src="https://github.com/neihitha18/Explainable_AI_for_Breastcancer_diagnosis/assets/60841944/a0643180-c538-443e-a12f-a672f1a5c9dd">

# LIME Heatmap - Benign Samples: 
<img width="633" alt="image" src="https://github.com/neihitha18/Explainable_AI_for_Breastcancer_diagnosis/assets/60841944/bc04aef3-fa6a-4928-bf11-9f9919feaacb">

<img width="636" alt="image" src="https://github.com/neihitha18/Explainable_AI_for_Breastcancer_diagnosis/assets/60841944/19696136-9394-42ff-85ae-50d70df913d9">

# Conclusion 

The importance of this research becomes evident in its profound influence on diagnostic methodologies. Traditional models frequently prove inadequate, as they overlook crucial risk factors, resulting in inaccurate or delayed diagnoses. The incorporation of advanced deep learning models tackles these deficiencies, offering a meticulous and accurate diagnostic methodology. This progress not only heightens the precision and speed of diagnoses but also enables early detection. Furthermore, the focus on interpretability in the developed models contributes to a more comprehensive understanding of the diagnostic process, representing a substantial leap toward more dependable and efficient healthcare practices.





