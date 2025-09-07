# Playstore Reviews Sentiment Analysis

[![Python](https://img.shields.io/badge/Python-3.10%2B-blue)](https://www.python.org/)  
[![Google Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/)  
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](https://opensource.org/licenses/MIT)  
[![Status](https://img.shields.io/badge/Status-Active-success.svg)]()  

---

## 📌 Overview
This project analyzes Google Playstore reviews to classify them into **positive, negative, and neutral**.  
The goal is to identify user satisfaction, detect main complaints, and provide actionable recommendations for app improvement.

---

## 🎯 Objectives
- Classify reviews by sentiment.  
- Summarize positive & negative reviews using **LLM**.  
- Extract keywords and visualize them with WordClouds & graphs.  
- Generate insights and recommendations with `agent.invoke`.  

---

## 🔑 Key Findings
- **Positive** → Users describe the app as *good, useful, reliable*.  
- **Negative** → Complaints about *spam, update errors, sudden crashes*.  
- **Biggest Issues** → App stability & spam handling.  

---

## ✅ Recommendations
- Strengthen **spam detection**.  
- Improve **stability & error handling**.  
- Use **staged rollouts** for updates.  
- Add **in-app support** for faster issue reporting.  

---

## 🚀 How to Use
1. Open the notebook in **Google Colab**.  
2. Run preprocessing & sentiment analysis.  
3. Generate WordClouds, graphs, and summaries.  
4. Review insights for product decisions.  



## 📂 Repository Structure
📦 playstore-sentiment-analysis
┣ 📜 sentiment_analysis.ipynb # Main Colab notebook
┣ 📜 README.md # Project documentation
┣ 📂 data/ # (Optional) Review dataset
┣ 📂 outputs/ # WordClouds & graphs
