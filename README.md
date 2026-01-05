# Real vs AI Image Detection

This project focuses on training a deep learning model to **classify images as real or AI-generated**.  

---

## Model

- Base model: **Pretrained AlexNet**  
- Last layer modified for **2-class classification** (Real vs AI)  
- Fine-tuning applied on selected layers  

---

## Training

- **Optimizer:** Adam  
- **Loss Function:** CrossEntropyLoss  
- **Hardware:** GPU supported (Google colab)
- **Live loss visualization** during training  

---

## Results

- Accuracy and loss graphs will be added after testing  
- Model distinguishes **real vs AI-generated images** effectively  

---

## Requirements

- Python 3.8+  
- PyTorch & torchvision  
- matplotlib, numpy  

---
