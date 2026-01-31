# Automated Brain Tumor Classification via CNNs
#### Description:

This project focuses on performing Exploratory Data Analysis (EDA) on GlobalMart’s sales data to better understand business performance across product categories, regions, and time periods.

#### Motivation:
The motivation behind this project was to gain hands-on experience analysing real-world business data and extracting meaningful insights that can support strategic decision-making.

#### Why this project was built:
The project was built to explore how sales, profit, discounts, and seasonality interact, and to identify patterns that could help improve pricing strategies, regional targeting, and overall performance.

#### Problem it solves:
It helps transform raw sales data into actionable insights by identifying trends, relationships, and areas of strength or concern within the business.

#### What I learned:
Through this project, I learned how to clean and explore datasets, perform time-based analysis, visualise data effectively, and interpret results from a business perspective.


## Overview:


This project classifies MRI brain scans into four categories using a convolutional neural network (CNN):

- Glioma Tumor
- Meningioma Tumor
- No Tumor
- Pituitary Tumor
  
 The model assists in brain tumor diagnosis by identifying the type of tumor present in MRI images.

 ### Commonly asked questions
1. Can the model predict on new MRI images?

Yes. The trained model can take a new MRI image as input and predict the tumor category, making it suitable for testing on unseen real-world data.

2. How can this project be improved?

Possible improvements include:
- Using transfer learning (e.g., VGG16, ResNet, EfficientNet)
- Increasing dataset size
- Applying advanced preprocessing techniques
- Adding explainability methods like Grad-CAM
- Hyperparameter tuning for better accuracy

3. Why use CNNs for brain tumor classification?

CNNs are highly effective for image-based tasks because they:
- Automatically extract spatial features from images
- Capture patterns like edges, shapes, and textures
- Perform well on medical imaging tasks such as MRI analysis
- This makes them ideal for detecting subtle tumor characteristics in brain scans.

### Project Structure

 **Notebook:** AutomatedBrainTumorClassificationviaCNNs.ipynb - all code from data processing to evaluation.
 
**README.md:** Project instructions and documentation.

### Installation:

Step 1: Clone the repository:
- git clone <repository-url>


Step 2: Navigate to the project directory.

Step 3: Install the required Python libraries:
- pip install pandas numpy matplotlib seaborn statsmodels


Step 4: Ensure the Global_Superstore.csv dataset is in the project directory.

Step 5: Open the Jupyter Notebook to run the analysis.

### Key Steps
 1. Data Preprocessing: Images are augmented and loaded from Train and Test directories for each class.
 2. Model Architecture: A CNN with convolutional, max-pooling, and dropout layers for multi-class classification.
 3. Training & Evaluation: Model performance is visualized using accuracy/loss plots and a confusion matrix.
 4. Testing: Predicts tumor types on new images to verify real-world applicability.

## Results
 Plots and a confusion matrix provide insights into model performance.
