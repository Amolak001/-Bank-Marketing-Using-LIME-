# 🏦 Bank Marketing Campaign Analysis

## 🎯 Project Overview
This project analyzes bank marketing campaign data using Random Forest classification and LIME (Local Interpretable Model-agnostic Explanations) to predict and explain customer subscription decisions for term deposits. Through advanced machine learning techniques and visualization methods, we extract actionable insights to optimize marketing strategies.

## 👨‍💻 Author
- **Github:** [Amolak Singh](https://github.com/Amolak001)
- **LinkedIn:** [Amolak Singh](https://www.linkedin.com/in/amolak--singh/)

## 🔗 Project Links
- **Google Colab Notebook**: [Bank Marketing Analysis](https://colab.research.google.com/drive/1uDK1XnNNpV4BBa9qJs94afQu2Hq4bF27?usp=sharing)

## 📊 Key Features
- Random Forest Classification for prediction
- LIME for model interpretation and explanation
- Comprehensive data visualization
- Feature importance analysis
- Model performance evaluation

## 📂 File Structure

```

bank-marketing-analysis/
├── README.md
├── Bank_Marketing.ipynb
├── bank_marketing.py
└── bank-additional-full.csv

```

## 🔍 Analysis Process

1. **Data Preprocessing**
   - Loading the dataset from CSV file
   - Encoding target variable ('y') to binary (1 for 'yes', 0 for 'no')
   - One-hot encoding of categorical variables

2. **Model Development**
   - Splitting data into training and testing sets (80-20 split)
   - Random Forest Classifier implementation
   - Model training and prediction

3. **Model Evaluation**
   - Classification report generation
   - Accuracy score calculation

4. **Feature Importance Analysis**
   - Global feature importance visualization

5. **Model Interpretation with LIME**
   - Local explanations for individual predictions
   - Visualization of LIME explanations

## 📈 Visualizations
- Global feature importance bar plot
- LIME explanation plots for individual observations

## 🎯 Model Performance
- Detailed classification report including precision, recall, and F1-score
- Overall accuracy score

## 🧠 Key Insights
- Identification of most important features in predicting term deposit subscriptions
- Local explanations for individual predictions, providing insights into model decision-making

## 🚀 Getting Started

### Prerequisites
- Python 3.x
- Required libraries:
```

pandas
numpy
matplotlib
seaborn
scikit-learn
lime

```

### Installation

1. Clone the repository:
 ```bash
 git clone https://github.com/Amolak001/Bank-Marketing-Using-LIME
```

2. Install required Python libraries:

```shellscript
pip install -r requirements.txt
```


3. Run the Python script or open the Jupyter Notebook:

```shellscript
python bank_marketing.py
```

or

```shellscript
jupyter notebook Bank_Marketing.ipynb
```




## 🔑 Keywords

- Random Forest Classification
- LIME Explanations
- Machine Learning
- Banking Analytics
- Marketing Campaign Analysis
- Feature Importance
- Model Interpretability


## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## ⭐ Stay Updated

Star this repository to keep track of the latest developments and insights!

## 📫 Contact

For any queries or discussions related to this project, feel free to reach out through:

- GitHub Issues
- [LinkedIn](https://www.linkedin.com/in/amolak--singh/)
- [GitHub](https://github.com/Amolak001)


## 🙏 Acknowledgments

- Dataset: Bank Marketing Data Set (UCI Machine Learning Repository)
- LIME library for model explanations


