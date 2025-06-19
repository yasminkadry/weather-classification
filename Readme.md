# 🌦️ Weather Classification – Deep Learning Project

This repository contains a deep learning project focused on classifying weather conditions from images using powerful pretrained and from-scratch convolutional neural networks (CNNs).

## 📁 Project Overview

This project includes:

- Data preprocessing using Keras' `ImageDataGenerator`
- Implementation of multiple CNN architectures, both from scratch and pretrained:
  - From Scratch Models
  - InceptionResNetV2
  - ResNet152
  - EfficientNetV2B2
- Model training with Adam optimizer and early stopping
- Evaluation of model performance on training, validation, and test sets

## 🧪 Model Performance Comparison

| Model Name                        | Train Accuracy (%) | Validation Accuracy (%) | Test Accuracy (%) |
|----------------------------------|--------------------|--------------------------|-------------------|
| ScratchModel1                    | 79.30              | 72.10                    | 72.00             |
| ScratchModel2                    | 79.20              | 68.45                    | 71.17             |
| Scratch_Model_With_SkipConnection| 76.24              | 70.21                    | 74.17             |
| InceptionResNetV2                | 89.55              | 84.76                    | 85.10             |
| ResnetModel152                   | 97.93              | 88.28                    | 90.81             |
| EfficientNetV2B2                 | 90.90              | 82.50                    | 85.29             |

> 📌 **Insight:** Transfer learning models significantly outperform from-scratch models in accuracy across all datasets.

## 🛠️ Technologies Used

- Python
- TensorFlow & Keras
- NumPy, Pandas
- Matplotlib, Seaborn

## 📦 Installation

Install the required libraries:

```bash
pip install tensorflow keras pandas numpy matplotlib seaborn
````

## 🚀 How to Run the Project

1. **Clone the repository:**

   ```bash
   git clone https://github.com/yasmin-AI/weather-classification.git
   cd weather-classification
   ```

2. **Launch the Jupyter Notebook:**

   ```bash
   jupyter notebook
   ```

3. **Open the `.ipynb` notebook file and run all cells** to:

   * Preprocess image data
   * Train the CNN models
   * Evaluate and visualize model performance

> 🖼️ Make sure your dataset is placed in the expected directory structure before running the notebook.

## 👩‍💻 Connect with Me

* **Name:** Yasmin
* **Role:** AI Engineer Trainee at ITI (AI-Pro, Intake 45)
* **📧 Email:** [ yasminkadry6720@gmail.com](mailto:yasminkadry6720@gmail.com)
* **🔗 LinkedIn:** [linkedin.com/in/yasminkadry](https://www.linkedin.com/in/yasmin-kadry)
* **💻 GitHub:** [https://github.com/yasminkadry](https://github.com/yasminkadry)

---

> *This project applies deep learning techniques to real-world weather classification using both custom and pretrained models. Built with love and curiosity to explore AI's impact in image recognition.* 💡

