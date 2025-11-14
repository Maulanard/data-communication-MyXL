# 📊 Data Communication Analysis — MyXL  
Analyzing Customer Interaction Patterns and Their Impact on Brand Awareness

## 📁 Project Overview
This project analyzes customer reviews related to **MyXL**, focusing on how user sentiment and interaction patterns affect overall **brand awareness**.  
The workflow includes data cleaning, sentiment scoring using VADER, visualization created fully in Excel (bar + horizontal bar + line charts), and a final PDF report.

---

## 📁 Project Files
- [📊 myxl_data_communication.xlsx](myxl_data_communication.xlsx)
- [📄 myxl_sentiment_report.pdf](myxl_sentiment_report.pdf)

---

## 🔧 Tools & Libraries Used
- **Python (Google Colab)** – sentiment scoring  
- Pandas  
- NLTK + VADER SentimentIntensityAnalyzer  
- **Excel** – all charts created here (bar, horizontal bar, line)  
- Canva – final report design  

---

## 🛠 Project Workflow (Step-by-Step)

### **1. Data Cleaning (Excel)**
- Removed duplicates  
- Standardized text formatting (lowercase, trimming spaces)  
- Cleaned symbol noise  
- Checked for missing values  
- Prepared dataset for sentiment analysis  

### **2. Sentiment Analysis (Google Colab)**
- Imported Excel dataset using Pandas  
- Applied `SentimentIntensityAnalyzer`  
- Generated sentiment scores: positive, neutral, negative, compound  
- Categorized each review into sentiment classes  
- Exported sentiment-labeled dataset back to Excel  

### **3. Visualization in Excel (Full Process)**
All charts were created manually in Excel:

- **Vertical Bar Chart**  
  - Used to compare sentiment score distributions  
  - Also used to highlight issue frequencies  

- **Horizontal Bar Chart**  
  - Used to show ranking of user pain points from most frequent to least  

- **Line Chart**  
  - Used to visualize sentiment trend over time  

Formatting included:
- Clear labeling  
- Highlight colors  
- Data-driven sorting for easier interpretation  

### **4. Insight Development**
Insights were constructed based on:
- Volume distribution of sentiment  
- Visual patterns from charts  
- Reoccurring user pain points  
- Customer perception shifts  

### **5. Final Report**
- Visuals and insights were compiled into a PDF  
- Designed in Canva for structured storytelling and readability  

---

## 🔍 Key Insights

### ⭐ 1. Negative Sentiment Dominates  
Negative reviews form the largest portion, mainly driven by app performance issues.

### ⭐ 2. Top User Issues Identified
Visualized using horizontal bar charts:
- Slow or lagging application  
- Login errors preventing account access  
- Data package activation delays  

### ⭐ 3. Positive Sentiment Does Exist  
Mostly related to:
- Fast package activation  
- Useful promotional offers  

### ⭐ 4. Trend Analysis (Line Chart)
Sentiment fluctuates over time, with clear negative spikes during:
- App disruptions  
- System errors  
- Sudden performance drops  

### ⭐ 5. Impact on Brand Awareness
Negative customer experiences influence:
- Trust in MyXL’s digital services  
- Satisfaction with the mobile app  
- Overall brand perception  

---

## 📈 Excel Visualizations Included
- Vertical bar chart (sentiment distribution)  
- Horizontal bar chart (top issues ranking)  
- Line chart (sentiment trend over time)

All visuals are included inside **report_myxl.pdf**.

---

## 🎯 Conclusion
Analysis shows that:
- MyXL’s digital experience strongly influences customer sentiment  
- Repeating technical issues significantly reduce brand awareness  
- Enhancing app performance will help improve customer perception and trust  

---

## 👤 Created by  
**Maulana — Data Analytics Learner**
