# Netflix_titles


# 🧹 Data Cleaning and Preprocessing – Netflix Movies and TV Shows

## 📌 Project Overview

This project focuses on cleaning and preprocessing a raw dataset from Kaggle: [Netflix Movies and TV Shows](https://www.kaggle.com/datasets/shivamb/netflix-shows). The objective is to handle missing values, remove duplicates, fix inconsistent formats, and prepare the dataset for analysis or modeling.

---

## 📁 Dataset Info

- **Source**: Kaggle – Netflix Movies and TV Shows
- **File**: `netflix_titles.csv`
- **Features**:
  - `show_id`, `type`, `title`, `director`, `cast`, `country`, `date_added`, `release_year`, `rating`, `duration`, `listed_in`, `description`

---

## 🔧 Cleaning Steps

| Task                            | Action Taken                                  |
|---------------------------------|-----------------------------------------------|
| Missing Values                  | Filled with 'Unknown' or converted accordingly |
| Duplicates                      | Removed using `drop_duplicates()`             |
| Text Standardization            | Used `str.strip().str.lower()/str.title()`    |
| Date Format Fix                 | Converted `date_added` to `datetime` format   |
| Column Header Cleaning          | Renamed to lowercase with underscores         |
| Data Type Conversion            | Converted fields like `release_year` to `int` |

---

## ✅ Final Outcome

- Cleaned file: `netflix_titles_cleaned.csv`
- Total records after cleaning: _(update with actual number)_
- Cleaned and ready for analysis or visualization

---

## 📦 Tools Used

- Python (Pandas)
- Jupyter Notebook / Google Colab

---

## 📝 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/netflix-data-cleaning.git
   cd netflix-data-cleaning
