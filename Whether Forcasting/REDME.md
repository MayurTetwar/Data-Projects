# 🌦️ Weather Forecasting Dashboard – Power BI

An interactive **Weather Forecasting Dashboard** built using **Power BI** with real-time data fetched through an external Weather API.  
The dashboard displays current weather conditions, air quality, sunrise/sunset time, and a 7-day forecast based on the selected city.

---

## 📌 Project Overview

This weather dashboard provides users with an intuitive and beautiful UI to check:
- **Current weather**  
- **Temperature**  
- **Visibility**  
- **Humidity**  
- **Wind speed**  
- **Air Quality Index (AQI)**  
- **Sunrise & Sunset timings**  
- **Chance of rain**  
- **7-day forecast curve**
  
The report updates dynamically based on **city selection**, making it fully interactive.

---

## 🖼️ Dashboard Preview

![Weather Dashboard](https://github.com/MayurTetwar/Data-Projects/blob/ff961dd1aff4b9a2a91d6ef5a91a3e496db26a6d/Whether%20Forcasting/Wheter_Forcasting_DashBoard.png
)

---

## ⭐ Key Features

### ✔️ **City-Based Weather Search**
Select any city from the dropdown, and the dashboard updates instantly with fresh weather details.

### ✔️ **Real-Time API Integration**
- Fetches **live temperature**, **AQI**, **humidity**, **wind**, and other weather details  
- Uses **Current Weather API** call for up-to-date data  

### ✔️ **7-Day Weather Forecast (Originally Available)**
- Temperature trend chart for the upcoming days  
- Icons for weather conditions (sunny, mist, cloudy, rainy, etc.)

### ✔️ **Air Quality Index (AQI) Gauge**
Displays:
- PM10  
- PM2.5  
- CO  
- NO2  
- O3  
- SO2  

With color-coded indicators.

### ✔️ **Sunrise & Sunset Panel**

### ✔️ **Chance of Rain Analysis for 7 Days**
Shows the probability of rain for everyday in a weekly range.

---

## ⚠️ Important Note

When this project was created, the **Weather API free trial allowed complete 7-day forecasting**.  
After the free-trial expired, the API provides **only 3-day forecast**, which is why the current version may show fewer days.

---

## 🛠️ Tech Stack / Tools Used

- **Power BI Desktop**
- **Weather API (Current + Forecast endpoints)**
- **Power Query**
- **JSON Parsing**
- **Custom Visualization Design**
- **Icons & UI Enhancements**


---

## 🔗 How It Works (Technical Flow)

1. **User selects a city**  
2. Power Query constructs the API URL dynamically  
3. API returns real-time weather JSON  
4. JSON is transformed into tables  
5. Power BI visuals update instantly  

---

## 📚 Learning Outcome

Through this project, I gained experience in:
- Connecting Power BI to external APIs  
- Working with JSON & dynamic URLs  
- Designing dashboards with dark/light theme contrast  
- Handling API limitations & refresh logic  
- Creating forecasting visuals  

---

## 👨‍💻 Author

**Mayur Tetwar**  
Data Analyst | Power BI | Python | SQL | Visualization  

GitHub: https://github.com/MayurTetwar  

---

⭐ *If you like this project, please star the repository!*  

