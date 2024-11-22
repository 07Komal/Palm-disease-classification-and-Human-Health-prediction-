# Palm-disease-classification-and-Human-Health-prediction-
A deep learning project for detecting palm leaf diseases using a CNN (MobileNetV2) model, with a Gradio interface for image-based disease prediction and analysis.
This project aims to classify diseases in palm leaves using deep learning techniques and analyze the potential health impacts on humans from consuming infected leaves. The solution leverages Convolutional Neural Networks (CNN) with a custom model architecture based on MobileNetV2 for effective and accurate disease detection in palm leaves. The project is developed in Python using Jupyter Notebook and VS Code.

Key Features
Disease Classification: Identifies diseases in palm leaves by classifying visible symptoms in leaf images.
Human Health Analysis: Evaluates potential health risks associated with each type of leaf disease, providing insights into possible health impacts from consuming infected leaves.
Gradio User Interface: Provides an interactive UI for users to upload palm leaf images and receive disease predictions.
Customizable Model: The model is trained on a custom dataset and can be adapted for various plant disease classification tasks.
Model Accuracy Improvement with Ensemble Techniques: Uses Nash Equilibrium and ResNet to train multiple models with different data splits and hyperparameters, enhancing overall model accuracy.
Technical Details
1. Data Collection and Preprocessing
ImageDataGenerator is used to load and preprocess the dataset for training.
Zipped datasets are handled efficiently using zip and unzip functions.
2. Model Architecture
Utilizes MobileNetV2 architecture for efficient disease detection in palm leaves.
Trained over 1000 epochs to optimize classification accuracy.
3. Disease Detection and Prediction
The model identifies disease-specific characteristics in the palm leaf image and provides a disease prediction.
Outputs the confidence level of each disease detected in the image.
4. Health Impact Analysis
Provides a secondary layer of analysis where potential health impacts of consuming infected leaves are analyzed and reported based on detected diseases.
5. User Interface (Gradio)
A Gradio interface allows users to upload images of palm leaves and view predictions.
The UI displays the original image, processed image with highlighted disease spots (using Grad-CAM), and the disease prediction result.
Displays accuracy metrics before and after processing for better understanding of model performance.
6. Troubleshooting and Model Improvement
Custom architecture and re-training methods are used to resolve issues with classification accuracy.
Fine-tuning and adjustments in data augmentation and model architecture are applied to improve the model’s ability to differentiate between diseases.
