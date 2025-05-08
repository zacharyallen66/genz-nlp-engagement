💬 Gen Z NLP Engagement Project
A sentiment-driven NLP pipeline that helps brands engage authentically with Gen Z and other chronically-online audiences using advanced topic modeling and large language models. Built using BERTopic, OpenRouter, and real Twitter data from the Sentiment140 dataset.

🧠 Overview
Modern brands struggle to connect with younger audiences who speak in memes, slang, emojis, and culturally nuanced language. This project demonstrates how to:

Understand trending topics using BERTopic and sentiment clustering

Generate human-like, Gen Z–style replies using OpenRouter LLM prompts

Scale social media engagement with personalized yet automated messaging

This pipeline helps organizations transition from passive listening to active participation in online dialogue — staying relevant and relatable across platforms.

📸 Example Output
BERTopic Cluster Visualization	LLM-Based Gen Z Replies
![image](https://github.com/user-attachments/assets/10069787-c136-4692-b3c4-716f0f3ace93)
![newplot (6)](https://github.com/user-attachments/assets/417d42e8-ff9b-42b8-a408-1058d9c154cc)

🔍 Core Technologies
BERTopic — Topic modeling of sentiment-tagged tweets

OpenRouter — Prompt-based LLMs for reply generation

Sentiment140 — Pre-labeled Twitter dataset (160k+ tweets)

Scikit-learn, UMAP, HDBSCAN — For vectorization and clustering

Pandas / Matplotlib — Data processing and visualizations

🔗 Dataset
This project uses the Sentiment140 dataset, which contains 1.6 million tweets labeled as positive or negative sentiment.

📥 Kaggle Dataset: [Sentiment140](https://www.kaggle.com/datasets/kazanova/sentiment140)

Note: You must be signed into Kaggle and accept the license to download the dataset.

🚀 Run It Locally
bash
Copy
Edit
git clone https://github.com/zacharyallen66/genz-nlp-engagement.git
cd genz-nlp-engagement

# (Optional) Create a virtual environment
conda create -n genz_nlp python=3.9
conda activate genz_nlp

# Install requirements
pip install -r requirements.txt

# Launch notebook or script
jupyter notebook Group_Projv1.1.ipynb
📎 Project Structure
bash
Copy
Edit
├── Group_Projv1.1.ipynb           # Main notebook: analysis + LLM response generation
├── data/                          # Local copy of Sentiment140 (after download)
├── assets/                        # Visuals (clustering, Gen Z replies)
├── requirements.txt              # Project dependencies
├── README.md
💡 Use Cases
Customer sentiment classification

Social media brand engagement

Automatic Gen Z-style tweet replies

Trend identification and campaign feedback

Cultural sentiment shifts over time

