# Short-Term Load Forecasting Using Dual Attention Quantile LSTM  

This project presents a robust approach to short-term load forecasting using a Dual Attention Quantile LSTM (DA-QLSTM) model. It is designed to predict energy consumption trends with high accuracy and reliability, leveraging advanced machine learning techniques.  

## **Project Overview**  
The primary objective of this project is to forecast short-term energy demand using modern deep learning techniques. The DA-QLSTM model integrates dual attention mechanisms to enhance feature extraction and capture temporal patterns effectively, enabling accurate predictions at different quantile levels.  

### **Datasets**  
The model was trained and evaluated on two datasets:  
1. **IESCO Dataset**: Historical energy consumption data from the Islamabad Electric Supply Company (IESCO), Pakistan.  
2. **Panama City Dataset**: Publicly available energy consumption data from Panama City, providing diverse seasonal and regional patterns.  

### **Key Features**  
- **Dual Attention Mechanism**: Incorporates temporal and spatial attention to focus on the most relevant features dynamically.  
- **Quantile Regression**: Predicts energy demand at different quantile levels (e.g., 0.1, 0.5, 0.9) for uncertainty quantification.  
- **LSTM Backbone**: Utilizes Long Short-Term Memory networks for effective sequential data modeling.  
- **Performance Metrics**: Evaluated using Mean Absolute Error (MAE), Root Mean Squared Error (RMSE), and Quantile Loss.  

### **Technologies Used**  
- Python  
- TensorFlow  
- Pandas, NumPy  
- Matplotlib, Seaborn (for visualization)  

## **Project Structure**  
- **Data Preprocessing**: Includes data cleaning, normalization, and feature engineering.  
- **Model Implementation**: Code for the DA-QLSTM model, including attention mechanisms and quantile loss functions.  
- **Evaluation**: Scripts for model evaluation and visualization of predictions.  
- **Results**: Comparison of forecasted vs actual values and performance metrics.  

## **How to Use**  
1. Clone the repository:  
   ```bash  
   git clone https://github.com/Afrazshah94/Time-Series-Load-Forecasting/edit/main/README.md
