Here's a well-structured README for your GitHub repository on **Earthquake Magnitude Prediction Using Machine Learning**:

# Earthquake Magnitude Prediction Using Machine Learning

## 📌 Overview
This project predicts earthquake magnitudes using machine learning models based on historical seismic data. The goal is to analyze earthquake patterns and estimate the magnitude of future events to help in disaster preparedness.

## 📂 Dataset
We used the **SOCR Earthquake Dataset**, which contains historical earthquake data, including:
- Date and time of the earthquake
- Latitude & Longitude
- Depth of the earthquake
- Magnitude of the earthquake

## 🛠️ Technologies Used
- **Python** for data processing and model building
- **Pandas & NumPy** for data handling
- **Matplotlib & Seaborn** for data visualization
- **Scikit-learn** for implementing machine learning models

## 🚀 Machine Learning Models
We tested multiple models to predict earthquake magnitudes:
1. **Linear Regression** 📈
2. **Support Vector Machine (SVM)** 🔄
3. **Naïve Bayes** 📊
4. **Random Forest** 🌲

## 📊 Performance Evaluation
The models were evaluated using:
- **Mean Absolute Error (MAE)**
- **Mean Squared Error (MSE)**
- **R² Score**

Random Forest performed the best in capturing patterns in the data.

## 🔧 How to Run the Project
1. Clone the repository:
   ```sh
   git clone https://github.com/akash-r34/Earthquake-prediction-using-Machine-learning-models.git
   cd Earthquake-prediction-using-Machine-learning-models
   ```
2. Install dependencies:
   ```sh
   pip install -r requirements.txt
   ```
3. Run the Jupyter Notebook:
   ```sh
   jupyter notebook
   ```
4. Open `Earthquake_Prediction.ipynb` and run the cells.

## 📌 Future Improvements
- Adding more features like soil type and tectonic plate movement
- Using deep learning models like LSTMs for time-series forecasting
- Incorporating real-time data for continuous learning


Let me know if you need any modifications! 🚀
