🚢 Titanic Survival Prediction
This machine learning project predicts the survival of passengers aboard the Titanic using the popular Titanic dataset. It applies data preprocessing and classification techniques to build a robust prediction model.

📌 Objective
To build a classification model that predicts whether a passenger survived the Titanic disaster, based on features like age, sex, class, and fare.

🔍 Dataset
- **Source**: Titanic dataset (CSV format)
- **Features** used:
  - `Pclass`: Ticket class
  - `Sex`: Gender
  - `Age`: Age of passenger
  - `SibSp`: # of siblings/spouses aboard
  - `Parch`: # of parents/children aboard
  - `Fare`: Ticket fare
  - `Embarked`: Port of embarkation (if used)

🧼 Data Preprocessing
- Handled missing values
- Converted categorical variables using Label Encoding
- Normalized or scaled data if necessary
- Split data into training and testing sets

🤖 Model Used
- Random Forest Classifier
- `train_test_split()` used for an 80-20 train-test split

🧪 Evaluation Metrics
- Accuracy : `~81.56%`
  
- Classification Report :
- Precision, Recall, F1-Score for both survival classes

📈 Output
- Model trained and evaluated
- Output includes accuracy score, classification report, and confusion matrix

✅ Conclusion
This project demonstrates the ability to process real-world data, perform classification, and interpret results using a machine learning pipeline. The Random Forest Classifier provided strong predictive accuracy, showing good performance on unseen data.

📚 Libraries Used
- `pandas`
- `numpy`
- `sklearn`
- `matplotlib` *(optional if visualization is added)*

🚀 How to Run
1. Clone the repository  
 `git clone https://github.com/ishasahlot/titanic_survival_prediction.git`
2. Open the Jupyter Notebook `titanic_survival_prediction.ipynb`
3. Run the cells step-by-step to see preprocessing, model training, and evaluation

📬 Contact
Isha Sahlot
[LinkedIn](https://www.linkedin.com/in/ishasahlot)
