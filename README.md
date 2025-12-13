**📊 Social Media Sentiment Analysis (Sentiment140)**

**📌 Project Overview**

This project performs sentiment analysis on Twitter data using the Sentiment140 dataset.
The goal is to analyze public opinions by classifying tweets into Positive, Negative, and Neutral sentiments and preparing the data for visualization and business insights.

**📂 Dataset**
Name: Sentiment140 Dataset
Source: Kaggle
Size: 1.6 million tweets
Format: CSV (no header)

| Column | Description                                  |
| ------ | -------------------------------------------- |
| target | Sentiment label (0 = Negative, 4 = Positive) |
| id     | Tweet ID                                     |
| date   | Tweet timestamp                              |
| flag   | Query flag                                   |
| user   | Twitter username                             |
| text   | Tweet content                                |

**🛠️ Technologies Used**

Python
Pandas & NumPy
NLTK (VADER Sentiment Analyzer)
Matplotlib
WordCloud
Power BI (for visualization)

**🔍 Project Workflow**
1. Loaded Sentiment140 dataset and defined column headers manually

2. Cleaned tweet text (removed URLs, special characters, lowercase conversion)

3. Applied VADER sentiment analysis to generate sentiment scores

4. Classified tweets into Positive, Negative, and Neutral

5. Exported processed data for Power BI analysis

6. Prepared dataset for dashboard visualization

**📁 Project Structure**
Social-Media-Sentiment-Analysis/

│
├── app.py

├── requirements.txt

├── sentiment140_powerbi.csv

├── README.md

└── data/

    └── training.1600000.processed.noemoticon.csv
    
**▶️How to Run the Project**

pip install -r requirements.txt
streamlit run app.py

**📊 Output**

* Sentiment classification for each tweet
* Sentiment distribution insights
* Clean dataset ready for Power BI dashboard
* Word cloud visualization of frequent terms

**🧠 Key Learnings**

Practical application of Natural Language Processing

Handling large real-world datasets

Text preprocessing techniques

Sentiment analysis using lexicon-based models

Data preparation for business intelligence tools

**🚀 Future Enhancements**

Implement BERT-based sentiment analysis

Real-time Twitter data scraping

Advanced Power BI dashboard

Topic modeling on tweets

**📌 Author**

Dharshini
B.E. Computer Science and Engineering
Aspiring Data Scientist

**📎 License**
This project is created for educational and portfolio purposes.
