CODTECH Data Analysis Internship – Final Submission

Welcome! This repository contains my completed tasks for the **CODTECH Data Analysis Internship**. All four required tasks have been completed using tools like PySpark, Scikit-learn, Power BI, and NLP libraries (VADER).

Due to GitHub upload limits, the dataset (`IMDB Dataset.csv`) used in these tasks is stored on Google Drive:

🔗 [Download Dataset (63 MB)](https://drive.google.com/file/d/1pEb8lwSBY12PHAlJCV57YAyOw_g-w-NZ/view?usp=drive_link)
Tasks Overview

### Task 1: Big Data Analysis using PySpark
- **Objective**: Perform analysis on a large dataset using scalable big data tools
- **Tools**: PySpark, Google Colab
- **Actions**:
  - Loaded the IMDB review dataset
  - Added custom feature: `review_length`
  - Grouped by sentiment to calculate average review length and count
- **Deliverable**: [`task1_bigdata.ipynb`](./task1_bigdata.ipynb)



### Task 2: Machine Learning – Sentiment Prediction
- **Objective**: Build a classification model to predict sentiment (positive/negative)
- **Tools**: Python, Scikit-learn, TF-IDF, Logistic Regression
- **Steps**:
  - Preprocessed text reviews
  - Converted text to vectors using TF-IDF
  - Trained logistic regression model
  - Evaluated using accuracy and classification report
- **Deliverable**: [`task2_machine_learning.ipynb`](./task2_machine_learning.ipynb)

---

### Task 3: Interactive Dashboard using Power BI
- **Objective**: Visualize insights from the IMDB dataset in an interactive dashboard
- **Tool Used**: Power BI Desktop
- **Visuals Included**:
  - Review Count by Sentiment
  - Average Review Length by Sentiment
  - Slicer for interactive filtering
- **Deliverable**: [`task3_dashboard.pbix`](./task3_dashboard.pbix)


### Task 4: Sentiment Analysis using NLP
- **Objective**: Perform sentiment analysis on text data using NLP techniques
- **Tools**: VADER Sentiment Analyzer, Matplotlib, Seaborn
- **Steps**:
  - Cleaned and preprocessed text
  - Applied VADER to analyze sentiment
  - Compared with original labeled sentiment
  - Visualized sentiment distribution
- **Deliverable**: [`task4_sentiment_analysis.ipynb`](./task4_sentiment_analysis.ipynb)
