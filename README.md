# Garbage Classification using PyTorch

This project classifies garbage images into categories using a Convolutional Neural Network (CNN) and PyTorch. It is designed to help sort waste into appropriate recycling categories.

## 📁 Dataset
Dataset used: [Garbage Classification](https://www.kaggle.com/asdasdasasdas/garbage-classification)

You can download it manually or use the Kaggle API. Ensure the folder structure is compatible with `ImageFolder` from `torchvision.datasets`.

## 🚀 Features
- Transfer learning with pretrained CNN (e.g., ResNet18)
- Custom training and evaluation pipeline
- Image transformations and visualization
- Performance metrics and plots

## 🧠 Model
- Architecture: ResNet18 (pretrained)
- Loss Function: CrossEntropyLoss
- Optimizer: Adam

## 📊 Results
- Accuracy: ~92% (example)
- Includes loss/accuracy curves and confusion matrix

## 🛠️ Installation

```bash
git clone https://github.com/yourusername/garbage-classification-pytorch.git
cd garbage-classification-pytorch
pip install -r requirements.txt
```

## ▶️ Usage

```bash
python src/train.py       # Train the model
python src/evaluate.py    # Evaluate the model and plot metrics
```

## 📎 License
MIT License

---

For best results, place the dataset inside a `data/` folder or update paths accordingly in the scripts.

