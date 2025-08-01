## 🐱🐶 Cat vs Dog Image Classifier using SVM (Support Vector Machine)
This project uses a Support Vector Machine (SVM) to classify images of cats and dogs using Python and OpenCV in a Google Colab environment. It uses simple grayscale image features and a linear kernel to demonstrate classical image classification.

---


## 🚀 How to Run in Google Colab
✅ Step 1: Upload test_set Folder
Upload the entire test_set folder using the left sidebar in Colab (Files > Upload Folder).
✅ Step 2: Set Folder Path

---


## 🧠 Model Overview
Algorithm: Support Vector Machine (SVM)
Features: Grayscale images resized to 64×64 pixels, flattened into 1D vectors
Classes: Cat (0), Dog (1)

---


## 🛠️ Dependencies
opencv-python
numpy
matplotlib
scikit-learn

---


## 📜 Steps Performed
Image Loading: Load all .jpg images from cats/ and dogs/ folders.
Preprocessing:
Resize to 64×64
Convert to grayscale
Flatten to 1D vector
Train-Test Split: 80% training, 20% testing
Model Training: SVC(kernel='linear')
Evaluation:
Accuracy
Classification Report
Random image visualization with prediction

---

## Author
Shaik Shabnam 
Internship at SkillCraft Technology
