🛒 ShopSmart – Purchase Prediction using Machine Learning
Predicting whether an online store visitor will make a purchase based on their browsing behavior using a Decision Tree Classification model.

📖 Overview
This project develops a Decision Tree Classification model to predict customer purchase intent from online shopping session data. The workflow includes data preprocessing, exploratory data analysis (EDA), feature engineering, model training, and hyperparameter tuning to improve predictive performance.

✨ Features
📊 Exploratory Data Analysis (EDA)
🧹 Data preprocessing using Scikit-learn Pipelines
🔄 One-Hot Encoding & Feature Scaling
🌳 Decision Tree Classification
⚙️ Hyperparameter tuning with GridSearchCV
📈 Performance evaluation using F1 Score
🛠️ Tech Stack
Category	Technologies
Language	Python
Data Analysis	Pandas, NumPy
Machine Learning	Scikit-learn
Visualization	Matplotlib, Seaborn
Environment	Jupyter Notebook
📂 Dataset
The dataset consists of 12,330 online shopping sessions containing visitor browsing behavior and purchase information.

Target Variable: Revenue

1 → Visitor completed a purchase
0 → No purchase
📁 Project Structure
├── shop_smart.ipynb
├── dataset.csv
├── problem_statement
└── README.md
📊 Results
Built and optimized a Decision Tree Classifier for an imbalanced classification problem.

Improved model performance through pruning and hyperparameter tuning.

Evaluated the model using:

✅ F1 Score
✅ Confusion Matrix
✅ Classification Report
🚀 How to Run
git clone https://github.com/your-username/shop-smart.git
cd shop-smart
pip install -r requirements.txt
jupyter notebook
👨‍💻 Author
Anish Mishra
