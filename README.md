# Support Ticket Classification & Prioritization

## Overview

This project was developed as part of the Future Interns Machine Learning Internship Program.

The objective of this project is to automatically classify customer support tickets into different categories and predict ticket priority levels using Natural Language Processing (NLP) and Machine Learning techniques.

---

## Objective

Build a machine learning system that can:

* Classify support tickets into categories
* Predict ticket priority levels
* Improve ticket routing efficiency
* Help support teams respond faster to customer issues

---

## Technologies Used

* Python
* Pandas
* NumPy
* NLTK
* Scikit-learn
* Matplotlib
* Seaborn
* Jupyter Notebook

---

## Dataset

**Customer Support Ticket Dataset**

Dataset contains:

* Ticket Description
* Ticket Type
* Ticket Priority
* Ticket Status
* Customer Information

---

## Project Workflow

### 1. Data Collection

Loaded customer support ticket dataset.

### 2. Data Cleaning

Handled missing values and selected relevant columns.

### 3. Text Preprocessing

* Lowercasing
* Removing punctuation
* Removing stopwords

### 4. Feature Extraction

Used TF-IDF Vectorization to convert text into numerical features.

### 5. Ticket Type Classification

Built a Machine Learning model to classify support tickets into categories such as:

* Billing Inquiry
* Technical Issue
* Product Inquiry
* Refund Request
* Cancellation Request

### 6. Priority Prediction

Built a model to predict ticket priority levels:

* Critical
* High
* Medium
* Low

### 7. Model Evaluation

Evaluated performance using:

* Accuracy Score
* Classification Report
* Confusion Matrix

### 8. Visualization

Created visualizations for:

* Ticket Type Distribution
* Priority Distribution
* Confusion Matrix

---

## Results

### Ticket Type Classification Accuracy

18.36%

### Priority Prediction Accuracy

24.91%

---

## Visualizations

### Confusion Matrix

Displays model predictions versus actual ticket categories.

### Ticket Type Distribution

Shows frequency of different ticket categories.

### Priority Distribution

Shows frequency of ticket priority levels.

---

## Business Impact

This solution helps organizations:

* Automatically categorize support tickets
* Prioritize urgent customer issues
* Reduce manual ticket sorting effort
* Improve customer support response times
* Increase operational efficiency

---

## Project Structure

FUTURE_ML_02

├── README.md

├── TicketClassification.ipynb

├── customer_support_tickets.csv

├── project_summary.txt

├── confusion_matrix.png

├── ticket_type_distribution.png

└── priority_distribution.png

---

## Author

**Sai Rakesh**

Future Interns – Machine Learning Internship (2026)
