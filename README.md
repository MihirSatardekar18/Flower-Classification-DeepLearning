# 🌸 Flower Classification with Deep Learning

![Python](https://img.shields.io/badge/Python-3.10-blue?logo=python&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-2.x-orange?logo=tensorflow&logoColor=white)
![Keras](https://img.shields.io/badge/Keras-2.x-red?logo=keras&logoColor=white)
![License](https://img.shields.io/badge/License-MIT-green)

---

## 🚀 Project Overview

This project demonstrates **Image Classification of Flowers** using **Convolutional Neural Networks (CNN)** built with **TensorFlow & Keras**.  
It automatically downloads a flower dataset, preprocesses images, trains a CNN, and allows **real-time image prediction**.

**Dataset Source:** [TensorFlow Flower Photos](https://storage.googleapis.com/download.tensorflow.org/example_images/flower_photos.tgz)

---

## 🌺 Dataset Details

- **Number of Classes:** 5  
- **Classes:** `daisy`, `dandelion`, `roses`, `sunflowers`, `tulips`  
- **Total Images:** ~3,670  
- **Train/Test Split:** 80% train / 20% validation

---

## 🛠 Features

- ✅ Automatic dataset download & preprocessing  
- ✅ Train/Validation split with `image_dataset_from_directory`  
- ✅ CNN architecture with **Conv2D**, **MaxPooling2D**, **Flatten**, **Dense**, and **Dropout**  
- ✅ Training & validation accuracy/loss visualization  
- ✅ Real-time image upload & prediction  
- ✅ GPU acceleration support on **Google Colab**  

---

## 📈 Model Architecture


- Optimizer: **Adam**  
- Loss Function: **Sparse Categorical Crossentropy**  
- Metrics: **Accuracy**  

---

## 🖥 How to Run

1. Open `Flower_Classification.ipynb` in **Google Colab**  
2. **Runtime → Change runtime type → GPU**  
3. Run all cells sequentially  
4. Upload any flower image in the last cell to see **real-time predictions**

---

## 📊 Visualization

- Accuracy & Loss plots are generated after training  
- Sample predictions with **bar chart of probabilities** are displayed  

---

## 💻 Requirements

```bash
tensorflow>=2.10
numpy
matplotlib
Pillow
👨‍💻 Author

Mihir Satardekar 😎
Internship Project – Data Analysis & Deep Learning
📧 Contact: mihir@example.com

📜 License

This project is licensed under the MIT License – see the LICENSE
 file for details.
