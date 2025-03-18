# ipl-prediction
This project predicts the outcome of an IPL match's second innings using machine learning, where RandomForestClassifier provides win/loss predictions with 99% accuracy, and LogisticRegression estimates the winning probability of each team at any given point.

Here's a **README.md** for your GitHub repository:  

---

# IPL Match Outcome Predictor  

This project predicts the outcome of an IPL match's second innings using machine learning. It offers two approaches:  

- **RandomForestClassifier:** Predicts whether the batting team will win or lose with **99% accuracy**.  
- **LogisticRegression:** Estimates the probability of each team winning at a given point in the second innings.  

## 📂 Dataset  
The project uses IPL match and ball-by-ball data, extracting key features like team performance, venue stats, and match situations.  

## ⚡ Features  
- One-hot encoding for categorical features (teams, venues, etc.).  
- Feature engineering with **current score, required run rate, wickets left, etc.**  
- Data cleaning to handle missing and infinite values.  

## 🔧 Model Training  
- **RandomForestClassifier:** High accuracy for win/loss classification.  
- **LogisticRegression:** Provides real-time win probability.  
- **Train-Test Split:** 80-20 split 


## 📊 Results  
- **RandomForestClassifier:** 99% accuracy on test data.  
- **LogisticRegression:** Dynamic probability estimates for real-time predictions.  

## 🛠️ Future Improvements  
- Incorporate live match data for real-time predictions.  
- Improve feature selection for better model interpretability.  
- Deploy as a web app using Flask or FastAPI.  

## 📌 Contributors  
- **Sanak Aich Bhowmick** ([@yourgithubhandle](https://github.com/sanakaich))  

## 🏆 License  
This project is open-source under the **MIT License**.  

