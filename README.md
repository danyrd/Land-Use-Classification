# Land-Use Classification (COMP534)

This project explores various deep learning approaches to classify aerial scene images, as part of the COMP534 module at the University of Liverpool.

---

### 🚀 Key Features

* **Custom CNN Implementation**: Developed a convolutional neural network from scratch to understand the fundamentals of CNN architecture.
* **Transfer Learning**: Implemented and fine-tuned pre-trained models such as ResNet and VGG to leverage powerful existing architectures.
* **Data Augmentation**: Used techniques like rotation, flipping, and scaling to expand the dataset and improve model robustness.
* **K-Fold Cross-Validation**: Employed k-fold cross-validation to ensure reliable performance evaluation and prevent overfitting.

### 📁 Dataset

* **Name**: UCMerced Land-use Dataset
* **Description**: A collection of 2100 aerial scene images, divided into 21 distinct land-use classes (e.g., agricultural, forest, river).

### 📈 Results & Evaluation

The models were trained and evaluated on key metrics to compare performance:
* **Accuracy**: Overall classification accuracy.
* **F1-Score**: A measure of a model's accuracy on the dataset, especially useful for imbalanced classes.
* **Confusion Matrix**: A detailed breakdown of the model's predictions, showing correct and incorrect classifications for each class.

I compared the performance of the custom-built CNN with the fine-tuned and feature-extracted models from ResNet and VGG, showcasing the benefits of transfer learning.

---

### 🛠️ Technologies Used

* Python
* TensorFlow / Keras
* NumPy
* Scikit-Learn
* Matplotlib
