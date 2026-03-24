# 📰 Fake News Detection System (Python)

## 📌 Overview

This project is a **Fake News Detection System** built using **Machine Learning in Python**.
It classifies news articles as **REAL** or **FAKE** based on their text content.

---

## 🚀 Features

* Detects fake vs real news
* Uses **TF-IDF Vectorization**
* Trained with **Logistic Regression**
* Simple and easy to understand
* Can test custom news input

---

## 🛠️ Technologies Used

* Python
* Pandas
* Scikit-learn

---

## 📂 Project Structure

```
Fake-News-Detection/
│
├── detection.py        # Main Python script
├── News.csv            # Dataset file
└── README.md           # Project documentation
```

---

## 📊 Dataset

The dataset contains:

* `text` → News content
* `label` → REAL / FAKE

Example:

```
"Government announces new policy", REAL
"Aliens landed on Earth", FAKE
```

---

## ⚙️ Installation

1. Clone the repository:

```
git clone https://github.com/your-username/fake-news-detection.git
cd fake-news-detection
```

2. Install required libraries:

```
pip install pandas scikit-learn
```

---

## ▶️ How to Run

Run the Python script:

```
python detection.py
```

---

## 🧠 How It Works

1. Load dataset
2. Split into training and testing data
3. Convert text into numerical features using TF-IDF
4. Train model using Logistic Regression
5. Predict whether news is fake or real

---

## 📈 Output

* Displays model accuracy
* Predicts custom news input

Example:

```
Accuracy: 0.85
Prediction: REAL
```

---

## 🔮 Future Improvements

* Add GUI using Tkinter
* Deploy as a web app (Flask/Django)
* Use advanced models (SVM, Deep Learning)
* Improve dataset size for better accuracy
