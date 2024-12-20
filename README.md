

---

# **Uber Customer Reviews Sentiment Analysis**

This project analyzes Uber customer reviews to extract insights about user sentiments using natural language processing (NLP) techniques. The analysis includes sentiment classification, polarity scoring, and predictions using machine learning models, and the results are visualized for better understanding.

---

## **Project Overview**
The goal of this project is to:
1. Understand customer feedback through sentiment polarity analysis.
2. Classify reviews into sentiment categories: `Positive`, `Negative`, and `Neutral`.
3. Build a machine learning model for sentiment prediction.
4. Visualize the results using Tableau.

---

## **Dataset**
The dataset consists of Uber customer reviews, preprocessed to remove unnecessary columns:
- **Original Dataset**: [Uber Reviews on Kaggle](#) *(Add the dataset link if applicable)*
- **Processed Dataset**: `uber_reviews_with_predictions.csv` (includes sentiment analysis and predictions).

### **Columns in Processed Dataset**:
- `content`: The text of the customer review.
- `sentiment_polarity`: Numerical polarity scores (`-1.0` to `1.0`).
- `sentiment_category`: Categorized sentiments (`positive`, `negative`, `neutral`).
- `predicted_sentiment`: Sentiment category predicted by the machine learning model.

---

## **Methodology**
1. **Data Preprocessing**:
   - Removed unnecessary columns such as `userImage`, `replyContent`, and `repliedAt`.
   - Calculated sentiment polarity using TextBlob.
   - Mapped polarity to sentiment categories.

2. **Machine Learning**:
   - Features: Text reviews (`content`).
   - Labels: Sentiment categories (`sentiment_category`).
   - Vectorization: TF-IDF Vectorizer.
   - Model: Logistic Regression.

3. **Evaluation**:
   - The model's performance was evaluated using classification metrics.

4. **Visualization**:
   - Visualized the processed dataset in Tableau for insights into sentiment distribution and trends.

---

## **Results**
- The classification report indicates the model's performance on predicting sentiments.
- Visualizations in Tableau reveal:
  - Sentiment distribution across reviews.
  - Polarity trends and frequency distribution.

---

## **Visualization in Tableau**
The processed dataset was visualized in Tableau to uncover patterns and trends:
- **Sentiment Distribution**: A bar chart displaying counts of `positive`, `negative`, and `neutral` reviews.
- **Polarity Distribution**: A histogram showing the distribution of sentiment polarity values.
- **Other Visualizations**: Time-based trends, word clouds (optional), etc.

You can view the Tableau dashboard [here](#) *(Add Tableau Public link if applicable)*.

---

## **How to Run This Project**
### **Requirements**
- Python 3.8 or above
- Libraries: `pandas`, `textblob`, `scikit-learn`, `matplotlib`, `seaborn`

### **Steps**:
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/uber-customer-review-analysis.git
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the Jupyter Notebook to perform the analysis.
4. Visualize the processed dataset (`uber_reviews_with_predictions.csv`) in Tableau.

---

## **Project Files**
- `uber_reviews_without_reviewid.csv`: Raw dataset (if allowed to share).
- `uber_reviews_with_predictions.csv`: Processed dataset.
- `Uber_Reviews_Analysis.ipynb`: Jupyter Notebook containing the code.
- `README.md`: Project documentation.
- `requirements.txt`: Required Python libraries.

---

## **Conclusion**
This project demonstrates how NLP and machine learning can be applied to extract meaningful insights from customer reviews. By visualizing the results, stakeholders can better understand customer sentiment and improve services.

---

## **Acknowledgments**
- **Dataset**: Uber Reviews (Kaggle)
- **Libraries**: Python, TextBlob, Scikit-learn, Matplotlib, Seaborn
- **Visualization**: Tableau

---
