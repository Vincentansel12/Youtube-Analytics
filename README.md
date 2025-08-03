# 📊 YouTube Analytics Portfolio: A/B Testing, Retention, and Recommender System

This project showcases three core data science use cases using real-world YouTube video data:  
1. A/B testing,  
2. Cohort-based retention analysis, and  
3. A simple rule-based recommender system.  

---

## 📁 Project Structure

### 1. A/B Testing
- **Objective**: Test whether longer videos are associated with higher subscriber counts.
- **Methods**:
  - Skewness check
  - Log transformation
  - Mann-Whitney U test
- **Insight**: Statistically significant difference in subscriber count between shorter and longer videos.

### 2. Cohort Retention Analysis
- **Objective**: Simulate how video performance evolves based on upload year (cohorts).
- **Methods**:
  - Group videos by upload year
  - Track average views over time since release
- **Insight**: Clear decay pattern; older videos tend to plateau in views after a few months.

### 3. Recommender System (Rule-Based)
- **Objective**: Recommend similar videos based on title and category using cosine similarity.
- **Methods**:
  - Feature engineering: Title + Category
  - CountVectorizer + Cosine Similarity
- **Insight**: Successfully returns contextually similar videos; lightweight but effective.

---

## 🛠️ Tech Stack
- Python (Pandas, Matplotlib, Seaborn)
- Scikit-learn (for CountVectorizer & similarity)
- Jupyter Notebook

---

🔑 Key Takeaways
Basic A/B testing and statistical thinking can uncover real user behavior patterns.
Cohort analysis is powerful to understand content lifecycle performance.
Even a simple rule-based recommender can provide meaningful suggestions.
