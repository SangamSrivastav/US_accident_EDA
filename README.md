# 📌 **US Accidents Exploratory Data Analysis (EDA) Project**

## 📂 **Project Overview**
This project focuses on performing **Exploratory Data Analysis (EDA)** on the **US Accidents Dataset** to gain insights into accident patterns, contributing factors, and trends. The dataset contains information on accidents occurring across different states in the US, collected from multiple sources such as traffic sensors, APIs, and reports.

---

## 📊 **Dataset Details**
- **Source:** [Kaggle - US Accidents Dataset](https://www.kaggle.com/sobhanmoosavi/us-accidents)
- **Format:** CSV
- **Key Features:**
  - 🆔 `ID`: Unique accident identifier
  - ⏰ `Start_Time` & `End_Time`: Timestamp of the accident
  - 📍 `Start_Lat` & `Start_Lng`: Location coordinates
  - 🏙️ `City`, `State`, `Zipcode`: Geographic information
  - ⚠️ `Severity`: Accident severity scale (1 to 4)
  - 🌡️ `Temperature`, 💧 `Humidity`, ☁️ `Weather_Condition`: Environmental factors
  - 👀 `Visibility`, 🌬️ `Wind_Speed`: Meteorological conditions
  - 🌄 `Sunrise_Sunset`, 🌙 `Civil_Twilight`: Time-based features

---

## 🎯 **Objectives**
✅ Understand accident trends across different states and cities  
✅ Identify weather and environmental factors affecting accident severity  
✅ Analyze time-based patterns (day vs. night, weekdays vs. weekends)  
✅ Visualize accident hotspots on maps  

---

## 🔍 **Exploratory Data Analysis (EDA) Steps**
### 1️⃣ **Data Preprocessing**
- Handle missing values
- Convert data types
- Remove duplicate records (if any)

### 2️⃣ **Data Exploration**
- Summary statistics of numeric and categorical columns
- Distribution of accident severity levels
- Most accident-prone cities and states

### 3️⃣ **Time-Series Analysis**
- Identify peak accident hours
- Trends across months and years

### 4️⃣ **Weather & Environmental Impact**
- Effect of temperature, humidity, and visibility on accidents
- Impact of weather conditions (rain, snow, fog, etc.)

### 5️⃣ **Geospatial Analysis**
- Mapping accident hotspots using **Folium** or **Plotly**
- State-wise and city-wise accident distribution

---

## 🛠️ **Tools & Libraries**
- 🐍 **Python** (Pandas, NumPy, Matplotlib, Seaborn, Plotly, Folium)
- 📜 **Jupyter Notebook / Google Colab**
- 🗃️ **SQL** (optional, for querying large datasets)

---

## 📌 **Key Insights & Findings**
📈 Most accidents occur during peak traffic hours (morning & evening rush hours).  
🚗 Certain states (e.g., California, Florida, Texas) report higher accident counts.  
🌧️ Poor weather conditions (fog, rain, snow) correlate with increased accident severity.  
🏙️ Urban areas have more accidents than rural regions due to high vehicle density.  

---

## 📈 **Visualizations**
📊 **Accident Count by State** (Bar Chart)  
📅 **Accidents Over Time** (Line Graph)  
🌦️ **Weather Impact on Accidents** (Heatmap)  
🗺️ **Accident Hotspots** (Interactive Map)  

---

## 🚀 **Future Improvements**
- 🤖 Implement **Machine Learning models** for accident severity prediction  
- 📡 Use **real-time accident data** for dynamic analysis  
- 🚦 Integrate **traffic and road infrastructure data** for deeper insights  

---

## 📜 **References**
- 📚 US Accidents Dataset: [Kaggle](https://www.kaggle.com/sobhanmoosavi/us-accidents)  
- 📊 Data Visualization Techniques: Matplotlib, Seaborn, Plotly  

---

## 📬 **Contact**
For queries or collaboration, reach out at **your_email@example.com** or connect via [LinkedIn](https://www.linkedin.com/yourprofile).  

---

