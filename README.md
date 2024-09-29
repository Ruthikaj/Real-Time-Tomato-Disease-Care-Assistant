# Real-Time-Tomato-Disease-Care-Assistant
The Plant Disease Detection for Tomato Plants project employs a CNN model to achieve 94.77% accuracy in identifying diseases from  given images, significantly enhancing early detection and optimizing resource efficiency in agriculture.
Here’s a revised version of your project description with more realistic and relevant emojis:

---

# 🌱 **Real-Time Tomato Disease Care Assistant** 🍅

### **Team Members**
- **Janani A** - 21MIS0068
- **Ruthika J** - 21MIS0359

## **Project Overview**

This repository showcases a deep learning model employing Convolutional Neural Networks (CNNs) to accurately identify diseases affecting tomato plants. Our approach aims to improve early disease detection, thereby enhancing crop yield and promoting sustainable agricultural practices. 🚜🌾

### **Problem Statement**

Tomato diseases can drastically reduce crop yields and adversely affect farmers' incomes. Conventional detection methods are often inefficient and prone to inaccuracies, resulting in delayed interventions and greater losses. ⏳❌

### **Proposed Solution**

We propose a robust CNN model that facilitates real-time disease detection through webcam input and manual image uploads, providing a user-friendly experience for farmers and agricultural professionals. 📷👩‍🌾

### **Key Performance Metrics**

- **Accuracy**: 94.77% 🌟
- **Dataset Size**: 18,000+ images 📊
- **Disease Classes**: Multiple tomato plant diseases 🌿

## **Technical Stack**

- **Languages**: Python 🐍
- **Frameworks**: TensorFlow, Keras 🛠️
- **Image Processing**: OpenCV 🖼️
- **Web Framework**: Streamlit 🌐
- **Data Management**: Pandas, NumPy 📈
- **Visualization**: Matplotlib 📊
- **GPU**: NVIDIA RTX 2050 with CUDA 11.2, cuDNN 8.1 💻

## **Key Features**

- **Real-Time Detection**: Instant analysis of tomato leaves via webcam. 📹
- **Manual Upload**: Users can upload images for disease diagnosis. 📤
- **Comprehensive Insights**: Detailed information about detected diseases and treatment recommendations. 📝
- **Data Augmentation**: Increases dataset variability through techniques such as rotation, flipping, and zooming. 🔄

## **Installation Guide**

### **Prerequisites**

- Python 3.7 or higher 🐍
- NVIDIA GPU with CUDA 11.2 and cuDNN 8.1 🖥️

### **Setup Steps**

1. **Clone the Repository**:
   ```bash
   gh repo clone Ruthikajayaprakash/Real-Time-Tomato-Disease-Care-Assistant
   cd Real-Time-Tomato-Disease-Care-Assistant
   ```

2. **Create a Virtual Environment**:
   ```bash
   python -m venv venv
   source venv/bin/activate  # For Windows: venv\Scripts\activate
   ```

3. **Install Dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

4. **Dataset Preparation**:
   ```bash
   # Ensure the dataset is located in the `data` folder
   python src/data_preprocessing.py
   ```

5. **Model Training**:
   ```bash
   python src/train.py
   ```

6. **Model Evaluation**:
   ```bash
   python src/evaluation.py
   ```

7. **Launch Streamlit App**:
   ```bash
   streamlit run src/app.py
   ```

## **Evaluation Metrics**

- **Accuracy**: Proportion of correctly identified samples. ✅
- **Precision**: Ratio of true positive predictions to total predicted positives. 📈
- **Recall**: Ratio of true positives to actual positives. 🔍
- **F1 Score**: Harmonic mean of precision and recall. ⚖️


## **Contribution Guidelines**

Contributions are encouraged to enhance this project. Please follow these steps:

1. Fork the repository. 🍴
2. Create a new branch (e.g., `git checkout -b feature-branch`).
3. Commit your changes (e.g., `git commit -m 'Add new feature'`).
4. Push to the branch (e.g., `git push origin feature-branch`).
5. Open a pull request. 🔄

## **Acknowledgements**

- **Kaggle**: For the dataset. 📊
- **TensorFlow and Keras**: For the deep learning frameworks. ⚙️
- **Streamlit**: For the web framework. 🌍
- **OpenCV**: For image processing. 📸

