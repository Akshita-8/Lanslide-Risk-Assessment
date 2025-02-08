# Landslide Vision: Deep Learning for Landslide Risk Assessment

[![GitHub](https://img.shields.io/badge/GitHub-Repository-blue?style=flat&logo=github)](https://github.com/Akshita-8/landslide-vision)

## Overview
Landslide Vision is a deep learning-based project that leverages **LinkNet** for automated **landslide detection** using satellite imagery. The model achieves **97.2% accuracy** on the **Bijie Landslide Dataset**, offering precise risk assessment in disaster-prone areas.

## 🚀 Features
- **Deep Learning Model**: Implements LinkNet with an encoder-decoder architecture for accurate segmentation.
- **High Accuracy**: Achieves 97.2% accuracy in detecting landslides across diverse terrains.
- **Data Processing**: Preprocesses **2,700+ satellite images** and integrates **shapefiles** for improved risk mapping.
- **Cloud-Based Execution**: Developed and trained using **Google Colab** for scalable model training.

## 🛠 Tech Stack
- **Model**: LinkNet
- **Programming Language**: Python
- **Framework**: PyTorch
- **Dataset**: Bijie Landslide Dataset
- **Development Environment**: Google Colab

## 📂 Dataset
The **Bijie Landslide Dataset** consists of **satellite images** with annotated landslide regions. The dataset was processed to enhance spatial feature retention and improve segmentation precision.

## 📈 Model Architecture
The model follows an **encoder-decoder architecture**, where:
- The **encoder** extracts key features from input images.
- The **decoder** reconstructs the segmented output while retaining spatial information.

## 📊 Performance
- **Accuracy**: 97.2%
- **Precision**: High segmentation accuracy across different terrains
- **Robustness**: Effective in detecting landslides in varied geographical regions

## 🔧 Installation & Usage
### 1️⃣ Clone the Repository
```bash
git clone https://github.com/Akshita-8/landslide-vision.git
cd landslide-vision
```
### 2️⃣ Install Dependencies
```bash
pip install -r requirements.txt
```
### 3️⃣ Run Model Training
```bash
python train.py
```
### 4️⃣ Evaluate Model
```bash
python evaluate.py
```

## 🚀 Future Improvements
- Enhance dataset diversity by including more geographical regions.
- Optimize model performance for real-time deployment.
- Integrate the model into an interactive web application for visualization.

## 🤝 Contributing
Feel free to fork this repository, open issues, or submit pull requests to improve Landslide Vision!

## 📜 License
This project is licensed under the **MIT License**.

## 📬 Contact
For any queries or collaborations, reach out to **[Akshita Maremanda](https://github.com/Akshita-8)** on GitHub.

