# weather-data-api-project1
Analyzing weather patterns using Open-Meteo API and pandas.
his mini-project explores historical weather data using the [Open-Meteo API](https://open-meteo.com/). The goal was to fetch, clean, and analyze hourly weather data for **New York City** and **Los Angeles**, and compare their temperature patterns over one week.

---

## 📌 Project Goals

- Retrieve historical weather data from a real-world API
- Convert and clean JSON data using `pandas`
- Perform exploratory data analysis (EDA)
- Visualize weather trends such as temperature, humidity, and precipitation
- Compare weather between two major cities
- Save cleaned and processed datasets for future use

---

## 🧪 Tools Used

- Python
- Jupyter Notebook
- `requests` for API calls
- `pandas` for data wrangling
- `matplotlib` for visualization

---

## 🔍 Key Steps Completed

 Accessed weather data via Open-Meteo API  
 Cleaned and preprocessed data (datetime formatting, missing values)  
 Created line and bar plots for analysis  
 Resampled hourly data to daily averages  
 Compared temperatures between NYC and LA  
 Calculated and visualized daily temperature differences  
 Saved results to CSV files

---

## 📈 Example Visualizations

- Line plots for hourly temperature, humidity, and precipitation  
-  Scatter plot: Temperature vs. Humidity  
- Bar chart: Daily temperature comparison between NYC and LA  
- Temperature difference chart (LA − NYC)

---

## 📂 Files Included

| File | Description |
|------|-------------|
| `api_data_wrangling.ipynb` | Main notebook with full code and analysis |
| `new_york_weather.csv` | Cleaned hourly weather data for NYC |
| `los_angeles_weather.csv` | Cleaned hourly weather data for LA |
| `ny_vs_la_comparison.csv` | Daily average temps and differences |

---

## 🚀 Next Steps (Optional Extensions)

- Extend the time range to a full month or year
- Add more weather variables (e.g., wind speed, pressure)
- Forecast weather using machine learning models
- Compare additional global cities

---

## 📬 Contact

Project by [Your Name]  
Data sourced from [Open-Meteo](https://open-meteo.com/)
