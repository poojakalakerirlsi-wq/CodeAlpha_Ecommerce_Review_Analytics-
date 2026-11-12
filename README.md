# CodeAlpha_Ecommerce_Review_Analytics

## CodeAlpha Internship Project — EDA, Data Visualization & Sentiment Analysis

**Domain:** Data Analytics / Data Science  
**Tasks completed:** Task 2 (EDA), Task 3 (Data Visualization), Task 4 (Sentiment Analysis)

### Project Objective
Analyze e-commerce product reviews to:
1. understand the structure and quality of the review dataset,
2. discover trends, patterns and anomalies,
3. create decision-focused visualizations, and
4. classify review text into positive, negative or neutral sentiment.

### Business Questions
- Which products receive the highest average ratings?
- How are positive, negative and neutral reviews distributed?
- Is rating associated with sentiment?
- Which products show warning signs from negative reviews?
- What common words/emotions appear in positive and negative feedback?

### Dataset
`data/product_reviews.csv` contains 30 anonymized product reviews covering laptops, headphones, smartphones, smartwatches and tablets.

### Tools
Python, Pandas, NumPy, Matplotlib, Seaborn and VADER Sentiment.

### Project Structure
```text
CodeAlpha_Ecommerce_Review_Analytics/
├── data/
│   └── product_reviews.csv
├── outputs/
│   ├── 01_sentiment_distribution.png
│   ├── 02_average_rating_by_product.png
│   ├── 03_rating_vs_sentiment.png
│   └── 04_negative_review_share.png
├── sentiment_analysis.py
├── requirements.txt
├── PROJECT_REPORT.md
├── README.md
└── .gitignore
```

### How to Run
```bash
pip install -r requirements.txt
python sentiment_analysis.py
```

The script creates the analysis charts in the `outputs/` folder.

### Internship Submission Checklist
- [ ] Share internship status on LinkedIn and tag **@CodeAlpha**
- [ ] Upload this complete project to GitHub
- [ ] Repository name: **CodeAlpha_Ecommerce_Review_Analytics**
- [ ] Record a short video explaining the project
- [ ] Add the GitHub repository link to the LinkedIn video post
- [ ] Submit the CodeAlpha Submission Form

> Note: The included dataset is a small educational dataset created for this internship project. For a larger portfolio version, replace it with a larger public review dataset while keeping the same analysis pipeline.
