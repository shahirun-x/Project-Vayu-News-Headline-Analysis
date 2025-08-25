# Project Vāyu: Interactive News Headline Dashboard

An NLP project that analyzes over 200,000 news headlines and presents the findings in a fully interactive web application built with Streamlit.

---

##  Project Summary

This project transforms a static data analysis into a dynamic, interactive dashboard. It analyzes over 200,000 news headlines from the HuffPost (2012-2022) to uncover trends in public discourse. The final product is a web application where users can filter data by date and news category to explore sentiment, topic popularity, and key terms in real-time.

### Key Analyses Performed:
1.  **Sentiment Analysis:** Classifies each headline as **Positive**, **Negative**, or **Neutral**.
2.  **Topic Modeling:** Discovers the 10 most prominent hidden topics within the headlines.
3.  **Predictive Modeling:** Includes a trained model that can classify news categories from headline text.

---

##  Dashboard Features

* **Interactive Sidebar:** Filter the entire analysis by a specific **date range** or by selecting/deselecting **news categories**.
* **Dynamic Visualizations:** All charts (Sentiment Pie Chart, Topic Popularity, Word Cloud) update instantly based on user selections.
* **Key Metrics:** An overview panel showing the total number of headlines being analyzed based on the current filters.
* **Data Explorer:** An expandable table to view the raw, filtered data.

---

##  Tech Stack

* **Language:** Python 3
* **Dashboard:** Streamlit
* **Core Libraries:**
    * `pandas` for data manipulation
    * `nltk` for text preprocessing and sentiment analysis
    * `scikit-learn` for topic modeling and predictive modeling
    * `matplotlib`, `seaborn`, & `wordcloud` for visualization

---

##  Getting Started

### Prerequisites

You must have Python 3 installed on your machine.

### Installation & Execution

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/shahirun-x/Project-Vayu-News-Headline-Analysis.git](https://github.com/shahirun-x/Project-Vayu-News-Headline-Analysis.git)
    cd Project-Vayu-News-Headline-Analysis
    ```

2.  **Install the required libraries:**
    ```bash
    pip install streamlit pandas matplotlib seaborn wordcloud scikit-learn nltk
    ```

3.  **Run the Streamlit app:**
    ```bash
    python -m streamlit run app.py
    ```

Your web browser will automatically open a new tab with the interactive dashboard.

---
### Original Analysis

The initial data exploration, text preprocessing, and model training steps can be found in the Jupyter Notebook: `Project_Vayu_Analysis.ipynb`.
