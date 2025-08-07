
# 🧠 Diagnosing Alzheimer’s Disease

A deep learning-based system to classify the four stages of Alzheimer’s Disease using MRI images, designed to aid in early detection and clinical decision-making.

---

## 📑 Table of Contents

* [Introduction](#-introduction)
* [Usage](#-usage)
* [Features](#-features)
* [License](#-license)

---

## 🧠 Introduction

Alzheimer’s Disease (AD) is a progressive neurodegenerative disorder marked by brain atrophy and neuronal death due to abnormal protein accumulation. Timely and accurate diagnosis is critical to slowing disease progression and improving patient outcomes.

This project leverages Convolutional Neural Networks (CNNs) to detect and classify MRI scans into one of four stages of Alzheimer’s:

* **NonDemented**
* **VeryMildDemented**
* **MildDemented**
* **ModerateDemented**

The proposed custom baseline CNN model has been trained on **10,114 grayscale MRI images**, achieving a remarkable **97.80% accuracy**, outperforming traditional machine learning methods and some advanced pre-trained models like **Xception**.

---


## 🧪 Usage

### Run Using Docker

#### CPU-Only Version

```bash
sudo docker run -it --rm -v ${PWD}:/workspace ghcr.io/pip700/ad_stage_diagnosis:latest
```

#### GPU-Enabled Version

```bash
sudo docker run --gpus all -it --rm -v ${PWD}:/workspace ghcr.io/pip700/ad_stage_diagnosis:latest
```

---

## ✨ Features

* Custom CNN model trained on **10,114 MRI images**
* Detects **four clinical stages** of Alzheimer’s Disease
* Achieves **97.80% classification accuracy**
* Includes a **ready-to-use pretrained model**
* Straightforward image-to-prediction workflow


---

## 📄 License

This project is licensed under the **MIT License**.
See the [LICENSE](./LICENSE) file for more details.
