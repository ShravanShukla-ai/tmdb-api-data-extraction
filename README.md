# 🎬 TMDB Top Rated Movies - API Data Extraction Project

![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-yellow?logo=pandas)
![API](https://img.shields.io/badge/API-TMDB-green)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-yellow?logo=pandas)
![Status](https://img.shields.io/badge/Data-Extraction-Completed-brightgreen)

---

## 📌 Project Overview

This project extracts **10,000 top-rated movies** from the **TMDB (The Movie Database) API** using Python.

The dataset was collected programmatically with:
- API authentication
- Pagination handling (500 page limit)
- Rate limiting management
- HTTP error handling (400 & connection reset)
- Clean export to CSV format

---

## 🚀 Key Features

- ✅ API Authentication using Bearer Token
- ✅ Dynamic Pagination Handling
- ✅ Rate Limit Protection
- ✅ Error Handling & Retry Logic
- ✅ Data Export to CSV
- ✅ Clean & Structured Dataset

---

## 🛠 Tech Stack

- **Python**
- **Pandas**
- **Requests**
- **TMDB API**

---

## 📊 Dataset Information

- 📦 Total Records: **10,000**
- 📁 Columns:
  - `id`
  - `title`
  - `overview`
  - `release_date`
  - `vote_count`
  - `vote_average`

---
## 📸 Sample Output

Example of extracted dataset:

| id | title | vote_average |
|----|-------|-------------|
| 278 | The Shawshank Redemption | 8.7 |
| 238 | The Godfather | 8.6 |

--- 

## 📁 Project Structure

tmdb-api-data-extraction/
│
├── api-to-dataframe.ipynb
├── tmdb_top_rated_movies.csv
└── README.md

---

## ▶ How To Run This Project

1. Clone the repository:

git clone https://github.com/ShravanShukla-ai/tmdb-api-data-extraction.git

2. Install required libraries:

pip install pandas requests

3. Replace YOUR_ACCESS_TOKEN with your TMDB API key.

4. Run the notebook:

api-to-dataframe.ipynb
---

## 🧠 Skills Demonstrated

- API Integration
- Pagination Handling
- Rate Limit Management
- Error Handling
- Data Cleaning
- Dataset Publishing (Kaggle)
- GitHub Project Documentation
---

## 📌 Kaggle Dataset

Dataset available on Kaggle:

👉 https://www.kaggle.com/datasets/shravanshukla/tmdb-top-rated-movies-dataset-api-extracted

---

## 👨‍💻 Author

**Shravan Shukla**  
BSc Computer Science Student  
Aspiring Data Analyst  

---

## ⭐ If you found this useful, consider giving it a star!


