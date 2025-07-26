# 🌲 Forest Fire Prediction using Machine Learning

This project aims to predict the burned area of forest fires using machine learning techniques, based on meteorological and environmental data. It is built using Python and Flask, with a web interface for making predictions.

## 🔍 Overview

- Data source: UCI Forest Fires Dataset
- Algorithms: Linear Regression, Random Forest, and others
- Output: Burned area prediction (in hectares)
- Web interface: Flask-powered frontend to input data and get predictions

## 📁 Project Structure

```
testforestfires-main/
│
├── dataset/
│   └── forestfires.csv       # Dataset file
│
├── model/
│   └── model.pkl             # Trained machine learning model
│
├── notebooks/
│   └── ForestFirePrediction.ipynb  # Jupyter notebook for analysis & modeling
│
├── app.py                    # Flask web app
├── requirements.txt          # Python dependencies
└── README.md                 # Project documentation
```

## 🛠️ Setup Instructions

1. **Clone the repository**

```bash
git clone https://github.com/your-username/testforestfires.git
cd testforestfires
```

2. **Install dependencies**

```bash
pip install -r requirements.txt
```

3. **Run the Flask app**

```bash
python app.py
```

Then open your browser at: `http://127.0.0.1:5000`

## 📊 Dataset Features

| Feature | Description |
|---------|-------------|
| X, Y | Spatial coordinates |
| month, day | Time of year |
| FFMC, DMC, DC, ISI | Fire weather indices |
| temp | Temperature (°C) |
| RH | Relative humidity (%) |
| wind | Wind speed (km/h) |
| rain | Rainfall (mm) |
| area | Burned area (ha) – Target variable |

Dataset: [UCI Machine Learning Repository - Forest Fires](https://archive.ics.uci.edu/ml/datasets/Forest+Fires)

## ✅ Model Performance

Evaluated using:

- Mean Squared Error (MSE)
- R² Score
- Train/test split for validation

## 🌐 Web App

The Flask web app allows users to input new forest conditions and get predicted fire area instantly.

## 🚀 Possible Improvements

- Add support for multiple models
- Use advanced algorithms like XGBoost or Neural Networks
- Deploy the app using Render or Heroku
- Visualize results with maps or interactive dashboards

## 👨‍💻 Author

**Your Name**  
[GitHub](https://github.com/RanganathChintha)

## 📄 License

This project is licensed under the MIT License.
