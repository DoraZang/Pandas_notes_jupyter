# Pandas Data Analysis Mastery: Learning Notes & Practice Exercises

This repository is a comprehensive collection of my learning journey and practical applications of the Python **Pandas** library. It encompasses conceptual notes, technical summaries, and real-world data analysis exercises designed to demonstrate proficiency in data manipulation, exploratory data analysis (EDA), and financial time-series processing. 

## Key Technical Skills Showcased

* **Data Inspection & Cleaning:** Mastery of handling missing values (NaN), data deduplication, and precise data type casting.
* **Complex Filtering & Indexing:** Expert use of `.loc` and `.iloc` for label-based and integer-based slicing, along with multi-conditional boolean indexing.
* **Table Joins & Merging:** Deep understanding of relational algebra in Pandas, including Inner, Left, Right, and Outer joins with custom suffixes.
* **Time Series Analysis:** Practical experience in parsing date strings, extracting temporal features, and performing time-span slicing on financial datasets.

## Repository Structure

### 1. [Pandas notes.ipynb](./Pandas%20notes.ipynb)
* **Focus:** Exploratory Data Analysis (EDA) and foundational Pandas operations.
* **Highlights:** High-dimensional data inspection, categorical frequency analysis using the Stack Overflow Developer Survey dataset, and professional schema lookup techniques.

### 2. [Pandas data analysis&cleaning.ipynb](./Pandas%20data%20analysis%26cleaning.ipynb)
* **Focus:** Core Pandas CRUD operations, data structures, and data wrangling.
* **Highlights:** Series vs. DataFrame distinctions, in-place data modification, handling missing data (`dropna`, `fillna`), complex filtering, and the use of Lambda functions with `.apply()`, `.map()`, and `.replace()`.

### 3. [Notes-DatesTimeSeries.ipynb](./Notes-DatesTimeSeries.ipynb)
* **Focus:** Financial time-series processing and analysis.
* **Highlights:** Analyzing Ethereum (ETH) historical high-frequency price data, datetime object conversion, parsing date strings, and calculating time-based spans and metrics.

## Datasets Used
* **Stack Overflow Annual Developer Survey:** A massive real-world dataset used to practice complex querying and statistical analysis.
* **Ethereum (ETH) 1h Price Data:** High-frequency financial data used to demonstrate time-series capabilities.

## Getting Started
To explore these notebooks:
1. Clone this repository to your local machine.
2. Ensure you have the following libraries installed:
   ```bash
   pip install pandas matplotlib numpy
   ```
3. Run Jupyter Notebook or JupyterLab to interact with the .ipynb files.
