## Chest X-Ray Medical Diagnosis with CNN & DenseNet
This project utilizes Convolutional Neural Networks (CNNs) and the DenseNet architecture to perform binary classification (Normal vs Pneumonia) on chest X-ray images. The model is trained on the Chest X-Ray Images (Pneumonia) dataset to assist in automated medical diagnosis.

#### 🧠 Project Objective
To build and evaluate a deep learning model that can classify chest X-rays as:

Normal

Pneumonia

using a fine-tuned DenseNet121 model for high performance and accuracy.

#### 📂 Dataset
The dataset used is Chest X-Ray Images (Pneumonia) available on Kaggle:

Training Set

Normal

Pneumonia

Validation Set

Test Set

#### 🏗️ Model Architecture
Pretrained DenseNet121 from torchvision.models

Modified final fully-connected layer for binary classification

Loss Function: BCELoss (Binary Cross Entropy)

Optimizer: Adam

Evaluation Metrics: Accuracy, Precision, Recall, F1 Score

#### 🛠️ Key Features
Data preprocessing using torchvision transforms

Transfer learning using pretrained DenseNet121

Training loop with validation phase

Evaluation on test data with confusion matrix and classification report

Visualization of predictions

#### 🚀 How to Run
Clone the repository or download the notebook.

Download the dataset from Kaggle and unzip into the working directory under a folder named chest_xray/.

###### Install dependencies:

bash
Copy
Edit
pip install torch torchvision matplotlib seaborn scikit-learn
Run the notebook:

csharp
Copy
Edit
chest-x-ray-medical-diagnosis-with-cnn-densenet.ipynb
#### 📊 Results
Achieved high test accuracy.

Model effectively distinguishes between normal and pneumonia X-rays.

Includes visualization of correct and incorrect predictions.

#### 📈 Sample Output
Confusion Matrix

ROC Curve

Classification Report

#### 📌 Future Improvements
Apply data augmentation for improved generalization

Multi-class classification (bacterial vs viral pneumonia)

Integration with medical image explainability tools (Grad-CAM)

#### 🤝 Acknowledgements
Dataset by Paul Mooney (Kaggle)

Pretrained DenseNet121 model from PyTorch

Inspiration from Stanford’s CheXNet paper

