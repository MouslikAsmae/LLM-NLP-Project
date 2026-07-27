# 🤖 Helpdesk Ticket Classification and Response Suggestion using NLP & Large Language Models

## 📌 Project Overview

This project aims to improve IT Helpdesk support by automatically analyzing customer support tickets and generating relevant response suggestions using Natural Language Processing (NLP) and Large Language Models (LLMs).

The workflow combines text preprocessing, semantic retrieval with TF-IDF, and Google's **Flan-T5** model to generate context-aware responses based on similar historical tickets.

---

## 🎯 Objectives

* Clean and preprocess helpdesk tickets.
* Analyze ticket content using NLP techniques.
* Retrieve the most relevant historical tickets.
* Generate response suggestions using a Large Language Model.
* Demonstrate an end-to-end AI workflow for customer support automation.

---

## 📂 Dataset

The project uses a Helpdesk Customer Tickets dataset containing information such as:

* Ticket Subject
* Ticket Description
* Existing Answer
* Ticket Type
* Priority
* Queue
* Language
* Business Type
* Tags

---

## 🛠 Technologies Used

* Python
* Pandas
* NumPy
* NLTK
* Scikit-learn
* TF-IDF Vectorization
* Cosine Similarity
* Hugging Face Transformers
* Google Flan-T5
* Matplotlib
* Seaborn

---

## 📊 Project Workflow

### 1. Data Loading

The Helpdesk dataset is imported and explored.

### 2. Data Preprocessing

* Remove unnecessary columns
* Handle missing values
* Normalize text
* Tokenization
* Stopword removal
* Stemming
* Text cleaning

### 3. Ticket Analysis

The ticket subject and description are combined into a single text representation for analysis.

### 4. Similar Ticket Retrieval

TF-IDF vectorization and cosine similarity are used to retrieve the most relevant historical tickets.

### 5. Response Generation

The retrieved tickets are used as context for **Google Flan-T5**, which generates a response suggestion for the new ticket.

---

## 🤖 AI Model

Large Language Model:

* Google Flan-T5 Base

Retrieval Method:

* TF-IDF
* Cosine Similarity

---

## 📈 Project Features

* Text preprocessing
* Ticket similarity search
* AI-assisted response generation
* NLP pipeline
* Retrieval-Augmented response generation
* Helpdesk automation

---

## 📁 Project Structure

```text
Helpdesk-Ticket-Classification/
│
├── classification_des_tickets_et_suggestion_des_reponse.ipynb
├── helpdesk_customer_tickets.csv
├── README.md
└── requirements.txt
```

---

## 🚀 How to Run

1. Clone this repository.

```bash
git clone https://github.com/yourusername/helpdesk-ticket-classification.git
```

2. Install the required libraries.

```bash
pip install pandas numpy nltk scikit-learn transformers torch matplotlib seaborn
```

3. Download the dataset and place it in the project folder.

4. Run the notebook.

---

## 💡 Future Improvements

* Replace TF-IDF with semantic embeddings.
* Integrate a vector database such as FAISS or Chroma.
* Deploy the solution as a web application.
* Fine-tune an open-source LLM on historical helpdesk conversations.
* Add multilingual support.

---

## 👩‍💻 Author

**Asmae Mouslik**

Master's Degree in Data Science for Management and Artificial Intelligence
LinkedIn: www.linkedin.com/in/asmae-mouslik-a1b546243


