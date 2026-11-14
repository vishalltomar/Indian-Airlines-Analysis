<div align="center">

# ✈️ Indian Airlines Analysis Dashboard

### *Compare performance, passenger traffic, ratings and more across Indian airlines*

![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![DAX](https://img.shields.io/badge/DAX-FF5722?style=for-the-badge)
![Excel](https://img.shields.io/badge/Excel-217346?style=for-the-badge&logo=microsoftexcel&logoColor=white)
![Status](https://img.shields.io/badge/Status-Completed-success?style=for-the-badge)

<br>

<img src="images/dashboard.png" alt="Indian Airlines Dashboard Preview" width="95%">

</div>

<br>

---

## 🌟 About the Project

An interactive **Power BI dashboard** that brings Indian aviation data to life. Pick an airline from the top bar and the entire report updates with its KPIs, aircraft image and charts, with extra filters for **route** and **destination city**.

> 🛫 **Airlines covered:** Air India · Akasa Air · IndiGo · SpiceJet · Star Air

---

## ✨ Features

| | Feature | Description |
|:-:|---|---|
| 🎛️ | **Airline Selector** | Switch between 5 airlines with one click |
| 📍 | **Smart Slicers** | Filter by Route and Destination City |
| 📈 | **KPI Cards** | Headline numbers update dynamically |
| 🖼️ | **Dynamic Aircraft Image** | The plane changes with the selected airline |
| 🎨 | **Custom Design** | Clean, modern layout with branded header |

---

## 📊 KPIs Tracked

<div align="center">

| 👥 Total Passengers | 💺 Passenger Capacity | 🌿 CO₂ per Passenger | ⛽ Fuel Efficiency | ⏱️ Avg. Flight Duration |
|:-:|:-:|:-:|:-:|:-:|
| Per airline | Seats available | In kg | Fuel usage metric | In minutes |

</div>

---

## 📉 Visuals

| Chart | Insight |
|---|---|
| ⭐ **Airline Ratings** | Average customer rating out of 5 |
| 📅 **Monthly Passenger Trend** | Passenger volume in millions over time |
| 📈 **Passengers by Airline** | Year-wise trend from 2023 to 2026 |
| 🍩 **Estimated Profit by Airline** | Profit share of each airline |

---

## 🛠️ Tech Stack

- 🟨 **Power BI Desktop** for modeling and visuals
- 🧮 **DAX** for measures, organized in a dedicated Measure Table
- 📗 **Excel / CSV** for source data

---

## 🗂️ Data Model

```
📦 Data
 ┣ 📄 Flight_Data       → flights, passengers, ratings, fuel, duration, profit
 ┣ 🖼️ Aircraft_Images   → aircraft image for each airline
 ┗ 🧮 Measure Table     → all DAX measures
```

---

## 📁 Repository Structure

```
📦 indian-airlines-dashboard
 ┣ 📊 airlines_analysis_dashboard.pbix
 ┣ 📂 data
 ┣ 📂 images
 ┃ ┗ 🖼️ dashboard.png
 ┗ 📝 README.md
```

---

## 🚀 Getting Started

```bash
# 1. Clone the repository
git clone https://github.com/vishalltomar/<repo-name>.git

# 2. Open the .pbix file in Power BI Desktop

# 3. Click an airline and explore!
```

---

## 💡 What I Learned

- 🎯 Designing a clean, user-friendly report layout
- 🧮 Writing DAX measures and organizing them in a measure table
- 🖱️ Building interactive reports with slicers and buttons
- 📖 Telling a story with data, not just showing charts

---

## 🔮 Future Improvements

- [ ] Add more airlines and routes
- [ ] On-time performance and delay analysis
- [ ] Ticket price comparison page
- [ ] Publish to Power BI Service for live sharing

---

<div align="center">

## 👨‍💻 Author

**Vishal Tomar**
*B.Tech CS Student · Aspiring Data Analyst*

[![GitHub](https://img.shields.io/badge/GitHub-vishalltomar-181717?style=for-the-badge&logo=github)](https://github.com/vishalltomar)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Vishal%20Tomar-0A66C2?style=for-the-badge&logo=linkedin)](https://linkedin.com/in/vishal-tomar-34b640311)

<br>

⭐ **If you liked this project, give it a star!** ⭐

</div>
