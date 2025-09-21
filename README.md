# genai-sentiment-analysis-stock-prediction
Predicting stock market trends using Generative AI and sentiment analysis from financial news and professional forums.

📌 Summary

This project explores how Generative AI and NLP can be applied to analyze professional sentiments from platforms like Reddit, Glassdoor, and financial news sources to improve stock market prediction accuracy. All data was collected using public APIs to ensure freshness and reproducibility. By combining sentiment-driven features with market indicators, the model enhances short-term and medium-term predictive performance.

⚠️ Note: Only publicly available datasets and APIs are used. No proprietary or trading-sensitive data is included.


🎯 Objectives

Extract sentiment data from Reddit, Glassdoor, and financial news APIs.

Use Generative AI (LLMs) to interpret and score sentiment beyond simple polarity.

Combine sentiment insights with stock price time-series features.

Train machine learning and deep learning models to predict market trends.


⚙️ Tech Stack

Languages & Tools: Python, Jupyter Notebooks

ML Frameworks: Scikit-learn, PyTorch

NLP/GenAI: OpenAI GPT models, Hugging Face Transformers

Visualization: Matplotlib, Seaborn

Data Sources: Reddit API, Glassdoor API, Financial News APIs


🚀 Implementation Highlights

Built a data pipeline to collect and clean text data using APIs.

Applied LLMs to perform context-aware sentiment scoring, capturing nuances like optimism, skepticism, or fear.

Integrated sentiment embeddings with historical stock market data.

Trained models including logistic regression, random forests, and deep learning (LSTMs, Transformers).

Benchmarked models on predictive accuracy and correlation with market outcomes.


📊 Results & Business Value

Developed a Generative AI–powered predictive model that leveraged Reddit, Glassdoor, and financial news sentiment to achieve stronger correlation with stock market fluctuations.

Uncovered an 88% correlation between financial report sentiment and Tesla’s stock prices by engineering sentiment pipelines with LLMs (FinBERT, Grok), outperforming news and Reddit baselines.

Validated predictive limits through statistical hypothesis testing, ensuring reliability and robustness.

Demonstrated practical value of professional sentiment as a leading indicator, showing how AI-driven analytics can augment financial decision-making.


⚠️ Challenges Faced

Data Quality: Sentiment from Reddit and Glassdoor can be noisy, requiring advanced filtering and cleaning.

API Limitations: Rate limits and access restrictions made continuous large-scale data extraction challenging.
Sentiment Ambiguity: Sarcasm, slang, and domain-specific jargon required careful handling beyond standard polarity detection.
Model Generalization: Ensuring predictions held across different market conditions (e.g., volatility spikes) was non-trivial.
