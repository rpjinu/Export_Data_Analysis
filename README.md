# Export_Data_Analysis
ALL python jupyter notebook

<img src="https://github.com/rpjinu/Export_Data_Analysis/blob/main/export%20image.png">

# 🌾 Spice Trade and Production Analysis 

Welcome to the repository! This project dives into the trade, production, and consumption patterns of **spices** (Anise, Badian, Coriander, Cumin, Caraway, Fennel, Juniper) in **Afghanistan** from **2014 to 2018** using FAO statistics 📊

---

## 📂 Dataset Overview

| Column Name | Description |
|-------------|-------------|
| `Domain Code` | Code representing the domain (TCL = Crops and Livestock Products) 🌾 |
| `Domain` | Description of domain (Crops and Livestock Products) 🐄🌱 |
| `Area Code (M49)` | UN M49 code for country/area (4 = Afghanistan) 🌍 |
| `Area` | Country name (Afghanistan 🇦🇫) |
| `Element Code` | Code for the element (5610 = standard for trade/production/consumption data) 🛠️ |
| `Item Code (CPC)` | FAO CPC code (1654 = Spice mixture) 🥄 |
| `Item` | Description of item (Anise, badian, coriander, cumin, caraway, fennel, juniper berries) 🌿 |
| `Year` | Year of record (2014–2018) 📅 |
| `Unit` | Measurement unit (`t` = metric tonnes) ⚖️ |
| `Import` | Quantity imported into Afghanistan (tonnes) 🚢 |
| `Export` | Quantity exported from Afghanistan (tonnes) ✈️ |
| `Production` | Domestic production quantity (tonnes) 🏭 |
| `Consumption` | Domestic consumption quantity (tonnes) 🍽️ |

---

## 🎯 Project Objectives

- 📈 Understand trade flows (Import/Export trends)
- 🏭 Analyze production trends of key spices
- 🍽️ Estimate domestic consumption patterns
- 🔍 Identify self-sufficiency — Is Afghanistan a net exporter/importer?

---

## 🛠️ Project Workflow

1️⃣ **Data Cleaning**  
➡️ Removed unnecessary columns  
➡️ Checked and handled missing values (if any)

2️⃣ **Exploratory Data Analysis (EDA)**  
- 📊 Trend analysis of import, export, production, and consumption (2014–2018)
- 📉 Correlation analysis between trade and production/consumption

3️⃣ **Visualizations**  
- 📈 Line plots for yearly trends
- 🛠️ Bar charts for comparing imports vs exports

4️⃣ **Insights & Reporting**  
- ✍️ Summarized findings
- 📝 Documented actionable insights

---

## 📊 Key Insights

- 🚢 **Exports dominate**: Afghanistan consistently exported large quantities of spices compared to imports  
- 🏭 **Steady production**: Domestic production ranged between ~17k and ~21k tonnes  
- 🍽️ **Low domestic consumption**: Consumption was much lower than production → significant export economy  
- 🔄 **Trade balance**: Afghanistan is a **net exporter** of these spices

---

## 🖥️ Technologies Used

- 🐍 Python (Pandas, NumPy, Matplotlib, Seaborn)
- 📊 Jupyter Notebook
- 📝 Git & GitHub for version control

---

## 🚀 How to Run

```bash
git clone https://github.com/yourusername/spice-trade-afghanistan.git
cd spice-trade-afghanistan
jupyter notebook
