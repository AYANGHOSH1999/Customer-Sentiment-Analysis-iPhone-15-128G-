# 📱 Customer Sentiment Analysis – iPhone 15 (128GB)

This project performs a sentiment analysis on customer reviews of the iPhone 15 (128GB) using web scraping and natural language processing techniques. The analysis extracts user opinions from online sources and classifies them into positive, negative, and neutral sentiments.

## 📊 Overview

- **Target Product**: iPhone 15 (128GB)
- **Data Source**: Flipkart (scraped using Selenium + BeautifulSoup)
- **Sentiment Tool**: TextBlob
- **Visualization**: Matplotlib & WordCloud

---

## 🧰 Tools & Libraries

- **Python 3.10+**
- `Selenium` – For browser automation and review scraping
- `BeautifulSoup` – HTML parsing
- `Pandas` – Data manipulation
- `TextBlob` – Sentiment analysis
- `Matplotlib` & `WordCloud` – Data visualization

---

## 📁 Project Structure

Customer-Sentiment-Analysis-iPhone15/
│
├── Customer Sentiment Analysis(iPhone 15 128G).ipynb # Main notebook
├── requirements.txt # Required libraries
└── README.md # Project description


---

## ⚙️ How It Works

1. **Scraping Reviews**:  
   Using Selenium to load the Flipkart page dynamically and BeautifulSoup to extract review data.

2. **Data Cleaning**:  
   Cleaning the extracted text to remove unwanted characters and symbols.

3. **Sentiment Classification**:  
   - TextBlob calculates polarity score:
     - `> 0`: Positive
     - `< 0`: Negative
     - `= 0`: Neutral
---

## 📸 Sample Outputs

- **Sentiment Distribution**
  ![sentiment-pie](images/sentiment_pie.png)

- **Word Cloud**
  ![wordcloud](images/wordcloud.png)

---

## 📌 Key Findings

- Most users had a **positive** experience with iPhone 15 128GB.
- Frequent mentions include **camera**, **battery**, and **performance**.
- Some **negative feedback** focused on **price** and **heating issues**.

---

## 🚀 Getting Started

### 1. Clone the Repository
```bash
git clone https://github.com/your-username/iphone15-sentiment-analysis.git
cd iphone15-sentiment-analysis

3. Run the Notebook
Open Customer Sentiment Analysis(iPhone 15 128G).ipynb in Jupyter and execute all cells.

📝 To-Do
Integrate sentiment analysis using VADER or transformers for better accuracy

Deploy as a web app using Streamlit or Flask

Expand to other models (e.g., iPhone 15 Pro, Android phones)

📬 Contact
Made with ❤️ by [Ayan Ghosh]
****  
📍 Howrah, West Bengal, India   |
🌐 [GitHub](https://github.com/AYANGHOSH1999)
📧 ayanghosh6291@gmail.com  
🔗 [LinkedIn](https://www.linkedin.com/in/ayan-ghosh-b9955933a/)
---

