# 🧠 Deep Learning-Based Brain Tumor Classification
### Using CNN and U-Net Variants

## 📌 Overview
This project implements and compares deep learning architectures for brain tumor
classification and segmentation using medical images. The models include CNN,
U-Net, Attention U-Net, and ResNet50.

The objective is to analyze performance trade-offs and identify the most effective
model for AI-assisted medical diagnosis.

---

## 🧩 Project Phases

### Phase 1: Dataset Preparation
Medical images are organized by tumor class and split into training and validation
sets.

**Output:**
- Structured dataset
- Class distribution analysis

---

### Phase 2: Preprocessing & Augmentation
Images are resized, normalized, and augmented to improve generalization.

**Techniques:**
- Normalization
- Rotation, flipping, zooming
- Data balancing

**Output:**
- Augmented training images

---

### Phase 3: Model Architectures
Implemented models:
- CNN (baseline)
- U-Net (segmentation)
- Attention U-Net
- ResNet50 (transfer learning)

**Output:**
- Defined deep learning pipelines

---

### Phase 4: Model Training
Models are trained using Adam optimizer with EarlyStopping and ReduceLROnPlateau.

**Output:**
- Trained model weights
- Accuracy & loss curves

---

### Phase 5: Evaluation
Models are evaluated using:
- Accuracy, Precision, Recall, F1-score
- Confusion Matrix
- Dice Coefficient & IoU

---

### Phase 6: Visualization
- Accuracy–Loss graphs
- Confusion matrices
- Segmentation mask overlays

---

## 📊 Results Summary

| Model           | Accuracy (%) |
|-----------------|--------------|
| CNN             | 96.75        |
| U-Net           | 96.80        |
| Attention U-Net | 98.70        |
| ResNet50        | 73.41        |

---

## 🛠️ Technologies Used
- Python
- TensorFlow, Keras
- CNN, U-Net, Attention U-Net, ResNet50
- OpenCV, NumPy, Matplotlib

---

## 🚀 Applications
- Medical image analysis
- Brain tumor detection
- AI-assisted diagnostic systems
