# 🧠 AI-Powered Product Comparison System using RAG

An intelligent product comparison system that uses **Retrieval-Augmented Generation (RAG)** to compare products based on reviews, ratings, and metadata.

This project combines **semantic search (FAISS)** with **LLM reasoning (Google Gemini)** to generate meaningful, data-driven comparisons.

---

## 🚀 Features

- 🔍 Semantic search using FAISS  
- 🤖 AI-powered comparison using Gemini  
- 📊 Uses real product reviews and ratings  
- ⚡ Fast retrieval with embeddings  
- 🧠 Context-aware results (not generic AI output)  

---

## 🏗️ Tech Stack

- Python  
- FAISS  
- Sentence Transformers (`all-MiniLM-L6-v2`)  
- Google Gemini API  
- NumPy  

---
## 📂 Project Structure


├── data_product.json # Main dataset (JSON)

├── baby_product.csv # Additional dataset (CSV)

├── app.py # Main script

├── README.md # Documentation


---

## 📊 Datasets

This project uses two datasets:

### 1. JSON Dataset
- 📁 `data_product.json`  
- Contains product names, reviews, ratings, and price  

👉 [View JSON Dataset](./data_product.json)

---

### 2. CSV Dataset
- 📁 `baby_product.csv`  
- Contains additional product data  

👉 [View CSV Dataset](./baby_product.csv)

---

## ⚙️ Setup & Installation

### 1. Clone the repository
```bash
git clone https://github.com/Amit-004/AI-Powered-Product-Comparison-System-using-RAG.git
cd AI-Powered-Product-Comparison-System-using-RAG

## Install Dependencies
pip install faiss-cpu numpy sentence-transformers google-generativeai

## API Setup
Get your Gemini API key from:
https://aistudio.google.com/app/apikey

Then update in your code:
GEMINI_API_KEY = "YOUR_API_KEY"



---


## How to Run
python app.py

## How It Works
Loads product datasets (JSON + CSV)
Converts product reviews into embeddings
Stores embeddings in FAISS index
Takes user input (2 products)
Retrieves relevant product data
Sends context to Gemini
Generates structured comparison:
Pros
Cons
Best pick


## Example Output
COMPARISON RESULT

Pros of Product A:
...

Pros of Product B:
...

Best Pick:
...






## 📂 Project Structure
