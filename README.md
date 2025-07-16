# API-INTEGRATION-AND-DATA-VISUALIZATION

**COMPANY: CODTECH IT SOLUTIONS

NAME:VEDANT AVINASH KHARANGKAR

INTERN ID:CT06DH1250

DOMAIN: PYTHON PROGRAMMING

DURATION:6 WEEKS

MENTOR: NEELA SANTOSH**

# DESCRIPTION OF TASK

# 📊 API Integration and Data Visualization

## 📌 Project Overview

This project demonstrates how to **fetch real-time weather data** from a public API (OpenWeatherMap) and present it in a **tabular** and **graphical format** using Python.  
Developed entirely in **Google Colab**, it focuses on weather forecasting for **Nagpur, India**, displaying data for the next **5 days at 12 PM**.

Users will learn how to connect to APIs, extract structured data, and visualize parameters like **temperature**, **min/max temperatures**, and **pressure**.

---

## 🔧 Tools & Technologies Used

- **Language:** Python 3  
- **API:** OpenWeatherMap (5-day forecast)  
- **Libraries Used:**
  - `requests` – for HTTP requests  
  - `datetime` – for time/date handling  
  - `matplotlib` – for data visualization  
  - `json` – for parsing API responses  
- **Platform:** Google Colab (no installation required, runs in-browser)

---

## 🔄 Workflow

### ✅ Step 1: Fetch Weather Data
- Use `requests.get()` to call the OpenWeatherMap API  
- Include:
  - City coordinates (latitude & longitude)  
  - API key  
  - Unit type: `metric`  
- Receive a JSON response with 3-hour interval forecasts

### ✅ Step 2: Extract Relevant Data
- Filter data to include **only 12:00 PM** entries for each day  
- Extract:
  - 📅 Date  
  - 🌡 Temperature  
  - 🔻 Min / 🔺 Max Temperatures  
  - 💧 Humidity  
  - 🌫 Weather Description  
  - 🌬 Atmospheric Pressure

### ✅ Step 3: Tabular Representation
- Format the extracted data into a clean, readable table using Python string formatting

### ✅ Step 4: Graphical Visualization
- Plot the following using `matplotlib`:
  - Daily temperature  
  - Min/Max temperature  
  - Atmospheric pressure  
- Use **dual Y-axes**, **legends**, and **rotated x-ticks** for better readability

---

## 🎯 Learning Objectives

By completing this project, you’ll learn:

- 📡 How to connect to external REST APIs  
- 📁 How to parse and handle JSON data  
- 🧮 How to filter data using datetime  
- 📋 How to display data in a structured table  
- 📊 How to create multi-line and dual-axis plots

---

## 💡 Use Cases & Applications

- 🎓 **Educational Projects** – Great for learning data analysis and APIs  
- 🌦 **Weather Dashboards** – Can be integrated into web or IoT systems  
- 📰 **News & Utility Apps** – Use this logic in weather feature integration  
- 📈 **Data Journalism** – Visualize weather trends over time

---

## 🚀 Future Enhancements

- 🔄 Add user input to allow city selection  
- 🌄 Display weather icons  
- 📊 Use `pandas` DataFrames or save to CSV  
- 🌬 Add extra parameters like wind speed, visibility  
- 💻 Build a GUI with **Tkinter** or use **Streamlit** for web interactivity

---

## ▶️ How to Run the Project

1. Open **[Google Colab](https://colab.research.google.com/)**  
2. Paste the full Python code into a new notebook  
3. Install any missing libraries using `!pip install` (e.g., `requests`, `matplotlib`)  
4. Run the code cells and view output directly in the browser  

---

> ⚠️ *Make sure to replace the placeholder API key with your actual OpenWeatherMap API key.*

---

## 🙌 Contributions & Feedback

Feel free to fork this repo, open issues, or suggest improvements via pull requests!

---



