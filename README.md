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
⚙️ Installation & Setup
1️⃣ Clone the Repository

git clone https://github.com/your-username/titan-nlp-chatbot.git
cd titan-nlp-chatbot








