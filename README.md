# 📌 Customer Churn Prediction

## 📖 Introduction
This project focuses on **predicting customer churn** based on customer behavior and demographic data.  
The main goal is to build a Machine Learning/Deep Learning model that can classify customers into two groups:  
- **Churn (customers who leave the service)**  
- **Non-Churn (customers who stay with the service)**  

## ⚙️ Technologies Used
- **Python**  
- **Pandas, NumPy** – Data manipulation  
- **Matplotlib, Seaborn** – Data visualization  
- **Scikit-learn** – Data preprocessing & evaluation metrics  
- **TensorFlow / Keras** – Neural network modeling  
- **Callbacks (EarlyStopping)** – Prevent overfitting  

## 📊 Workflow
1. **Exploratory Data Analysis (EDA)**  
   - Load and inspect data using `pandas`  
   - Explore feature distributions and their relationship with churn  
   - Visualize trends using `matplotlib` and `seaborn`  

2. **Data Preprocessing**  
   - Normalize features with `MinMaxScaler`  
   - Split dataset into training and testing sets (80/20)  

3. **Model Building**  
   - Build a Neural Network with Keras (`Dense layers`, `sigmoid` activation for output)  
   - Apply **EarlyStopping** to stop training when validation performance stops improving  

4. **Model Training**  
   - Train on the training set  
   - Evaluate on the test set  

5. **Model Evaluation**  
   - Use **Confusion Matrix** and **Classification Report**  
   - Metrics: Accuracy, Precision, Recall, F1-score  

## 🚀 How to Run
1. Clone the repository:  
   ```bash
   git clone https://github.com/yourusername/customer_churn.git
   cd customer_churn
   ```
2. Install dependencies:  
   ```bash
   pip install -r requirements.txt
   ```
3. Open Jupyter Notebook and run:  
   ```bash
   jupyter notebook customer_churn.ipynb
   ```

## 📌 Expected Results
- Visualizations of churn distribution and feature relationships  
- A predictive churn model with accuracy around **80–90%** (depending on data and tuning)  
- Detailed performance metrics and evaluation report  
