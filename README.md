# 🎓 AI Student Intelligence & Academic Risk Analytics Platform

An advanced Machine Learning and AI-based student analytics system built using Streamlit, Scikit-Learn, and Python.

The platform predicts student performance, analyzes academic risks, performs clustering, and provides AI-driven recommendations using multiple ML algorithms.

---

# 🚀 Features

## 📊 Dashboard Analytics

* Student performance overview
* Academic statistics
* Interactive charts
* Risk indicators
* Real-time analytics dashboard
* Subject-wise performance monitoring

---

## 📈 Machine Learning Models

* Simple Linear Regression
* Multiple Linear Regression
* Logistic Regression
* Naive Bayes
* K-Means Clustering
* PCA Visualization

### ML Capabilities

* Score prediction
* Academic risk classification
* Student segmentation
* Performance analysis
* Trend detection

---

## 🤖 AI Features

* Student risk prediction
* Feedback sentiment analysis
* Performance categorization
* AI recommendation engine
* AI-powered study suggestions
* Resume analysis support

---

## 🎨 Modern UI

* Dark theme dashboard
* Interactive visualizations
* Professional Streamlit interface
* Responsive layout
* Sidebar navigation
* Dynamic charts and analytics

---

# 🛠 Technologies Used

* Python 3.12
* Streamlit
* Pandas
* NumPy
* Scikit-Learn
* Plotly
* Matplotlib
* Seaborn
* NLTK
* Google Generative AI

---

# 📂 Project Structure

```bash
ML/
│
├── .gitignore
│
├── runtime.txt
│
├── README.md
│
├── app/
│   │
│   ├── .env
│   │
│   ├── app.py
│   │
│   └── requirements.txt
│
├── data/
│   │
│   ├── StudentsPerformance.csv
│   │
│   └── Student Mental health.csv
│
└── notebooks/
    │
    └── AI_Student_Analytics.ipynb

```

---

# 🔐 Google Gemini API Setup

This project uses Google Generative AI for AI-powered recommendations and insights.

## 1️⃣ Open Google AI Studio

Visit:

https://aistudio.google.com/app/apikey

---

## 2️⃣ Login With Google Account

Sign in using your Google account.

---

## 3️⃣ Create API Key

* Click on **Create API Key**
* Select existing Google Cloud project or create a new one
* Generate the API key

---

## 4️⃣ Copy API Key

Example:

```env
AIzaSyXXXXXXXXXXXXXXX
```

---

## 5️⃣ Create `.env` File

Inside the `app/` folder create:

```bash
.env
```

---

## 6️⃣ Add API Key Inside `.env`

```env
GOOGLE_API_KEY=your_api_key_here
```

Example:

```env
GOOGLE_API_KEY=AIzaSyXXXXXXXXXXXXXXX
```

---

# ⚠️ Important Security Note

Never upload your `.env` file to GitHub.

Add this inside `.gitignore`:

```gitignore
.env
venv/
__pycache__/
*.pyc
```

---

# ⚙️ Complete Setup Guide

## 1️⃣ Go To Project Folder

```bash
cd ~/Desktop/ML
```

---

## 2️⃣ Check Python Version

```bash
python3 --version
```

---

## 3️⃣ Install Python 3.12

```bash
brew install python@3.12
```

---

## 4️⃣ Verify Python 3.12

```bash
python3.12 --version
```

### Expected Output

```bash
Python 3.12.x
```

---

## 5️⃣ Create Virtual Environment

```bash
python3.12 -m venv venv
```

---

## 6️⃣ Activate Virtual Environment

```bash
source venv/bin/activate
```

---

## 7️⃣ Verify Python Inside Venv

```bash
python --version
```

### Expected Output

```bash
Python 3.12.x
```

---

## 8️⃣ Install Requirements

```bash
python -m pip install -r app/requirements.txt
```

---

## 9️⃣ Upgrade pip

```bash
pip install --upgrade pip
```

---

# ▶️ Run Streamlit Application

```bash
python -m streamlit run app/app.py
```

---

# 🌐 Streamlit URLs

After running the app:

```bash
Local URL: http://localhost:8501
Network URL: http://172.xx.xx.xx:8501
```

---

# 📊 Data Visualization Features

* Histograms
* Scatter Plots
* Heatmaps
* Bar Charts
* Pie Charts
* PCA Cluster Visualization

---

# 🎯 Project Objectives

* Predict student academic performance
* Detect academic risks early
* Analyze student feedback
* Provide AI-powered recommendations
* Improve educational decision-making
* Enhance learning outcomes using AI

---

# 👨‍💻 Developed By

## Ankit Chowdhary

B.Tech CSE (Data Science & Machine Learning)

---
