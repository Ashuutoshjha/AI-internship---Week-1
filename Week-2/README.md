# 📂 Week 2 – Dataset Preparation & CNN Model Building

## ✅ Objective
In Week 2 of the AI Internship, the main goal was to **prepare the dataset** and **build a basic CNN model** for classifying waste into **Organic** and **Recyclable** categories.

---

## 📁 Tasks Completed
✔ Downloaded the **Waste Classification Dataset** from Kaggle  
✔ Organized dataset into folders: `TRAIN` and `TEST`  
✔ Applied **image preprocessing** (resizing & normalization)  
✔ Loaded images using `ImageDataGenerator` in TensorFlow  
✔ Built a **simple CNN architecture** using Keras  
✔ Trained the model for initial epochs  
✔ Observed training and validation accuracy  

---

## 🧠 CNN Model Summary
- Input Image Size: **224 × 224 × 3**  
- Layers Used:
  - Conv2D + MaxPooling  
  - Conv2D + MaxPooling (deeper)  
  - Flatten → Dense → Dropout  
  - Final Dense Layer with **Sigmoid Activation** (Binary Classification)  
- Optimizer: **Adam**  
- Loss Function: **Binary Crossentropy**

---


