# 📧 Spam vs Ham Mail Prediction System

A **Machine Learning project** that classifies emails/messages as **Spam** or **Ham (Not Spam)** using a **Logistic Regression model**.

This project uses **TF-IDF feature extraction** to convert text messages into numerical vectors and then trains a classification model to detect spam messages.

---

## 🚀 Project Overview

Spam emails are unwanted messages that can contain advertisements, scams, or malicious links. Detecting spam automatically is an important application of **Machine Learning and NLP**.

This project builds a predictive model that:
- Processes email/message text
- Converts text into numerical features using **TF-IDF Vectorization**
- Trains a **Logistic Regression classifier**
- Predicts whether a new message is **Spam or Ham**

---

## 📂 Dataset

The project uses a dataset named:

```
mail_data.csv
```

The dataset contains two columns:

| Column | Description |
|------|-------------|
| Category | Label of the message (`spam` or `ham`) |
| Message | The actual email/message text |

Example:

| Category | Message |
|---------|--------|
| ham | I'm going to attend the meeting tomorrow |
| spam | Free entry in a weekly competition to win cash prizes |

---

## 🛠 Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- TF-IDF Vectorizer
- Logistic Regression
- Jupyter Notebook

---

## ⚙️ Machine Learning Workflow

The project follows these steps:

1. **Import Libraries**
2. **Load Dataset**
3. **Data Cleaning**
   - Handle missing values
4. **Label Encoding**
   - `spam → 0`
   - `ham → 1`
5. **Train-Test Split**
6. **Text Feature Extraction**
   - TF-IDF Vectorization
7. **Model Training**
   - Logistic Regression
8. **Model Evaluation**
   - Accuracy Score
9. **Prediction System**
   - Classify new messages

---

## 📊 Model Used

**Logistic Regression**

Why Logistic Regression?
- Works well for binary classification
- Fast and efficient
- Good baseline model for NLP tasks

---

## 📈 Model Performance

The model is evaluated using **Accuracy Score**.

Metrics calculated:
- Training Accuracy
- Testing Accuracy

---

## 💻 Installation

Clone the repository:

```bash
git clone https://github.com/Collab-Ayush/spam-mail-prediction.git
```

Navigate to the project folder:

```bash
cd spam-mail-prediction
```

Install required libraries:

```bash
pip install pandas numpy scikit-learn
```

---

## ▶️ How to Run the Project

Run the Jupyter Notebook:

```bash
jupyter notebook Spam_Mail_Prediction.ipynb
```

Or run in Google Colab / Jupyter.

---

## 🧪 Example Prediction

Input message:

```
"Free entry in 2 a wkly comp to win FA Cup final tickets"
```

Prediction:

```
Spam
```

Another example:

```
"Even my brother is not like to speak with me."
```

Prediction:

```
Ham
```

---

## 📁 Project Structure

```
spam-mail-prediction
│
├── Spam_Mail_Prediction.ipynb
├── mail_data.csv
└── README.md
```

---

## 🔮 Future Improvements

Possible improvements for this project:

- Use **Naive Bayes or SVM models**
- Deploy as a **Web App (Streamlit / Flask)**
- Add **Deep Learning models**
- Use **larger email datasets**
- Build a **real-time spam detection system**

---

## 👨‍💻 Author

**Ayush Dutta**

Machine Learning & AI Enthusiast

---

## ⭐ If you like this project

Give the repository a **star ⭐ on GitHub**.
