# 🧠 Computer Vision Projects with PyTorch

This repository contains multiple **image classification projects** built using **PyTorch**, covering various datasets from standard benchmarks to custom domains.

> Whether you're a student, researcher, or enthusiast looking to study or build on CNN-based image classification, this repo offers practical, modular code examples for training and evaluating deep learning models.

---

## 📁 Project Structure

```
.
├── cifar10/                   # CNN models trained and tested on the CIFAR-10 dataset
├── cifar100/                  # Models adapted for the more complex CIFAR-100 dataset
├── food_mini/                 # A food image classification project using a smaller subset of food categories
├── vegtable_classification/   # Custom vegetable classification with preprocessing and model evaluation
└── README.md
```

---

## 🔍 Folder Descriptions

### 🟦 `cifar10/`

* Baseline CNN implementation for CIFAR-10
* Data augmentation using torchvision transforms
* Training loop, validation, and accuracy tracking
* Model saving and evaluation scripts

### 🟨 `cifar100/`

* Similar structure to `cifar10`, with a deeper model to handle the increased class complexity
* Experiments with deeper CNNs and regularization techniques

### 🍔 `food_mini/`

* Trained on a smaller food image dataset (e.g. Food-101 Mini)
* Custom dataset loader
* Transfer learning support (e.g., ResNet, EfficientNet via torchvision models)

### 🥦 `vegtable_classification/`

* Real-world vegetable image classification
* Image preprocessing, normalization, and augmentation
* Multi-class classification using CNNs or pretrained backbones

---

## ⚙️ Technologies Used

* 🧠 PyTorch
* 📦 torchvision
* 📊 matplotlib / seaborn (for training visualization)
* 🧪 sklearn (for metrics and confusion matrix)

---

## 🚀 Getting Started

1. Clone the repository:

```bash
git clone https://github.com/pouyasolltani81/your-repo-name.git
cd your-repo-name
```

2. Install dependencies:

```bash
pip install torch torchvision matplotlib scikit-learn
```

3. Study any project notebook:

you can run the notebooks cell by cell to undrestand how each model was trained and used . ;)

---

## 📈 Goals

* 🧪 Explore multiple datasets with consistent code structure
* ⚡ Compare different CNN architectures and learning strategies
* 🧰 Make reusable, modular code for image classification tasks

---

## 🧠 Learn More

If you’re learning PyTorch or deep learning, these projects are great starting points to understand:

* Dataset preparation
* CNN model building
* Training loops & optimizers
* Evaluation metrics and visualization

---

## 📜 License

MIT License — use, modify, and share freely.

---

## ✉️ Contact

Made with ❤️ by [Pouya Soltani](https://github.com/pouyasolltani81)
Have questions or feedback? Open an issue or reach out via GitHub!
