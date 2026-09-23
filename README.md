# FUTURE_ML_02
Built an ML-based Support Ticket Classification system using NLP to automatically categorize customer queries into Billing, Technical Issue, Product Inquiry, Refund, and Cancellation, helping support teams manage and prioritize tickets efficiently.
# 🎫 Support Ticket Classification & Prioritization

## 📌 Project Overview

This project uses **Machine Learning and Natural Language Processing (NLP)** to automatically classify customer support tickets into different categories.

The system helps support teams organize customer queries and handle tickets more efficiently.

## 🎯 Objectives

* Classify customer support tickets automatically
* Process and clean text data
* Apply NLP techniques for text classification
* Train a Machine Learning model
* Predict the category of new support tickets

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* NLTK
* Scikit-learn
* TF-IDF
* Multinomial Naive Bayes
* Google Colab / Jupyter Notebook

## 📂 Project Structure

```text
Support-Ticket-Classification/
│
├── Support_Ticket_Classification.ipynb
├── README.md
├── requirements.txt
└── outputs/
    └── predictions.csv
```

## 📊 Ticket Categories

The model classifies tickets into categories such as:

* Billing Inquiry
* Cancellation Request
* Product Inquiry
* Refund Request
* Technical Issue

## 🔄 Project Workflow

1. Load the customer support dataset
2. Clean and preprocess ticket text
3. Convert text into numerical features using **TF-IDF**
4. Train the Machine Learning model
5. Evaluate the model
6. Predict categories for new support tickets

## 📈 Result

The trained model can automatically predict the category of a new customer support ticket based on its description.

### Example

**Input:**

```text
My laptop is not turning on and I need immediate help
```

**Predicted Category:**

```text
Product Inquiry
```

## 📁 Output

Prediction results are stored in:

```text
outputs/predictions.csv
```

## 🚀 Future Improvements

* Improve classification accuracy
* Add ticket priority prediction
* Use advanced NLP models
* Build an interactive support ticket dashboard

## 👩‍💻 Internship Task

**Machine Learning Task 2 – Support Ticket Classification & Prioritization**

Completed as part of the **Future Interns Machine Learning Internship – 2026**.
