# sentiment-employee-reviews-analysis-IBM-Granite
Sentiment Employee Reviews Analysis using IBM Granite and Visualization

# 📝 Sentiment Analysis of Employee Reviews  
## 📌 Project Overview  
This project analyzes **29,273 employee reviews** from 6 startups.  
The focus is to extract insights about workplace conditions using **sentiment analysis** and classification into workplace categories.  
The analysis supports understanding what matters most for **Gen Z in the workplace**.  

## 📂 Dataset  
- Source: [Kaggle - Employee Reviews Dataset](https://www.kaggle.com/datasets/fireball684/hackerearthericsson/data)  
- Local filename: `Employee Review.csv` (original: test.csv)
- Size: 29,273 reviews  
- Key Columns:  
  - `Place` → Startup name  
  - `job_title` → Employee role  
  - `status` → Current / Former employee  
  - `location` → Location Startup
  - `summary` → Short review text  
  - `positives` → Positive highlights  
  - `negatives` → Negative highlights  
  - `date` → Review date  
  - `score_1` to `score_6` → Numerical scores (1–6)  

## ⚙️ Analysis Process  
1. **Data Cleaning** → Handle NaN, remove duplicates, remove irrelevant columns, normalize text.  
2. **Exploratory Analysis**  
   - Distribution of employee status "Current vs Former" (Pie Chart).  
   - Location distribution (WordCloud).  
   - Review trend over years (Line Chart).  
3. **Text Analysis**  
   - WordClouds of *summary*, *positives*, and *negatives*.  
   - Classification into workplace categories:  
     - Work Life Balance  
     - Growth & Learning  
     - Company Values & Culture  
     - Technology & Innovation  
     - Salary & Benefits  
     - Management Style  
4. **Insights Extraction** → Compare **Top 3** vs **Bottom 3** place by average score.  

## 📊 Insights & Findings  
- **Top 3 startups (startup_1, startup_3, startup_5)** → Focused on *benefits, structured growth, and strict innovation*.  
- **Bottom 3 startups (startup_2, startup_4, startup_6)** → Highlight *career mobility, collaborative learning, and flexible culture*.  
- Gen Z employees value **balance, transparency in pay, and community-driven culture**.  

## ✅ Conclusion  
- High-scoring startups emphasize **benefits, structure, and strict innovation**, while low-scoring startups stress **mobility,     collaborative, and flexible culture**.  
- Work-life balance and transparent compensation remain top priorities for Gen Z.  

## 🚀 Recommendations  
- Improve career mobility alongside strong benefits.  
- Blend structured training with peer collaboration.  
- Maintain alumni/exit community ties.  
- Balance strict goals with flexible projects.  
- Ensure transparent and fair compensation.  
- Simplify promotion processes & enhance office culture.  

## 🤖 AI Support  
- Used **IBM Granite** LLM to:  
  - Generate classification & summarization prompts.  
  - Assist in extracting workplace themes.  
  - Auto-generate Python code for visualizations.  
- Human oversight ensured cleaning, validation, and insight alignment.  

## 📎 Files in Repository  
📂 Files in Repository  
- `SDI Hacktiv Data - Lumyn Kounji.ipynb` → Full analysis (Colab)  
- [Google Colab Notebook](https://colab.research.google.com/drive/144ogu427GR_ozxhUNkoaIL86nnYp0Ujb?usp=sharing)  
- `Employee Review.csv` → Raw dataset  
- `Sentiment Analysis - Moreno Irawan Syahputra.pptx` → Presentation slides  
- `README.md` → Project documentation (this file)  
 
