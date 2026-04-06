# 🌍 World GDP Analysis & Prediction System
An interactive **Streamlit-based web application** that allows users to analyze global GDP data and predict GDP per capita using machine learning.
🚀 Features

📊 Interactive Dashboard
  * Upload your own dataset (CSV)
  * Explore regional and country-level insights
  * View aggregated statistics and trends

🤖 GDP Prediction System
  * Predict GDP per capita using a trained ML model
  * Input features manually
  * Compare predicted GDP with closest countries

📈 Data Visualization
  * Top 15 countries by GDP
  * Region-wise GDP distribution
  * Asia-specific literacy & GDP insights
  * Region-wise top 5 countries

🧠 Machine Learning Model

* Model Used: **Decision Tree Regressor**
* Features:
  * Literacy (%)
  * Agriculture
  * Birthrate
* Model file: `model_dtr.pkl`

## 📂 Project Structure

```
├── app2.py                 # Main Streamlit app (UI + Prediction)
├── helper.py               # Data processing & visualization functions
├── train_model.py          # Model training script
├── model_dtr.pkl           # Trained ML model
├── countries of the world.csv
├── requirements.txt
└── README.md
```

## ⚙️ Installation & Setup

1. Clone the repository

```bash
git clone https://github.com/your-username/world-gdp-analysis.git
cd world-gdp-analysis
```

2. Install dependencies

```bash
pip install -r requirements.txt
```

3. Run the application

```bash
streamlit run app2.py
```

## 📊 How It Works

### 1. Upload Dataset

* Upload a CSV file containing country-level GDP data
* The app calculates:

  * Total regions
  * Total countries
  * Countries per region

### 2. Data Processing

* Handles missing values
* Converts data types
* Aggregates regional data

### 3. Visualization

* Top 15 GDP countries
* Region-wise comparisons
* Asia-specific insights
* GDP distribution charts

### 4. Prediction

* Enter features:

```
Literacy, Agriculture, Birthrate
```

* Get instant GDP prediction

---

## 🖥️ Example Input

```
85.5, 0.15, 22.3
```
