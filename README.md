# Stock-sentiment Analysis-NLP

# 📰 News Sentiment Analysis (2017–2021)

## 1️⃣ Project Objectives and Methods  

The primary objective of this project was to perform a **step-by-step sentiment analysis** on the text data in the **'Title'** column of an uploaded CSV file containing news headlines from **January 2017 to April 2021**.  
The analysis aimed to understand the sentiment expressed in the news titles and identify any **trends over time**.  

### 🔧 Key Steps  

1. **Data Loading and Inspection**  
   - Loaded dataset into a **pandas DataFrame**.  
   - Inspected structure, columns, and data types.  

2. **Text Preprocessing**  
   - Converted text to lowercase.  
   - Removed punctuation and stopwords.  
   - Created a new column: `cleaned_title`.  

3. **Sentiment Analysis**  
   - Applied **VADER (Valence Aware Dictionary and sEntiment Reasoner)**.  
   - Extracted:  
     - `sentiment_score` (compound value between -1 to +1).  
     - `sentiment_label` → **POSITIVE, NEGATIVE, NEUTRAL**.  

4. **Trend Analysis**  
   - Calculated **monthly average sentiment score**.  
   - Computed **average sentiment score per label**.  

5. **Visualization**  
   - Generated plots for:  
     - 📈 Monthly average sentiment trend.  
     - 📊 Average sentiment score by label.  

---

## 2️⃣ Key Findings  

- Dataset contained **200,500 news headlines** (with date, URL, pre-existing sentiment/confidence).  
- Analysis primarily used **Title** + **Date**.  

- ✅ **Preprocessing** successfully cleaned the text.  
- ✅ **VADER** produced compound scores & labels:  
  - POSITIVE ≈ **0.42**  
  - NEUTRAL ≈ **0.00**  
  - NEGATIVE ≈ **-0.41**  

- 📈 **Trends over time**:  
  - Sentiment fluctuated between **2017–2021**, reflecting world events.  
  - No consistent dominance of positive or negative.  
  - Slight **increase in positivity** near 2021.  

- 📊 **Distribution of sentiment labels**:  
  - **NEUTRAL** (largest share).  
  - Then **POSITIVE**.  
  - Finally **NEGATIVE**.  
  - Suggests headlines are often presented in an **objective/balanced** manner.  

---

## 3️⃣ Business Implications  

The insights from this analysis can support multiple industries where **news sentiment impacts decisions**.  

- **📰 Media Monitoring & Analysis**  
  - Track sentiment about a **brand, competitor, or industry**.  
  - Detect crises or opportunities.  
  - Measure PR effectiveness.  

- **💹 Investment Decisions**  
  - Sentiment of financial news can indicate **market mood**.  
  - Consistently negative sentiment around a stock/sector may signal **risks**.  

- **📢 Marketing & Advertising**  
  - Tailor campaigns/messages to **match or counter public mood**.  
  - Use sentiment signals to boost engagement.  

- **⚠️ Risk Management**  
  - Identify **negative sentiment trends** early (e.g., regulations, scandals).  
  - Develop mitigation strategies before escalation.  

- **✍️ Content Strategy**  
  - Media firms can learn **which headlines evoke positive, negative, or neutral sentiment**.  
  - Optimize editorial strategy for **audience engagement**.  

---

## 🛠️ Tools & Libraries  

- **Python**  
- **Pandas / NumPy** – Data handling  
- **NLTK (VADER)** – Sentiment analysis  
- **Matplotlib / Seaborn** – Visualization  

---

## 📂 Project Structure  

