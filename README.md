# Chat-Database-
AI-Powered E-Commerce Search with Azure AI
# 🚀 AI-Powered E-Commerce Search with Azure AI

## 📌 Project Overview  
This repository contains a **Python-based e-commerce search system** integrated with **Azure AI Search**, allowing users to retrieve relevant product information using **semantic search and vector embeddings**.  

## 🔗 Technologies Used  
- **Azure AI Search** – Semantic search for product indexing  
- **Python (Jupyter Notebooks)** – Data processing and AI model integration  
- **Azure SQL Database** – Storing structured product data
- **FastAPI / Flask** – Backend API for search queries  
- **GitHub Actions** – Automating workflows  

## 🛠️ Setup Guide  
### **1️⃣ Clone the Repository**  
```bash
git clone https://github.com/Isha-Rana-Dahiya/Chat-Database.git
cd Chat-Databse

## Install dependencies
pip install -r requirements.txt

## Configure AI Search
Create Azure AI Service and define the index (azureblob_index2)
Upload dataset1 and configure semantic search

## Run the Application
python app.py

## Dataset Information
File : Dataset1.xlsx
Columns:
source_unique_id : Unique identifier
category : product category
sale_price : proce in USD
available : stock status
description : short product description 
