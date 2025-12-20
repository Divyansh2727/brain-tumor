Brain-Tumor-Classification/
│
├── dataset/
│   ├── Glioma/
│   ├── Meningioma/
│   ├── Pituitary/
│   └── No_Tumor/
│
├── notebooks/
│   └── besttestdeepnew.ipynb
│
├── models/
│   ├── cnn_model.h5
│   ├── unet_model.h5
│   └── attention_unet_model.h5
│
├── src/
│   ├── data_preprocessing.py
│   ├── cnn_model.py
│   ├── unet_model.py
│   ├── train.py
│   ├── evaluate.py
│   └── inference.py
│
├── results/
│   ├── confusion_matrix.png
│   ├── accuracy_loss.png
│   └── segmentation_outputs/
│
├── README.md
├── requirements.txt
└── LICENSE



## 🚀 Key Achievements
- ✅ Achieved **98.7% accuracy** using Attention U-Net.
- ✅ Segmentation masks with high **Dice Coefficient** for tumor detection.
- ✅ CNN achieved **96.75% classification accuracy** across 4 classes.
- ✅ Comparative analysis of **CNN, U-Net, Attention U-Net, ResNet50**.
- ✅ Interactive **inference script** to test new MRI scans.
