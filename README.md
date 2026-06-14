# Rice-Leaf-Disease-Detection
This README is based on the documentation and project structure found in the source material for the **Rice Leaf Disease Detection** project.

***

# 🌾 Rice Leaf Disease Detection using Deep Learning

### 📌 Project Information
*   **Project Name:** Rice-Leaf-Disease-Detection
*   **Goal:** Develop a robust and scalable AI-based solution to detect rice leaf diseases early to help farmers reduce crop damage.

### 🔍 Problem Statement
Rice crops are frequently affected by leaf diseases that reduce grain quality and yield. Traditional detection methods are slow, require expert knowledge, and are not scalable. This project utilizes **Deep Learning** to automate the classification of these diseases from images.

### 📊 Dataset Details
The dataset consists of **119 total images** categorized into three major classes:
1.  **Bacterial Leaf Blight** (40 images)
2.  **Brown Spot** (40 images)
3.  **Leaf Smut** (39 images)

### 🛠 Technology Stack
*   **Deep Learning Framework:** TensorFlow / Keras
*   **Data Manipulation:** NumPy, Pandas
*   **Visualization:** Matplotlib, Seaborn
*   **Model Type:** Convolutional Neural Network (CNN)

### 🚀 Key Project Tasks
1.  **Data Analysis (EDA):** Visualization of class distributions and sample images to understand data characteristics and challenges.
2.  **Preprocessing:** Implementing resizing (255x255) and normalization (scaling pixel values to a 0–1 range) to ensure consistent model input.
3.  **Data Augmentation:** Used to overcome the small dataset size by applying random flips, rotations, and zooms to prevent overfitting.
4.  **Model Development:** A CNN architecture featuring multiple `Conv2D` and `MaxPooling2D` layers, followed by `Dense` layers and a `Softmax` output for 3-class classification.
5.  **Evaluation & Inference:** Generating accuracy and loss curves, and performing inference on unseen images to verify real-world performance.

### 📈 Model Performance
The model was trained over **85 epochs** using the **Adam optimizer** and **Sparse Categorical Crossentropy** loss. 
*   **Training Accuracy:** Reached high levels (approx. 97.5% in final epochs).
*   **Validation Accuracy:** Reached approx. 93.75%.
*   **Test Evaluation:** Achieved an accuracy of approximately **91.30%** on the test set.

### 📂 Final Deliverable
The project is contained within a single Jupyter Notebook that includes data analysis, model architecture, training logs, and an inference report. The final trained model is saved as `Plant_leaf_diseases_detection_model.h5`.
