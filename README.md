# 🌍 AI Tools for Climate Resilience using Synthetic Data

This project demonstrates how to design and train AI models for climate risk prediction using **synthetic climate data**. It includes tools for data generation, machine learning classification, and exporting results to Excel.

---

## 📦 Features

- ✅ Synthetic generation of climate features (temperature, precipitation, humidity, etc.)
- ✅ Binary classification of climate risk (high vs. low)
- ✅ Random Forest & Neural Network models for prediction
- ✅ Excel export of synthetic dataset
- ✅ Ready-to-run code for experimentation or prototyping

---

## 📊 Synthetic Data Fields

| Feature            | Description                          |
|--------------------|--------------------------------------|
| `temperature`      | Daily average temperature (°C)       |
| `precipitation`    | Daily rainfall (mm)                  |
| `humidity`         | Relative humidity (%)                |
| `wind_speed`       | Wind speed (m/s)                     |
| `vegetation_index` | Proxy for land vegetation health     |
| `climate_risk`     | 1 = High risk, 0 = Low risk          |

---

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/climate-resilience-ai.git
cd climate-resilience-ai
2. Install Dependencies
bash


pip install numpy pandas matplotlib seaborn scikit-learn torch openpyxl
3. Run the Script
bash


python main.py
This will:

Generate synthetic data

Save it as synthetic_climate_data.xlsx

Train Random Forest and Neural Network classifiers

Output model metrics

📁 Output Files
synthetic_climate_data.xlsx: Excel file containing the generated dataset

Model output and evaluation in console

🧠 Model Architecture
Random Forest Classifier: Interpretable, fast baseline

PyTorch Neural Network: Lightweight MLP with ReLU activations

🔬 Future Extensions
Integrate satellite or IoT sensor data (e.g., Copernicus, NASA POWER)

Use GANs or VAEs for more realistic synthetic data

Build dashboards (e.g., Streamlit or React + Flask)

Geo-aware models using spatial features

Climate resilience scoring per region or city

📜 Author
Tarinabo williamtarinabo@gmail.com

