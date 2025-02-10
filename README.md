# Used Car Price Prediction
## Overview
This project develops a data-driven predictive analytics solution that utilizes advanced machine learning algorithms to forecast used car prices accurately. 
The system takes into account key features such as make, model, year, mileage, fuel type, transmission type, vehicle age, etc 
as input variables. By combining sophisticated data processing techniques with a user-friendly interface, the solution 
delivers valuable and precise pricing insights for consumers.

<p align="center">
  <br>
  <img src="https://github.com/user-attachments/assets/679420e1-c62d-42f1-b0c2-31cde7aba723"/>
</p>
<p align="center">
  <br>
  <img src="https://github.com/user-attachments/assets/705a0544-b9a7-4cbc-a254-cf98eae8772a"/>
</p> 
<br>

## Features
* **Machine Learning Model**: Uses Gradient Boosting Regressor for accurate price predictions.
* **Data Analysis**: Explores key factors like brand, mileage, fuel type, and vehicle age.
* **Feature Engineering**: Handles missing values, outliers, and categorical encoding.
* **Model Evaluation**: Compares Linear Regression, Decision Tree, Random Forest, and XGBoost.
* **Web App Deployment**: Built with Streamlit for real-time car price estimation.
* **Real-World Use**: Helps buyers, sellers, and dealerships make informed decisions.

## Usage  
1. **Open the Web App**: [Car Price Prediction](https://car-price-prediction-2kevc4iyv5vrexssiocuoz.streamlit.app/)  
2. **Enter Car Details**: Provide details like brand, model, mileage, fuel type, transmission type, and vehicle age.  
3. **Click "Predict Price"**: The model processes the inputs and predicts the selling price.  
4. **View the Results**: The estimated price is displayed on the screen.  
5. **Modify & Recalculate**: Try different values to analyze price variations.  

## Technologies Used 
* **Machine Learning Models**: Gradient Boosting, Random Forest, XGBoost
* **Data Processing**: Pandas, NumPy
* **Exploratory Data Analysis (EDA)**: Matplotlib, Seaborn
* **Web App Development**: Streamlit
* **Model Deployment**: Streamlit Cloud
* **Programming Language**: Python
* **Version Control**: Git, GitHub

## Installation 
git clone https://github.com/Arc-1327/Car-Price-Prediction.git
cd Car-Price-Prediction
python -m venv env
env\Scripts\activate
pip install -r requirements.txt
streamlit run app.py


