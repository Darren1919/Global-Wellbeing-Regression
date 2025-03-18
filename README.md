# 📊 Regression Analysis of Global Well-being Indices  

This project applies **multiple linear regression models** to analyze factors influencing **global well-being indices**, using data-driven feature selection techniques.  

## 📂 Dataset & Objective  
The dataset includes various socio-economic and governance factors affecting well-being worldwide. The goal is to:  
✅ Identify key predictors of **global well-being**  
✅ Compare different regression models using **AIC, BIC, Adjusted R², and Mallow’s Cp**  
✅ Optimize model selection for better interpretability  

## 📊 Regression Models & Feature Selection  
We developed multiple regression models and compared them using:  
- **Adjusted R²** (to measure model fit)  
- **AIC & BIC** (to penalize model complexity)  
- **Mallow’s Cp** (to identify the best subset of predictors)  

### 🔥 Key Findings  
- **Education, Governance, and Economic Quality** are the strongest predictors of well-being.  
- **AIC model selection** provided the most optimal model, balancing fit and complexity.  
- The final model improved interpretability while maintaining high predictive accuracy.  

## 📈 Visualizations  
Regression diagnostics and data visualization were conducted using **ggplot2** and **corrplot** in R.  

![Example Plot](download.png)  

## ⚡ How to Run  
1️⃣ Clone this repository:  
```bash
git clone https://github.com/Darren1919/Regression-Analysis.git
cd Regression-Analysis
