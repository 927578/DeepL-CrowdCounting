# 🧍‍♂️🧍 Crowd Counting with Deep Learning
A deep learning project for estimating the number of customers appearing in business environments using surveillance images. This can help brick-and-mortar stores analyze foot traffic, optimize rent, and improve customer experience.

## 📌 Project Overview

> “We see our customers as invited guests to a party...” – Jeff Bezos

Knowing how many “guests” (customers) are attending your “party” (store) is vital. Instead of installing expensive sensors, this project uses **video surveillance images** and **neural networks** to estimate customer counts — a cost-effective and scalable solution.

## 🎯 Objective

- Build a neural network model that predicts the **number of people** in each surveillance image.
- Apply this for **retail analytics**, **customer behavior**, and **space optimization**.

## 🗃️ Dataset

- 📁 `labels.csv`: Contains image IDs and actual customer count per image
- 🖼️ Image Format: `.jpg` files named as `seq_XXXXXX.jpg`
- Dataset split:
  - 70% Training
  - 15% Validation
  - 15% Testing

> Dataset initially located in Google Drive ZIP file and extracted using Colab

## 🧠 Methods

- Used **pandas** and **scikit-learn** for preprocessing
- Created directory-based image references
- Built deep learning models (details in notebook, e.g., CNNs) to learn regression of headcounts

## 📦 Libraries Used

- Python, Pandas, Numpy
- Scikit-learn
- TensorFlow / Keras (for CNN)
- Google Colab (for cloud training)

## 🖼️ Visualization

- Training loss/MAE curves
- Sample prediction vs. ground truth counts
- Heatmap (optional enhancement)

## 🚀 Applications

- Retail footfall analysis
- Smart surveillance
- Public event crowd estimation
- Space utilization optimization

## 📁 Project Structure


## 👥 Authors

- **Daniel Du** (MSBA)
- Deep Learning Individual Project (2024)

---

## 🗣 中文简要说明

本项目旨在使用神经网络模型对视频监控图像中的顾客数量进行估计，用于零售业客流量分析和运营优化。相比传统的门禁传感器，该方法更加低成本且可拓展，适合大多数线下门店部署使用。
