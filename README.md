# Stock Market News Sentiment Analysis and Summarization

## Overview  
This project focuses on applying Natural Language Processing (NLP) and AI techniques to analyze financial news sentiment and summarize market-moving events. By understanding how news impacts stock prices, the solution supports investors and analysts in making more informed decisions and developing data-driven trading strategies.

## Objective  
The primary objective was to build an AI-powered pipeline capable of classifying the sentiment of financial news articles and generating weekly summaries of significant positive and negative events. These insights are designed to improve predictive models for stock price movements and optimize investment strategies.

## Dataset  
- **Source:** Provided as part of the project coursework  
- **Key Features:**  
  - Date and news content  
  - Daily stock price data (Open, High, Low, Close)  
  - Trading volume  
  - Sentiment label (`1` = Positive, `0` = Neutral, `-1` = Negative)

## Workflow  
1. **Data Preprocessing & EDA** – Cleaned and analyzed historical news and stock price data to uncover sentiment trends.  
2. **Embedding & Sentiment Modeling** – Generated vector representations using Word2Vec, GloVe, and Sentence Transformers, and built sentiment classification models.  
3. **Summarization Pipeline** – Used large language models (LLMs) to identify and summarize the most impactful weekly events.  
4. **Insights & Recommendations** – Linked sentiment shifts with stock price fluctuations to support trading decisions.

## Results & Key Insights  
- Built an AI-powered sentiment analysis model capable of processing large volumes of news data.  
- Generated concise weekly summaries highlighting critical market-moving events.  
- Enabled investors and analysts to integrate sentiment intelligence into predictive trading models.

## Tech Stack  
- **Language:** Python  
- **Libraries:** Pandas, NumPy, Scikit-learn, Hugging Face Transformers, Gensim  
- **Tools:** Jupyter Notebook / Google Colab  

## Author  
**Sandesh S. Badwaik**  
- [LinkedIn](https://www.linkedin.com/in/sbadwaik/)
