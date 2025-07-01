# SkinCancer
Skin Cancer Image Classification with Transformers
Project Overview
This project focuses on building and training an image classification model to classify skin lesions, leveraging the powerful transformers library from Hugging Face. The goal is to develop a robust model capable of accurately identifying different types of skin conditions, with a particular emphasis on handling potential class imbalance through a custom weighted loss function.

Features
Image Classification: Utilizes state-of-the-art transformers models for image classification tasks.

Weighted Loss Training: Incorporates a custom WeightedLossTrainer to address class imbalance issues by applying specific weights during loss calculation.

Comprehensive Metrics: Evaluates model performance using Accuracy, F1-Macro, and F1-Weighted scores, providing a holistic view of the model's effectiveness across all classes.

Mixed Precision Training (FP16): Leverages fp16 for faster training and reduced memory consumption.

Hugging Face Hub Integration: Configured to push the trained model directly to the Hugging Face Model Hub for easy sharing and deployment.

TensorBoard Logging: Integrates with TensorBoard for detailed logging and visualization of training progress and metrics.
