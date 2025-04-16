# 🧠 Fake News Detection Using Machine Learning

## 📌 Project Description

This project implements a machine learning pipeline to classify news articles as **real** or **fake**, aiming to combat the widespread dissemination of misinformation in digital media. The solution evaluates multiple supervised learning algorithms and compares their performance using relevant classification metrics.

---

## 📚 Problem Statement

The exponential growth of online content has made it easier for fake news to influence public opinion. Automating the detection of such content can assist in maintaining information credibility across platforms.

---

## ⚙️ ML Algorithms Implemented

We trained and evaluated the following classification models:

- **Logistic Regression**
- **Decision Tree Classifier**
- **Random Forest Classifier**
- **Gradient Boosting Classifier**

Each model was fine-tuned and assessed using cross-validation.

---

## 📂 Dataset Overview

The dataset contains labeled news articles categorized as:

- `1`: **Real News**
- `0`: **Fake News**

Each entry includes:
- Article Title
- Main Text
- Label (Target)

---

## 🧪 Evaluation Metrics

Model performance was measured using:

- **Accuracy**
- **Precision**
- **Recall**
- **F1 Score**
- **Confusion Matrix**

---

## 🖥️ System Requirements

**Hardware:**
- 4 GB RAM or higher  
- Intel i3 processor or better  
- 500 MB available disk space  

**Software:**
- Python 3.x  
- Anaconda (optional but recommended)

---

## 📦 Dependencies

Ensure the following packages are installed:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
