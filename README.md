

<h1> <p style="text-align: center";>  <B> Hand written digit analysis </B>  

### About Project 👨‍💻

- The Handwritten Digit Recognition project focuses on training a machine learning model to identify digits (0–9) from images of handwritten numbers.
- The dataset used in this project is the MNIST dataset, which consists of 28x28 pixel grayscale images representing handwritten digits.

- The project follows the typical supervised learning pipeline where:

- Data preprocessing is done to prepare the dataset for training.
  
- Various machine learning algorithms are applied to train the model.
  
- The model's performance is evaluated on a test set.
  
- Optimizations are made to improve the model's accuracy.
  
## Key Steps in the Project:
- Data Collection:Loaded the MNIST dataset (60,000 training and 10,000 test images of handwritten digits).
  
- Data Preprocessing:
Normalized pixel values (scaled to [0, 1]).
Flattened images into 1D arrays (784 features).
Split the data into training and test sets.

- Exploratory Data Analysis (EDA):Visualized sample images and checked label distribution.
  
- Model Training:Trained models using Random Forest,SVM,Decision Tree.
  
- Model Evaluation:Evaluated models on accuracy, precision, recall, F1-score.
  
### Algorithms Used:

The following machine learning algorithms were used in this project to classify the tumors as malignant or benign:

- Random Forest
  
- Support Vector Machine

- Decision Tree
  
###  Outcome:

- The accuracies obtained by the above algorithms are as follows:

- Random forest — 97%

- Support Vector Machines — 98%

- Decision Tree - 85%
