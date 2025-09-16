# 🌡️ Temperature Prediction from Humidity Data  

## 📌 Project Overview  
This project predicts **temperature** based on **humidity, pressure, and location data** using machine learning.  
The workflow is implemented in a Jupyter Notebook (`Temperature Prediction_Test.ipynb`) and uses the dataset `humidity.csv`.  

## 📂 Dataset  
The dataset consists of environmental sensor measurements with the following columns:  

- `sensor_id`: Unique sensor identifier  
- `lat`: Latitude of the sensor  
- `lon`: Longitude of the sensor  
- `pressure`: Atmospheric pressure (Pa)  
- `temperature`: Temperature (°C)  
- `humidity`: Relative humidity (%)  

## ⚙️ Workflow  
1. **Load the dataset** (`humidity.csv`)  
2. **Exploratory Data Analysis (EDA)**: Check missing values, duplicates, and basic statistics  
3. **Data Preprocessing**: Cleaning and preparing features  
4. **Model Training**: Regression models to predict temperature  
5. **Evaluation**: Compare predictions vs. actual temperature  

## 📊 Example Visualization  
- Scatter plots of humidity vs. temperature  
- Correlation heatmaps of features  
- Model performance evaluation (e.g., RMSE, R²)  

## 🛠️ Tech Stack  
- **Python 3**  
- **Jupyter Notebook**  
- Libraries:  
  - `pandas`, `numpy` – Data handling  
  - `matplotlib`, `seaborn` – Visualization  
  - `scikit-learn` – Machine Learning  

## 🚀 How to Run  
1. Clone this repository:  
   ```bash
   git clone https://github.com/your-username/temperature-prediction.git
   cd temperature-prediction
   ```
2. Install dependencies:  
   ```bash
   pip install -r requirements.txt
   ```
3. Run the notebook:  
   ```bash
   jupyter notebook "Temperature Prediction_Test.ipynb"
   ```

## 📌 Results  
- Built a regression model to predict temperature based on humidity and pressure.  
- Gained insights into the relationship between atmospheric conditions.  

## 📜 License  
This project is licensed under the MIT License.  
