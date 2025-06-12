# Brain-Tumor-Detection-DL
This project focuses on detecting brain tumors from MRI images using Convolutional Neural Networks (CNNs). Leveraging deep learning techniques, the model classifies whether an input image contains a brain tumor or not. The notebook includes image preprocessing, model training, evaluation, and predictions.

📂 Dataset
The dataset used for training and evaluation is obtained from Kaggle Brain Tumor Dataset, which consists of MRI images categorized into:
Tumor
No Tumor

 Technologies Used
Python
Jupyter Notebook
TensorFlow / Keras
OpenCV
Matplotlib, Seaborn
NumPy & Pandas
Scikit-learn

Project Workflow
Importing Libraries
All necessary libraries for image processing, model building, and visualization are imported.

Data Loading and Preprocessing
Images are resized, normalized, and augmented (if needed). Folder-based classification is done using image generators.

Model Architecture
A CNN-based deep learning model is built with layers such as Conv2D, MaxPooling, Flatten, and Dense.

Model Training
The model is compiled and trained on training data with validation monitoring.

Evaluation and Accuracy
Accuracy and loss curves are plotted. The trained model is evaluated using classification metrics.

Prediction on New Images
Sample test images are predicted, and results are visualized using matplotli
