# CodeAlpha Internship Tasks

![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-150458?logo=pandas)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-orange)
![Seaborn](https://img.shields.io/badge/Seaborn-Visualization-4C72B0)
![BeautifulSoup](https://img.shields.io/badge/BeautifulSoup-Web%20Scraping-green)
![NLP](https://img.shields.io/badge/NLP-Sentiment%20Analysis-purple)
![Google Colab](https://img.shields.io/badge/Google%20Colab-Notebook-yellow?logo=googlecolab)

## 📌 About This Repository

This repository contains the projects and tasks completed as part of my **CodeAlpha Internship**.

The internship provided hands-on experience in **Python programming, Web Scraping, Exploratory Data Analysis, Data Visualization, and Natural Language Processing (NLP)**.

The tasks were implemented using **Python and Google Colab**, with a focus on practical data analysis and visualization.

---

## 👩‍💻 Internship Tasks

### 🔹 Task 1 — Web Scraping

**Objective:**  
Collect and extract useful information from a website and organize the data into a structured dataset.

**Website Used:**  
Books to Scrape

**Technologies Used:**
- Python
- Requests
- BeautifulSoup
- Pandas
- Matplotlib

**Data Extracted:**
- Book Title
- Price
- Rating
- Availability
- Product URL

**Work Performed:**
- Sent HTTP requests to the website
- Parsed HTML content using BeautifulSoup
- Extracted book information
- Scraped data from multiple pages
- Created a Pandas DataFrame
- Cleaned and processed the data
- Performed basic analysis
- Exported the dataset as CSV

**Output:**
`CodeAlpha_Task1_Books_Dataset.csv`

📁 Folder: `Task1_Web_Scraping/`

---

### 🔹 Task 2 — Exploratory Data Analysis (EDA)

**Objective:**  
Explore the dataset to identify patterns, trends, relationships, anomalies, and useful insights.

**Technologies Used:**
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- SciPy

**Analysis Performed:**
- Dataset inspection
- Data types analysis
- Missing-value analysis
- Duplicate detection
- Descriptive statistics
- Price analysis
- Rating analysis
- Outlier detection using IQR
- Distribution analysis
- Correlation analysis
- Hypothesis testing
- Data visualization

**Key Concepts:**
- Exploratory Data Analysis
- Statistical Analysis
- Correlation
- Outlier Detection
- Hypothesis Testing

📁 Folder: `Task2_EDA/`

---

### 🔹 Task 3 — Data Visualization

**Objective:**  
Transform data into meaningful visualizations to identify patterns, trends, and relationships.

**Technologies Used:**
- Python
- Pandas
- Matplotlib
- Seaborn

**Visualizations Created:**
- Histogram
- Boxplot
- Bar Chart
- Pie Chart
- Scatter Plot
- Correlation Heatmap
- Count Plot
- Pair Plot
- Category-based visualizations
- Data visualization dashboard

**Analysis Included:**
- Book price distribution
- Rating distribution
- Average price by rating
- Price vs. rating relationship
- Most expensive books
- Availability analysis
- Price distribution by rating

**Output Files:**
- `CodeAlpha_Task3_Processed_Books_Dataset.csv`
- `CodeAlpha_Task3_Data_Visualization.png`

📁 Folder: `Task3_Data_Visualization/`

---

### 🔹 Task 4 — Sentiment Analysis

**Objective:**  
Analyze customer reviews and classify them into **Positive, Negative, and Neutral** sentiments using Natural Language Processing techniques.

**Technologies Used:**
- Python
- Pandas
- NLTK
- TextBlob
- Matplotlib
- Seaborn
- WordCloud

**Steps Performed:**
- Created and prepared customer review data
- Checked missing values
- Removed duplicate reviews
- Cleaned text data
- Removed stopwords
- Calculated sentiment polarity
- Classified reviews into sentiment categories
- Analyzed sentiment by product category
- Performed word-frequency analysis
- Generated word clouds
- Performed basic emotion detection
- Visualized sentiment distributions
- Identified positive and negative reviews
- Generated business insights

**Sentiment Categories:**
- 😊 Positive
- 😐 Neutral
- 😞 Negative

**Output:**
`CodeAlpha_Task4_Sentiment_Analysis.csv`

📁 Folder: `Task4_Sentiment_Analysis/`

---

## 🛠️ Tools & Technologies

| Technology | Purpose |
|------------|---------|
| Python | Programming and analysis |
| Pandas | Data manipulation |
| NumPy | Numerical operations |
| Matplotlib | Data visualization |
| Seaborn | Statistical visualization |
| BeautifulSoup | Web scraping |
| Requests | HTTP requests |
| SciPy | Statistical analysis |
| NLTK | Natural Language Processing |
| TextBlob | Sentiment analysis |
| WordCloud | Text visualization |
| Google Colab | Development environment |
| GitHub | Version control and project hosting |

---

## 📂 Repository Structure

```text
CodeAlpha-Tasks/
│
├── README.md
│
├── Task1_Web_Scraping/
│   ├── Task1_Web_Scraping.ipynb
│   └── CodeAlpha_Task1_Books_Dataset.csv
│
├── Task2_EDA/
│   └── Task2_EDA.ipynb
│
├── Task3_Data_Visualization/
│   ├── Task3_Data_Visualization.ipynb
│   ├── CodeAlpha_Task3_Processed_Books_Dataset.csv
│   └── CodeAlpha_Task3_Data_Visualization.png
│
└── Task4_Sentiment_Analysis/
    └── Task4_Sentiment_Analysis.ipynb
