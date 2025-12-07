# 🤖 AI/ML Portfolio

[![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)](https://www.python.org/)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange.svg)](https://jupyter.org/)

> A comprehensive portfolio showcasing machine learning and deep learning projects from the Post Graduate Program in AI/ML, demonstrating expertise in predictive modeling, neural networks, and data analysis.

---

## 📋 Table of Contents

- [Overview](#overview)
- [About Me](#about-me)
- [Projects](#projects)
- [Prerequisites](#prerequisites)
- [Installation & Setup](#installation--setup)
- [Usage](#usage)
- [Testing](#testing)
- [Project Structure](#project-structure)
- [Certifications](#certifications)
- [Future Work](#future-work)
- [Contact](#contact)
- [License](#license)

---

## 🎯 Overview

This repository contains a collection of AI/ML projects developed as part of the Post Graduate Program in AI/ML. Each project demonstrates practical applications of machine learning and deep learning techniques, with a focus on solving real-world business problems. The projects showcase skills in **machine learning**, **deep learning**, **exploratory data analysis (EDA)**, and **data preprocessing**.

With 22 years of Property & Casualty (P&C) insurance experience and certifications in **AWS AI Practitioner**, **Azure Data Scientist Associate**, **Duck Creek Policy Configurator**, and **Power BI Data Analyst**, I'm transitioning to an AI/ML Engineer role to solve claims, fraud, and underwriting challenges in the insurance industry.

---

## 👤 About Me

I'm a Solutions Architect with 22 years of experience in P&C insurance, specializing in SaaS implementations (Duck Creek) and digital transformation. Certified in **AWS**, **Azure**, **Duck Creek**, and **PMP**, I'm currently pursuing an MS in Computer Science to drive insurtech innovation.

**Connect with me:**
- [LinkedIn](https://www.linkedin.com/in/selvakumar-thirumalainambi)
- Portfolio Website: Coming Soon

---

## 🚀 Projects

### 1. [Plant Seedling Classification](plant-seedling-classification/)

**Objective:** Build a Convolutional Neural Network (CNN) to classify plant seedlings and weeds.

**Results:** Achieved **58.74% accuracy** in multi-class classification.

**Key Skills:** TensorFlow, Keras, CNNs, Image Processing, Data Preprocessing

**Business Application:** Adaptable for insurance document classification (e.g., claims photos, damage assessment).

**Technologies:** TensorFlow, Keras, OpenCV, Scikit-learn, Pandas, NumPy, Matplotlib

---

### 2. [Bank Customer Churn Prediction](bank-customer-churn/)

**Objective:** Develop a neural network model to predict customer churn in banking.

**Results:** Model identifies **75% of all actual churners**, enabling proactive retention strategies.

**Key Skills:** TensorFlow, Keras, Neural Networks, EDA, Feature Engineering

**Business Application:** Applicable to P&C policyholder retention and customer lifecycle management.

**Technologies:** TensorFlow, Keras, Scikit-learn, Pandas, NumPy, Matplotlib, Seaborn

---

### 3. [Credit Card Users Churn Prediction](credit-card-churn/)

**Objective:** Create a predictive model for credit card customer churn using ensemble methods.

**Results:** Random Forest model with SMOTE for handling class imbalance.

**Key Skills:** Scikit-learn, SMOTE, Hyperparameter Tuning, Ensemble Methods, Imbalanced Data Handling

**Business Application:** Adaptable for claims fraud detection and risk assessment in insurance.

**Technologies:** Scikit-learn, XGBoost, Imbalanced-learn, Pandas, NumPy, Matplotlib, Seaborn

---

### 4. [Personal Loan Campaign](personal-loan-campaign/)

**Objective:** Build a model to predict loan uptake for marketing campaign optimization.

**Results:** Decision Tree model for loan approval prediction.

**Key Skills:** Scikit-learn, Decision Trees, EDA, Feature Selection

**Business Application:** Applicable to P&C underwriting and risk assessment.

**Technologies:** Scikit-learn, Pandas, NumPy, Matplotlib, Seaborn

---

### 5. [FoodHub](foodhub/)

**Objective:** Conduct exploratory data analysis to derive business insights from food delivery data.

**Results:** Comprehensive EDA with actionable business recommendations.

**Key Skills:** Pandas, Seaborn, Data Visualization, Statistical Analysis, Python Foundations

**Business Application:** Adaptable for P&C customer analytics and behavior analysis.

**Technologies:** Pandas, NumPy, Matplotlib, Seaborn

---

### 6. [Stock Market Sentiment Analysis](stock-market-sentiment/)

**Objective:** Develop an AI-driven sentiment analysis system to process news articles and gauge market sentiment.

**Results:** NLP-based sentiment analysis for stock price prediction enhancement.

**Key Skills:** Natural Language Processing, Sentiment Analysis, Text Processing, Time Series Analysis

**Business Application:** Applicable for analyzing insurance industry news, regulatory changes, and market trends.

**Technologies:** NLTK, TextBlob, Scikit-learn, Pandas, NumPy, Matplotlib, Seaborn

---

## 📦 Prerequisites

Before you begin, ensure you have the following installed:

- **Python 3.8 or higher** ([Download Python](https://www.python.org/downloads/))
- **pip** (Python package installer - usually comes with Python)
- **Git** ([Download Git](https://git-scm.com/downloads))
- **Jupyter Notebook** (will be installed via requirements.txt)

**Recommended:**
- **Anaconda** or **Miniconda** for easier environment management ([Download Anaconda](https://www.anaconda.com/products/distribution))

---

## 🔧 Installation & Setup

### Step 1: Clone the Repository

```bash
git clone https://github.com/tselva-AIML/AI-ML-Portfolio.git
cd AI-ML-Portfolio
```

### Step 2: Create a Virtual Environment (Recommended)

**Using venv:**
```bash
# Create virtual environment
python -m venv venv

# Activate virtual environment
# On Windows:
venv\Scripts\activate
# On macOS/Linux:
source venv/bin/activate
```

**Using conda:**
```bash
# Create conda environment
conda create -n ai-ml-portfolio python=3.10
conda activate ai-ml-portfolio
```

### Step 3: Install Dependencies

**Option A: Install all dependencies (recommended for exploring all projects)**
```bash
pip install -r requirements.txt
```

**Option B: Install project-specific dependencies**
```bash
# Navigate to a specific project folder
cd plant-seedling-classification  # or any other project

# Install project-specific requirements
pip install -r requirements.txt
```

### Step 4: Install Jupyter Notebook (if not already installed)

```bash
pip install jupyter notebook
```

### Step 5: Download Additional Data (if required)

Some projects may require additional data files. Check individual project folders for specific data requirements:

- **Plant Seedling Classification:** Requires `images.npy` file (222 MB) - see project README for download link

---

## 💻 Usage

### Running a Jupyter Notebook

1. **Start Jupyter Notebook:**
   ```bash
   jupyter notebook
   ```
   This will open Jupyter in your default web browser.

2. **Navigate to a project folder:**
   - Click on the project folder (e.g., `plant-seedling-classification`)
   - Open `notebook.ipynb`

3. **Run the notebook:**
   - Execute cells individually using `Shift + Enter`
   - Or run all cells using `Cell > Run All`

### Running a Specific Project

```bash
# Navigate to project directory
cd plant-seedling-classification

# Launch Jupyter Notebook
jupyter notebook notebook.ipynb
```

### Alternative: Using JupyterLab

```bash
# Install JupyterLab (if not already installed)
pip install jupyterlab

# Launch JupyterLab
jupyter lab
```

---

## 🧪 Testing

### Verify Installation

To verify that all dependencies are correctly installed, run:

```bash
python -c "import pandas, numpy, matplotlib, seaborn, sklearn; print('All core libraries imported successfully!')"
```

For projects with TensorFlow:
```bash
python -c "import tensorflow as tf; print(f'TensorFlow version: {tf.__version__}')"
```

### Test Individual Projects

1. **Open the notebook** in Jupyter
2. **Run the first few cells** to verify data loading and imports work correctly
3. **Check for any missing dependencies** - install them using `pip install <package-name>`

### Common Issues & Solutions

**Issue: ModuleNotFoundError**
- **Solution:** Install the missing package: `pip install <package-name>`

**Issue: Kernel not found in Jupyter**
- **Solution:** Install ipykernel: `pip install ipykernel` and register: `python -m ipykernel install --user --name=ai-ml-portfolio`

**Issue: TensorFlow not working**
- **Solution:** Ensure Python 3.8-3.11 is used. For Apple Silicon Macs, use TensorFlow-Metal.

---

## 📁 Project Structure

```
AI-ML-Portfolio/
│
├── README.md                          # This file
├── requirements.txt                   # Root-level dependencies
├── LICENSE                            # MIT License
│
├── plant-seedling-classification/
│   ├── notebook.ipynb
│   ├── requirements.txt
│   ├── README.md
│   ├── data/
│   │   └── Labels.csv
│   └── visuals/
│       └── notebook_visual.html
│
├── bank-customer-churn/
│   ├── notebook.ipynb
│   ├── requirements.txt
│   ├── data/
│   │   └── bank-1.csv
│   └── visuals/
│       └── notebook_visual.html
│
├── credit-card-churn/
│   ├── notebook.ipynb
│   ├── requirements.txt
│   ├── data/
│   │   └── BankChurners.csv
│   └── visuals/
│       └── notebook_visual.html
│
├── personal-loan-campaign/
│   ├── notebook.ipynb
│   ├── requirements.txt
│   ├── data/
│   │   └── Loan_Modelling.csv
│   └── visuals/
│       └── notebook_visual.html
│
├── foodhub/
│   ├── notebook.ipynb
│   ├── requirements.txt
│   ├── data/
│   │   └── foodhub_order.csv
│   └── visuals/
│       └── notebook_visual.html
│
└── stock-market-sentiment/
    ├── notebook.ipynb
    ├── requirements.txt
    ├── data/
    │   └── stock_news.csv
    └── visuals/
        └── notebook_visual.html
```

---

## 🏆 Certifications

- [**AWS Certified AI Practitioner**](https://aws.amazon.com/certification/certified-ai-practitioner/) (2025)
- [**Microsoft Certified: Azure Data Scientist Associate**](https://learn.microsoft.com/en-us/credentials/certifications/azure-data-scientist/) (2024)
- [**Duck Creek Policy Configurator**](https://www.duckcreek.com/training-certification/) (2025)
- [**Power BI Data Analyst Associate**](https://learn.microsoft.com/en-us/credentials/certifications/power-bi-data-analyst-associate/) (2023)
- [**Associate in Insurance (AINS)**](https://www.theinstitutes.org/) (2025)
- **Project Management Professional (PMP)**

---

## 🔮 Future Work

Planned P&C-focused AI/ML projects include:

- **Claims Severity Prediction** (AWS SageMaker)
- **NLP for Claims Analysis** (Azure ML)
- **Fraud Detection Dashboard** (Power BI)
- **Underwriting Risk Assessment Models**
- **Customer Lifetime Value Prediction**

---

## 📞 Contact

For questions, collaborations, or opportunities, please reach out:

- **LinkedIn:** [selvakumar-thirumalainambi](https://www.linkedin.com/in/selvakumar-thirumalainambi)
- **Email:** Available on LinkedIn profile

---

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## 🙏 Acknowledgments

- Post Graduate Program in AI/ML faculty and mentors
- Open-source community for excellent ML libraries and tools
- Dataset providers and contributors

---

**⭐ If you find this portfolio helpful, please consider giving it a star!**
