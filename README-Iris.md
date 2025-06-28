# 🌸 Iris Flower Classifier

An interactive machine learning app built with **Gradio** and a **Decision Tree Classifier** to predict the species of an Iris flower based on its sepal and petal dimensions. The UI is enhanced with confidence visualizations and custom flower icons.

![App Screenshot](./41b208de-a457-4361-b839-6e103089ccf0.png)

## 🔗 Live Demo

👉 [Try the App](https://faee4300f1c5f840d4.gradio.live/) — Powered by Gradio

---

## 📊 Features

- 🌿 Input sliders for Sepal & Petal dimensions
- 🌼 Real-time prediction using Decision Tree model
- 📈 Confidence chart (bar graph)
- 🌺 Displays flower icon/image for predicted species
- 🎨 Clean and responsive Gradio UI

---

## 📁 Dataset

Uses the built-in [Iris dataset](https://scikit-learn.org/stable/auto_examples/datasets/plot_iris_dataset.html) from `scikit-learn`:
- 3 species: Setosa, Versicolor, Virginica
- 150 samples
- 4 features (sepal length/width, petal length/width)

---

## 🚀 Tech Stack

- Python 🐍
- Scikit-learn 🔍
- Gradio 🎛️
- Matplotlib 📊

---

## 📸 Screenshots

| Prediction UI | Confidence Chart & Icon |
|---------------|--------------------------|
| ![App](./41b208de-a457-4361-b839-6e103089ccf0.png) | Side-by-side display of confidence chart and predicted flower |

---

## 🧠 How It Works

1. User selects measurements via sliders.
2. Model predicts the species using a trained Decision Tree.
3. A bar chart shows model confidence.
4. A corresponding flower icon is displayed.

---

## 🛠️ Installation

```bash
git clone https://github.com/your-username/iris-flower-classifier.git
cd iris-flower-classifier
pip install -r requirements.txt
python app.py
