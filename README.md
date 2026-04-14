# Gold Price Prediction using Machine Learning

##  Project Overview
This project aims to predict gold prices using machine learning techniques based on historical financial data. Gold prices are highly volatile and influenced by multiple economic factors, making this a challenging time-series prediction problem.

The model analyzes past trends and patterns to estimate future gold prices and provide useful insights.

---

##  Dataset
The dataset contains historical gold price data along with other financial indicators such as:

- Date  
- Gold Price (GLD)  
- S&P 500 Index (SPX)  
- Oil Prices (USO)  
- Silver Price (SLV)  
- EUR/USD Exchange Rate  

These features help improve prediction accuracy by capturing market relationships 

---

##  Technologies Used
- Python 
- Pandas & NumPy  
- Matplotlib & Seaborn  
- Scikit-learn  
- Jupyter Notebook  

---

##  Project Workflow

### 1. Data Collection
- Imported dataset using Pandas  
- Converted date column to datetime format  

### 2. Data Preprocessing
- Handled missing values  
- Feature selection  
- Data scaling  

### 3. Exploratory Data Analysis (EDA)
- Visualized trends in gold prices  
- Correlation analysis between features  
- Identified patterns and relationships  

### 4. Model Building
Implemented machine learning models:
- Linear Regression  
- Random Forest Regressor  

Random Forest helps capture non-linear relationships and improves prediction accuracy.

---

##  Model Evaluation
The model performance was evaluated using:

- Mean Absolute Error (MAE)  
- Mean Squared Error (MSE)  
- R² Score  

These metrics help measure prediction accuracy and model reliability.

---

##  Results
- Successfully predicted gold price trends  
- Random Forest performed better compared to basic regression  
- Model captured key relationships between financial indicators  

---

##  Visualizations
- Gold price trends over time  
- Correlation heatmaps  
- Predicted vs Actual graphs  

---

##  Future Improvements
- Use deep learning models like LSTM/GRU for better time-series prediction  
- Add more external economic factors  
- Deploy model using Streamlit or Flask  

---


