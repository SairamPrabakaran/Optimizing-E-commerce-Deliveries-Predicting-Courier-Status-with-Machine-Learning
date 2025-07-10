# Optimizing-E-commerce-Deliveries-Predicting-Courier-Status-with-Machine-Learning
Predicting courier status (shipped, unshipped, cancelled) in e-commerce using machine learning. Analyzed 128K+ orders with features like fulfillment, product, and shipping details. Built logistic regression and random forest models to improve delivery efficiency and reduce cancellations.

Project Overview:
This project aims to build a predictive model that determines the courier status of e-commerce orders—classifying them as shipped, unshipped, or cancelled. Using a real-world dataset containing over 128,000 records and 24 features, the objective is to provide actionable insights to help businesses streamline delivery processes, reduce cancellations, and enhance customer satisfaction.

🧠 Problem Statement
E-commerce businesses often struggle with order cancellations and logistics delays, affecting profitability and consumer trust. By predicting courier status in advance, companies can proactively intervene, optimize fulfillment strategies, and improve operational efficiency.

📊 Dataset Description
The dataset includes detailed order information such as:

Order IDs & transaction dates

Fulfillment methods & service levels

Product details (SKU, size, category, price)

Shipping information (origin/destination locations)

These features are used to train classification models for courier status prediction.

🛠️ Tools & Technologies
Programming Language: Python

Libraries:

Data Processing: pandas, numpy

Visualization: matplotlib, seaborn

Machine Learning: scikit-learn

Models Used:

Logistic Regression

Random Forest Classifier

⚙️ Methodology
Data Preprocessing

Handling missing values

Label encoding categorical variables

Feature scaling

Exploratory Data Analysis (EDA)

Identifying trends in cancellations and delays

Feature correlation and distribution

Model Building & Evaluation

Baseline model: Logistic Regression

Advanced model: Random Forest

Performance metrics: Accuracy, Precision, Recall, F1-score

Feature importance analysis

🔍 Key Insights
Random Forest outperformed Logistic Regression in predictive accuracy.

Features such as service level, fulfillment method, and shipping destination significantly influence courier outcomes.

The model helps identify high-risk orders, allowing early intervention by logistics teams.

🎯 Business Impact
By implementing this ML pipeline, businesses can:
✅ Minimize order cancellations
✅ Improve last-mile delivery planning
✅ Enhance customer experience
✅ Make data-informed logistics decisions

📁 Project Status
✅ Data Cleaning & EDA
✅ Model Training & Evaluation
🛠️ Future Improvements: Model deployment and UI dashboard integration

