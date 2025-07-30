Climate Change Modeling

This project analyzes public sentiment on climate change using real Facebook comments from NASA's official climate page. It applies natural language processing (NLP) and machine learning (ML) techniques to explore trends, predict engagement, and project future sentiment distribution.

---

Dataset

- Source: NASA Climate Change Facebook Page (2020–2023)
- Format: CSV (climate_nasa.csv)
- Columns:
  - Date: Timestamp of comment
  - LikesCount: Number of likes
  - CommentsCount: Number of replies
  - ProfileName: Anonymized user identifier
  - Text: The comment text

---

Features

-  EDA – Comment frequency, top likes, comment length analysis
-  Sentiment Analysis – VADER-based sentiment scoring (positive, neutral, negative)
-  Scenario Analysis – Relationship between sentiment, length, and engagement
-  Machine Learning – Predict number of likes using Random Forest Regressor
-  Future Projections – Forecast next month's sentiment distribution using linear regression

---

Technologies Used

- Python 3
- Jupyter Notebook
- Libraries:
  - pandas , numpy , matplotlib , seaborn ,
  - sklearn for ML ,
  - nltk for sentiment analysis.
