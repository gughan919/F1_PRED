# Formula 1 Driver Performance Prediction  
Data Science Premier League Hackathon Submission  

## Project Overview  
This project predicts Formula 1 driver performance using machine learning models based on historical race data (1950-2024).  
We analyze key racing metrics, engineer features, and evaluate multiple models.  

Implemented machine learning models:  

- Logistic Regression  
- K-Nearest Neighbors (KNN) 
- Random Forest Classifier  
- Decision Tree Classifier  
- Gaussian Naïve Bayes  

The objective is to optimize model accuracy and identify key performance factors.  

---

## Tools, Libraries & Frameworks  

### Tools & Platforms  
- Google Colab – Development environment  
- Python 3.11 – Core programming language  
- Jupyter Notebook – Local testing  
- Excel – Data processing  

### Python Libraries  
- **Data Handling:**  
  - pandas – Data manipulation  
  - numpy – Numerical computations  

- **Data Visualization:**  
  - matplotlib – Basic plots  
  - seaborn – Advanced visualizations  

- **Machine Learning Models:**  
  - sklearn.linear_model – Logistic Regression  
  - sklearn.neighbors – K-Nearest Neighbors  
  - sklearn.ensemble – Random Forest Classifier  
  - sklearn.tree – Decision Tree Classifier  
  - sklearn.naive_bayes – Gaussian Naïve Bayes  

- **Feature Engineering & Optimization:**  
  - sklearn.preprocessing – Feature scaling  
  - sklearn.model_selection – GridSearchCV for hyperparameter tuning  

- **Graph-Based Analysis:**  
  - networkx – Social network and graph-based analysis  

---

## Dataset Information  
The dataset consists of 14 CSV files, merged into a structured final_df.xlsx.  
Key features:  
- Driver statistics: Wins, podiums, fastest laps  
- Team performance: Constructors' wins, podiums  
- Race metrics: Grid position, finishing position  
- Track data: Circuit ID, race times  
- Scoring system: Points, ranking  

---

## Setup Instructions  
1. Open Google Colab: [Google Colab Link](https://colab.research.google.com/)  
2. Upload the datasets to Colab  
3. Run each cell step by step  
4. Model training starts automatically  
5. Check evaluation metrics (accuracy, precision, recall, F1-score)  
6. Use the trained model for predictions  

---
