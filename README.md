#  MU Youth Scouting System

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![Kaggle](https://img.shields.io/badge/Dataset-Transfermarkt-20beff)
![License](https://img.shields.io/badge/License-MIT-green)

## 📖 Description
This project is a data analysis and machine learning system designed to help the **Manchester United** recruitment team identify highly potential young players (aged 17-23) who have a low market value but high upside (*undervalued / hidden gems*). 

The analysis utilizes the **Transfermarkt** dataset downloaded directly via the Kaggle API, processed through a robust preprocessing pipeline, and evaluated using **KMeans Clustering** alongside a custom composite scoring system.

## ✨ Key Features
- 🔄 **Auto-Download Dataset**: Fetches the Transfermarkt dataset directly from Kaggle using `kagglehub`.
- 🧹 **Robust Preprocessing**: Automated data cleaning for age formats, market values (handling €, $, £, M, K, etc.), and player position normalization.
- 🎯 **Custom Scoring System**: Generates a composite score based on age efficiency (long-term investment value) and market value (identifying undervalued assets).
- 💎 **Hidden Gems Discovery**: Uses **KMeans Clustering** to group players and isolate the specific cluster of young, undervalued talents.
- 📊 **Interactive Visualizations**: Generates interactive charts using Plotly (Age vs. Market Value scatter plot, Top 15 Recommendations bar chart).
- 💾 **Report Export**: Automatically generates CSV reports containing recruitment priorities per position and the list of hidden gems.

## 🛠️ Tech Stack
- **Language**: Python 3
- **Data Manipulation**: `pandas`, `numpy`
- **Machine Learning**: `scikit-learn` (KMeans, StandardScaler, Silhouette Score)
- **Visualization**: `plotly`, `matplotlib`, `seaborn`
- **Data Source**: `kagglehub`

## 📦 Installation & How to Run

> **Note:** This script is optimized for **Google Colab** or **Jupyter Notebook** environments due to the use of interactive displays and shell commands.

### Option 1: Google Colab (Recommended)
Upload the `pemain_muda_untuk_mu.py` file directly to your Colab workspace and run all cells.

### Option 2: Local Jupyter Notebook
1. **Clone the Repository**
   ```bash
   git clone https://github.com/atmajapamungkas/Young-Talent-For-Manchester_United.git
   cd Young-Talent-For-Manchester_United
