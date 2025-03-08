
![Logo](https://media.istockphoto.com/id/1399575283/photo/money-makes-the-world-go-round.jpg?s=1024x1024&w=is&k=20&c=JaI2-S2be9V7OHUn6ZhaA-glZlv3TDftN7DLKAHDsf0=)


# 📊💰 Economic Data Scraping, Cleaning, Exploration, and Analysis via FRED API (Python)

This project demonstrates how to **retrieve, clean, analyze, and visualize economic data** using the **FRED API (Federal Reserve Economic Data)**. It focuses on key economic indicators such as:

- **S&P 500 Index**

- **U.S. Unemployment Rates**

- **State-wise Unemployment Trends** 

- **Labor Force Participation Rate**

Using **Python, pandas, matplotlib, and plotly**, this project explores economic trends through **data visualization** and **statistical analysis**.

## 🚀 How It Works

1️⃣ **Connecting to the FRED API**
- The script initializes a **connection** to the **FRED API** using an API key.
- It **searches for relevant economic indicators** such as S&P 500, Unemployment Rates, and Labor Force Participation Rates.

2️⃣ **Fetching & Cleaning Data**
- **Retrieves time-series** data for the selected indicators.
- Filters datasets to keep **only relevant** entries (e.g., seasonally adjusted unemployment rates).
- Handles **missing values** using interpolation techniques.
- **Renames** columns for readability and consistency.

3️⃣ **Exploratory Data Analysis (EDA)**
- Performs **descriptive analysis** on unemployment trends across different states.
- Analyzes **labor force participation** rates to identify patterns.

4️⃣ **Data Visualization**
- **Time-Series Analysis**: Plots historical trends for S&P 500 and unemployment rates.
- **State-by-State Unemployment Comparison**: Uses bar charts to compare unemployment rates across U.S. states.
- **Unemployment vs. Labor Participation** (New York Case Study): Creates a dual-axis plot to visualize their relationship.
## 🛠️ Technologies Used
- **Python** – Core programming language
- **Fredapi** – For API communication
- **Pandas** – For data cleaning & transformation
- **Matplotlib & Seaborn** – For visualization

## 🚀 How to Run the Project
1️⃣ **Clone this repository**:

    git clone https://github.com/Mohab-DataAnalyst/economic-data-analysis.git
    cd economic-data-analysis

2️⃣ **Install dependencies**:

    pip install pandas numpy matplotlib seaborn fredapi plotly

3️⃣ **Run the script**:

    python "Economic Data Analysis via Fred API.py"

## 📎 Acknowledgements
- This project was inspired by [@Rob Mulla.](https://youtu.be/KB2CtEDrglY?si=tUicFLHChz7cj1Vo)
- API: [@FredAPI](https://fred.stlouisfed.org/docs/api/fred/)

## ✍️ Author
- 👤 [@Mohab-DataAnalyst](https://github.com/Mohab-DataAnalyst)
