# 🌦️ Weather Chronicles: Unveiling the Stories Behind the Skies

An exploratory data analysis (EDA) project that transforms raw meteorological data into compelling narratives about our changing climate.

## 📖 The Story
Every data point tells a story—a record-breaking heatwave, a surprisingly dry spring, or the subtle shift in seasonal patterns over decades. This project goes beyond simple charts to answer: *How is our local environment actually changing, and what does that mean for the way we live?*


## 📊 The Data Source
Some Data for this project may be sourced from **[Insert Source Name, e.g., OpenWeatherMap or NOAA]**. 
*   **Timeframe:** [e.g., Jan 2010 - Dec 2023]
*   **Granularity:** [e.g., Hourly/Daily observations]
*   **Variables:** Temperature, Precipitation, Wind Speed, and Humidity.

## 💻 Getting Started
1. **Clone the repo:** `git clone https://github.com`
2. **Run in Colab:** Open any file in the `notebooks/` folder and click the "Open in Colab" badge.
3. **Install Dependencies:** 
   ```bash
   pip install pandas matplotlib seaborn plotly

## 🔑 How to Get a NOAA API Token

This project may use the [NOAA Climate Data Online (CDO) API](https://www.ncdc.noaa.gov).

### Step 1: Request the Token
1. Go to the [NOAA Token Request Page](https://www.ncdc.noaa.gov).
2. Enter your **Email Address** and click **Submit**.
3. Check your inbox for your unique **API Token**.

### Step 2: Securely Store the Token in Colab
1. Click the **Key icon** (🔑) in the Google Colab sidebar.
2. Click **+ Add new secret** and name it `NOAA_TOKEN`.
3. Paste your token into the **Value** box and toggle **Notebook access** to **ON**.

