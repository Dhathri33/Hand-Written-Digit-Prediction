# **Handwritten Digit Recognition Using Machine Learning**  

🚀 **A Deep Learning-based handwritten digit recognition system using Convolutional Neural Networks (CNN) with TensorFlow & Keras**  

## **Overview**  
This project focuses on building an **image classification model** to recognize handwritten digits (0-9) from the **MNIST dataset** using **Convolutional Neural Networks (CNNs)**. The model is trained to classify digits with **high accuracy** and is optimized for fast inference on low-memory devices.  

## **Project Workflow**  
### 🔹 **Data Collection & Preprocessing**  
- Used the **MNIST dataset** containing **70,000 images** (60,000 for training, 10,000 for testing).  
- Resized all images to **28x28 pixels** and **grayscale** for standardization.  
- Normalized pixel values to **[0,1]** for better convergence.  
- Applied **one-hot encoding** for digit classification.  

### 🔹 **Model Development & Training**  
- Designed a **CNN architecture** with:  
  - **Convolutional layers** for feature extraction.  
  - **Max-Pooling layers** for dimensionality reduction.  
  - **Fully Connected (Dense) layers** for classification.  
- Trained on **60,000 labeled images**, validated with **10,000 test images**.  
- Optimized performance using **Adam Optimizer** and **Categorical Crossentropy loss**.  

### 🔹 **Deployment & Web Integration**  
- **Converted Keras model to TensorFlow.js** format for web-based predictions.  
- Built an **HTML + JavaScript frontend** to allow users to draw digits and receive real-time predictions.  

### 🔹 **Evaluation & Results**  
| Metric | CNN Model |  
|--------|----------|  
| **Training Accuracy** | **98.7%** |  
| **Test Accuracy** | **98.1%** |  
| **Loss Function** | Categorical Crossentropy |  

## **Technologies Used**  
✅ **Deep Learning**: TensorFlow, Keras  
✅ **Programming Languages**: Python, JavaScript  
✅ **Data Processing**: NumPy, Pandas, OpenCV  
✅ **Frontend Deployment**: HTML, CSS, JavaScript, TensorFlow.js  
✅ **Model Evaluation Metrics**: Accuracy, Loss, Precision, Recall  
