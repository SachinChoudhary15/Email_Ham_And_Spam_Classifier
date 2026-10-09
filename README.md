
# 📧 Email Ham and Spam Classifier

A Machine Learning-based application that classifies email messages as **Spam** or **Ham (Not Spam)** using text preprocessing, TF-IDF feature extraction, and a trained classification model.

[![Open Live Streamlit App](https://static.streamlit.io/badges/streamlit_badge_black_white.svg)](https://emailhamandspamclassifier-t2aw5qmzymea3avcqvtpeu.streamlit.app/)

## 🚀 Live Demo

**Try the application:** [Email Ham and Spam Classifier](https://emailhamandspamclassifier-t2aw5qmzymea3avcqvtpeu.streamlit.app/)

## 📌 Project Overview

Email spam is a common problem that affects communication, productivity, and online security. This project applies Natural Language Processing (NLP) techniques and Machine Learning to classify email messages automatically.

Users can enter an email message and receive a prediction indicating whether it is Spam or Ham (Not Spam).

## ✨ Features

* 📩 Email Spam Detection
* 🧹 Text Preprocessing
* 🔤 TF-IDF Feature Extraction
* 🤖 Machine Learning-based Classification
* ⚡ Fast Predictions using Saved Model Artifacts
* ♻️ Reusable Trained Model and Vectorizer
* 🌐 Interactive Web Application
* ☁️ Live Deployment on Streamlit Community Cloud

## 🛠️ Technologies Used

* **Programming Language:** Python
* **Machine Learning:** Scikit-learn
* **Data Processing:** Pandas, NumPy
* **Feature Extraction:** TF-IDF Vectorizer
* **Model Serialization:** Joblib
* **Web Application:** Streamlit

## 📂 Project Structure

```text
Email_Ham_And_Spam_Classifier/
│
├── app.py                  # Streamlit application
├── model.py                # Model training / prediction logic
├── best_model.pkl          # Saved trained ML model
├── vectorizer.pkl          # Saved TF-IDF vectorizer
├── spam_ham_dataset.csv    # Email dataset
├── requirements.txt        # Python dependencies
├── README.md               # Project documentation
└── .gitignore              # Git ignore rules
```

## ⚙️ Machine Learning Workflow

1. **Data Collection:** Load the labeled email dataset.
2. **Text Preprocessing:** Prepare email text for feature extraction.
3. **Feature Extraction:** Convert text into numerical features using TF-IDF.
4. **Model Training:** Train a supervised classification algorithm.
5. **Model Evaluation:** Evaluate performance using appropriate classification metrics.
6. **Model Serialization:** Save the trained model and vectorizer.
7. **Prediction:** Classify new email messages using the saved artifacts.
8. **Deployment:** Serve the application through Streamlit Community Cloud.

## 📊 Dataset

The project uses an email dataset containing labeled messages:

* **Ham:** Legitimate, non-spam messages.
* **Spam:** Unwanted or spam messages.

Dataset file: `spam_ham_dataset.csv`

## 💻 Installation and Setup

### 1. Clone the Repository

```bash
git clone https://github.com/SachinChoudhary15/Email_Ham_And_Spam_Classifier.git
```

### 2. Navigate to the Project Directory

```bash
cd Email_Ham_And_Spam_Classifier
```

### 3. Create a Virtual Environment

```bash
python -m venv EmailClassifier
```

### 4. Activate the Environment

**Windows PowerShell:**

```powershell
.\EmailClassifier\Scripts\Activate.ps1
```

### 5. Install Dependencies

```bash
pip install -r requirements.txt
```

## ▶️ Run the Application Locally

Start the Streamlit application:

```bash
streamlit run app.py
```

Streamlit will provide a local URL in the terminal where you can access the application.

## 📈 Model Evaluation

Useful classification metrics include:

* Accuracy
* Precision
* Recall
* F1-score
* Confusion Matrix

Actual evaluation results should be added after measuring the trained model on a held-out test dataset.

## ☁️ Deployment

The application is hosted on **Streamlit Community Cloud**.

🔗 **Live URL:** [Email Ham and Spam Classifier](https://emailhamandspamclassifier-t2aw5qmzymea3avcqvtpeu.streamlit.app/)

## 🔮 Future Improvements

* Compare multiple Machine Learning classification algorithms.
* Improve text preprocessing and feature engineering.
* Display model evaluation metrics in the application.
* Add prediction confidence when supported by the model.
* Improve the interface and input validation.
* Evaluate performance on additional email datasets.

## 👨‍💻 Author

**Sachin Choudhary

* GitHub: [SachinChoudhary15](https://github.com/SachinChoudhary15)

## ⚠️ Disclaimer

This project is intended for educational and demonstration purposes. Machine Learning predictions may be incorrect; therefore, the classifier should not be treated as the sole basis for email security decisions.

---

⭐ If you find this project useful, consider starring the repository!
