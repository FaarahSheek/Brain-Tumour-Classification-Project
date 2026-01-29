# Automated Brain Tumor Classification via CNNs
### Overview:


This project classifies MRI brain scans into four categories using a convolutional neural network (CNN):

- Glioma Tumor
- Meningioma Tumor
- No Tumor
- Pituitary Tumor
  
 The model assists in brain tumor diagnosis by identifying the type of tumor present in MRI images.

 ### Commonly asked questions
1. What is the objective of this project?

Answer:
The objective is to automatically classify brain MRI images into four categories—Glioma Tumor, Meningioma Tumor, Pituitary Tumor, and No Tumor—using a convolutional neural network (CNN) to assist in brain tumor diagnosis.

2. How can this project be improved?

Possible improvements include:
- Using transfer learning (e.g., VGG16, ResNet, EfficientNet)
- Increasing dataset size
- Applying advanced preprocessing techniques
- Adding explainability methods like Grad-CAM
- Hyperparameter tuning for better accuracy

### Project Structure

 **Notebook:** AutomatedBrainTumorClassificationviaCNNs.ipynb - all code from data processing to evaluation.
 
**README.md:** Project instructions and documentation.

### Key Steps
 Data Preprocessing: Images are augmented and loaded from Train and Test directories for each class.
 Model Architecture: A CNN with convolutional, max-pooling, and dropout layers for multi-class classification.
 Training & Evaluation: Model performance is visualized using accuracy/loss plots and a confusion matrix.
 Testing: Predicts tumor types on new images to verify real-world applicability.

## Results
 Plots and a confusion matrix provide insights into model performance.
