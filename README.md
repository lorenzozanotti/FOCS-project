# Foundations of Computer Science: Trending YouTube Relational Analysis

---

### 📌 Description
This project was developed as part of the **Foundations of Computer Science** course within the **MSc in Data Science** program at the **University of Milano-Bicocca**.

The project focuses on the advanced manipulation and integration of the **Trending YouTube dataset** using the **Python Pandas** library. The core objective was to solve 15 complex data processing tasks that mirror Relational Algebra operations. The analysis involves merging multi-country CSV files, parsing semi-structured JSON data, and implementing custom logic for temporal clustering and text-based tag analysis.

---

### 🎯 Project Objectives
* **Data Consolidation**: Merging multiple regional CSV files into a unified global dataframe while tracking country origins.
* **Engagement Analysis**: Calculating performance metrics such as like/dislike ratios and identifying top-performing channels by views.
* **Temporal Clustering**: Segmenting video publication times into discrete 10-minute intervals to analyze upload trends.
* **Tag & Category Mapping**: Deconstructing complex tag strings and integrating external JSON category definitions to resolve unassignable classifications.

---

### 🔬 Methodologies Used
The project follows a structured computational workflow to address specific relational challenges:
* **Relational Joins & Concatenation**: Unifying disparate datasets and linking video records with metadata from JSON sources.
* **Data Cleaning & Filtering**: Creating an "excluded" dataframe for videos with disabled features or errors while maintaining a clean primary dataset.
* **String Processing & Tokenization**: Parsing multi-value tag strings to perform frequency counts and cross-country comparisons.
* **Multi-dimensional Aggregation**: Computing group-wise statistics (average ratios, max views) for (tag, country), (trending_date, country), and (month, country) pairs.
* **Time-Series Transformation**: Decomposing date objects into granular components (year, month, day) for longitudinal analysis.

---

### 🛠️ Technologies Used
* **Programming Language**: Python 3.x
* **Data Manipulation**: Pandas, NumPy
* **Semi-Structured Data**: JSON library for category mapping
* **Environment**: Jupyter Notebook (`.ipynb`)
* **Dataset**: Trending YouTube Video Statistics (CSV and JSON)
