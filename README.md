# 💎 Titan Company Chatbot & NLP Analyzer

An interactive **Streamlit-based Natural Language Processing (NLP) application** that analyzes the **Titan Company Limited Annual Report (2023–24)**.  
This project combines a **rule-based chatbot** with **sentiment analysis, word frequency visualization, and topic modeling** to extract meaningful insights from corporate text data.

---

## 📌 Project Overview

Annual reports contain vast amounts of textual information that are difficult to analyze manually.  
This project demonstrates how **NLP techniques** can be applied to automatically interpret corporate documents and provide:

- Intelligent question–answering via a chatbot  
- Sentiment insights from user interactions  
- Thematic discovery using topic modeling  
- Interactive visual analytics through Streamlit  

---

## 🚀 Features

### 🤖 Titan Company Chatbot
- Answers questions related to:
  - Company overview
  - Brands & products
  - Financial performance
  - Customer support
- Uses **intent detection** with predefined response categories

### 😊 Sentiment Analysis
- Analyzes user messages using **TextBlob**
- Displays:
  - Sentiment polarity (Positive / Neutral / Negative)
  - Average sentiment score
  - Most positive and negative messages

### ☁️ Word Frequency & Word Cloud
- Extracts frequently used words from chat interactions
- Generates an interactive **WordCloud**
- Highlights dominant terms in conversations

### 🧠 Topic Modeling (LDA)
- Uses **Latent Dirichlet Allocation (LDA)** to discover hidden topics
- Sidebar control to adjust the number of topics
- Displays top keywords for each topic

### 📊 Interactive Dashboard
- Built entirely with **Streamlit**
- Custom UI styling with CSS
- Tab-based layout for easy navigation

### 📂 Chat Export
- Option to export chat history for further analysis

---

## 🏗️ Tech Stack

- **Application Framework**: Streamlit  
- **NLP**: TextBlob, NLTK  
- **Machine Learning**: Scikit-learn  
- **Data Processing**: Pandas, NumPy  
- **Visualization**: Matplotlib, WordCloud  

---

## 📁 Project Structure

```bash
├── chatbot_app.py                  # Main Streamlit application
├── Titan_nlp_project.ipynb          # NLP experimentation notebook
├── Titan Annual Report 2023-24.pdf  # Dataset (Annual Report)
├── miniProjectReport(titan).docx    # Project documentation
├── requirements.txt                # Python dependencies
└── README.md                        # Project README


```
---
⚙️ Installation & Setup
1️⃣ Clone the Repository

```
git clone https://github.com/your-username/titan-nlp-chatbot.git
cd titan-nlp-chatbot

```

2️⃣ Create a Virtual Environment (Recommended)
```
python -m venv venv
source venv/bin/activate      # Windows: venv\Scripts\activate
```
3️⃣ Install Dependencies
```
pip install -r requirements.txt
```
4️⃣ Run the Streamlit App
```
streamlit run chatbot_app.py
```
---
## 🧪 NLP Techniques Used

### Text Preprocessing
- Tokenization  
- Stopword removal  
- Normalization  

### Sentiment Analysis
- Polarity-based scoring using **TextBlob**

### Word Frequency Analysis
- CountVectorizer  
- WordCloud visualization  

### Topic Modeling
- Latent Dirichlet Allocation (**LDA**)

---

## 📊 Dataset Information

- **Source**: Titan Company Limited – 40th Annual Report (2023–24)  
- **Type**: Corporate document (PDF)

### Content Includes
- Company overview  
- Financial performance  
- Brand strategy  
- Sustainability & CSR  
- Governance & leadership  

---

## 🎯 Project Objective

The primary objective of this project is to showcase how **Natural Language Processing (NLP)** can be used to:

- Automatically analyze large corporate documents  
- Extract sentiment and thematic insights  
- Build an interactive analytical dashboard using **Streamlit**  
- Improve understanding of business communication and strategy  

---

## 🌐 Live Demo

🚀 **Streamlit Application**  
🔗 https://nlp-titan-analysis-chatbot-sainath-goud-l049.streamlit.app/

---

## 👨‍💻 Author

**Sainath Goud**  
B.Tech – Computer Science & Engineering (Data Science)

- NLP & Machine Learning  
- Streamlit Applications  
- Data Analytics  

---

## 📜 License

This project is developed for **academic and educational purposes only**.  
All company-related data and brand references belong to **Titan Company Limited**.



