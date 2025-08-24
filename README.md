# Project Vayu: News Headline Analysis

An NLP project that analyzes the sentiment and topics of over 200,000 news headlines from the HuffPost between 2012 and 2022. This project uses Python and popular data science libraries to uncover insights from a large text dataset.

---

##  Project Summary

In an age of information overload, it's impossible to manually track the dominant themes and emotional tones of the news. This project tackles that challenge by applying a complete Natural Language Processing (NLP) pipeline to a massive dataset of headlines. The goal is to move beyond anecdotal evidence and provide a quantitative, data-driven view of the media landscape.

### Key Analyses Performed:
1.  **Sentiment Analysis:** Each headline is classified as **Positive**, **Negative**, or **Neutral** to gauge the overall emotional tone of the news.
2.  **Topic Modeling:** An unsupervised machine learning model (LDA) was used to discover the 10 most prominent hidden topics within the headlines, revealing the core subjects of public discourse.

---

##  Key Features

* **Data Cleaning:** A robust preprocessing pipeline to tokenize, stem, and remove stopwords from raw text data.
* **Sentiment Classification:** Utilizes the VADER sentiment model to accurately score headlines.
* **Unsupervised Topic Discovery:** Employs Latent Dirichlet Allocation (LDA) to identify 10 distinct topics, including US Politics, Crime & Law Enforcement, and Family & Lifestyle.
* **Data Visualization:** Clear and insightful charts created with Matplotlib to present the findings.

---

##  Tech Stack

* **Language:** Python 3
* **Environment:** Google Colab
* **Core Libraries:**
    * `pandas` for data manipulation
    * `nltk` for text preprocessing and sentiment analysis
    * `scikit-learn` for topic modeling (LDA)
    * `matplotlib` & `wordcloud` for visualization

---

##  Getting Started

### Prerequisites

To run this analysis yourself, you will need a Python environment with the libraries listed above. The easiest way is to open the `Project_Vayu_Analysis.ipynb` notebook in Google Colab, which has everything pre-installed.

### Dataset

This project uses the **"News Category Dataset"** from Kaggle, which contains over 200,000 news headlines from HuffPost.

* **To get the data:**
    1.  Go to the dataset page on Kaggle: [https://www.kaggle.com/datasets/rmisra/news-category-dataset](https://www.kaggle.com/datasets/rmisra/news-category-dataset)
    2.  Click the "Download" button.
    3.  Unzip the file and you will find `News_Category_Dataset_v3.json`. This is the file used in the notebook.

### Installation & Execution

1.  Clone this repository to your local machine:
    ```bash
    git clone [https://github.com/shahirun-x/Project-Vayu-News-Headline-Analysis.git](https://github.com/shahirun-x/Project-Vayu-News-Headline-Analysis.git)
    ```
2.  Upload both the `Project_Vayu_Analysis.ipynb` notebook and the `News_Category_Dataset_v3.json` file to a Google Colab session.
3.  Run the cells in the notebook sequentially to reproduce the analysis.
