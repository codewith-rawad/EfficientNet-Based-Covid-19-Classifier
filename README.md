# COVID-19 Chest X-Ray Classification Project

Welcome to the **COVID-19 Chest X-Ray Classification Project** — a cutting-edge deep learning model designed to classify chest X-ray images into multiple categories of lung conditions. This project leverages state-of-the-art architectures (such as EfficientNet) to accurately detect and differentiate between normal lungs and various types of pneumonia, including COVID-19.

---

## 🗂️ Dataset Overview

Our dataset comprises chest X-ray images categorized into the following four key classes:

| Disease Category     | Description                                                                                     |
|---------------------|-------------------------------------------------------------------------------------------------|
| **Normal**          | Chest X-rays with no visible signs of lung infection or abnormality.                            |
| **Lung Opacity**    | X-rays showing lung opacity, indicating fluid or inflammation which is often associated with pneumonia or other lung conditions. |
| **Viral Pneumonia** | Images depicting pneumonia caused by viral infections other than COVID-19.                     |
| **COVID**           | Chest X-rays showing typical signs of COVID-19 viral pneumonia.                                |

These categories enable the model to learn discriminative features that help in accurate classification and early diagnosis.

---

## 🚀 Project Highlights

- Utilizes **EfficientNet** architecture optimized for image classification tasks.
- Trains on a well-curated dataset covering common lung infections plus normal cases.
- Supports saving both the **full trained model** and **weights separately** for easy deployment or fine-tuning.
- Generates insightful **accuracy and loss plots** to monitor model performance.
- Designed to be easily extendable with additional lung disease categories in the future.

---

## 📂 Data Organization Example

The dataset images are organized into folders named exactly as the disease categories for seamless training:

```plaintext
dataset/
│
├── Normal/
├── Lung_Opacity/
├── Viral_Pneumonia/
└── COVID/
