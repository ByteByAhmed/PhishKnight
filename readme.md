# 🛡️ PhishKnight – Phishing URL Detection System

PhishKnight is a machine-learning-based cybersecurity project designed to identify potentially phishing and legitimate URLs. The system analyzes different characteristics of a URL and uses machine learning to classify it as **Legitimate** or **Phishing**.

## 🎯 Objective

Phishing attacks commonly use deceptive URLs to trick users into visiting malicious websites or revealing sensitive information.

The objective of PhishGuard is to provide an automated method for analyzing URLs and identifying suspicious characteristics that may indicate a phishing attempt.

## 🚀 Features

* 🔗 URL-based phishing detection
* 🔍 URL feature extraction
* 🤖 Machine learning classification
* 🌐 HTTPS analysis
* 📏 URL length analysis
* 🔢 Domain and special-character analysis
* ⚠️ Suspicious keyword detection
* 📊 Model performance evaluation
* 📈 Confusion matrix and performance metrics
* 🧮 Risk assessment
* 🔎 Interactive URL scanner

## 🧠 How It Works

```text
User enters URL
       ↓
URL Feature Extraction
       ↓
Security Feature Analysis
       ↓
Machine Learning Model
       ↓
Prediction
       ↓
┌─────────────────────┐
│                     │
Legitimate        Phishing
   ✅                  🚨
```

## 🔎 Features Extracted

The system analyzes characteristics such as:

* URL length
* Number of dots
* Number of hyphens
* Presence of `@`
* HTTPS usage
* IP address presence
* Suspicious keywords
* Other URL structural characteristics

## 🤖 Machine Learning

The project can use classification algorithms such as:

* Random Forest
* Logistic Regression
* Support Vector Machine (SVM)

The models are evaluated using:

* Accuracy
* Precision
* Recall
* F1-score
* Confusion Matrix

## 🛠️ Technologies Used

* Python
* Google Colab / Jupyter Notebook
* Pandas
* NumPy
* Scikit-learn
* Matplotlib
* Seaborn

## 📂 Project Structure

```text
PhishGuard/
│
├── Phishknight.ipynb
├── dataset.csv
├── README.md
└── requirements.txt
```

## ▶️ How to Run

### 1. Clone the repository

```bash
git clone https://github.com/yourusername/PhishGuard.git
```

### 2. Open the notebook

Open:

```text
PhishGuard.ipynb
```

using Google Colab or Jupyter Notebook.

### 3. Install dependencies

```bash
pip install pandas numpy scikit-learn matplotlib seaborn
```

### 4. Run the notebook

Run the cells sequentially.

## 🧪 Example

```text
Enter URL:
http://example-login-verify.com

Result:
🚨 Potential Phishing URL

Risk indicators:
- Suspicious keyword detected
- Unusual URL structure
- Insecure HTTP connection
```

## ⚠️ Disclaimer

Phishknight is an educational cybersecurity project. A URL classified as legitimate is not guaranteed to be completely safe, and a suspicious classification does not necessarily prove that a website is malicious.

The system should be used as an additional security layer rather than a replacement for professional security tools.

## 👨‍💻 Project

**Phishknight – Machine Learning-Based Phishing URL Detection and Risk Analysis System**

Developed as a cybersecurity and machine learning project for educational purposes.
