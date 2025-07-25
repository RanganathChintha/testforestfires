# testforestfires
# Forest Fire Prediction using Machine Learning

This project uses machine learning techniques to predict the occurrence and severity of forest fires based on meteorological and environmental data. The model is trained on the UCI Forest Fires dataset and implemented in Python.

## 🔥 Project Overview

The main goal of this project is to:

- Understand forest fire behavior using available data
- Preprocess and visualize the data
- Apply and evaluate machine learning models for fire area prediction

## 📁 Project Structure

testforestfires-main/
│
├── dataset/
│ └── forestfires.csv # Dataset used for training and evaluation
│
├── model/
│ └── model.pkl # Trained machine learning model
│
├── notebooks/
│ └── ForestFirePrediction.ipynb # Jupyter notebook for EDA and modeling
│
├── app.py # Flask app for web-based prediction interface
├── requirements.txt # Required Python libraries
└── README.md # Project documentation

markdown
Copy
Edit

## 🧪 Technologies Used

- Python 3
- Pandas, NumPy, Matplotlib, Seaborn
- Scikit-learn
- Flask (for web app interface)
- Jupyter Notebook

## ⚙️ How to Run the Project

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/testforestfires.git
cd testforestfires
2. Install Dependencies
bash
Copy
Edit
pip install -r requirements.txt
3. Run the Flask App
bash
Copy
Edit
python app.py
Open your browser and go to http://127.0.0.1:5000 to use the web interface.

📊 Dataset Description
The dataset contains features such as temperature, wind, humidity, rain, and more:

Feature	Description
X, Y	Spatial coordinates
month, day	Temporal attributes
FFMC, DMC, DC, ISI	Fire weather indices
temp	Temperature in Celsius
RH	Relative humidity
wind	Wind speed in km/h
rain	Rainfall in mm
area	Burned area in ha (target variable)

Source: UCI Forest Fires Dataset

📈 Model Evaluation
The model was evaluated using regression metrics:

Mean Squared Error (MSE)

R² Score

Train/Test Split validation

🚀 Future Improvements
Use deep learning models like neural networks

Deploy the app on cloud platforms (Heroku, AWS)

Add visual fire risk heatmaps

🧑‍💻 Author
Your Name — your-portfolio-link

📄 License
This project is open-source under the MIT License.

yaml
Copy
Edit

---

Let me know if you'd like me to:

- Customize it with your name/GitHub link
- Generate the `requirements.txt`
- Write deployment instructions for Heroku or Render
- Add screenshots or badges (build, license, etc.)
