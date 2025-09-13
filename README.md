# 🏅 Tokyo Olympics 2020 Analytics Dashboard

An interactive Power BI dashboard providing a comprehensive snapshot of the Tokyo 2020 Olympic Games performance, medal standings, and participant demographics. This project showcases advanced Power BI capabilities including robust data modeling, dynamic DAX measures, and intuitive data visualization design.

---

## ✨ Live Dashboard Demo

Experience the interactive dashboard yourself! Explore medal distributions, top-performing countries, and participant gender splits, with dynamic filtering capabilities.

➡️ **[View Live Dashboard Here](YOUR_PUBLIC_POWER_BI_LINK_HERE)** ⬅️

<img width="1174" height="659" alt="Screenshot 2025-09-13 at 3 17 14 PM" src="https://github.com/user-attachments/assets/59b212ab-7efb-4be2-b1c3-1e8413ca6345" />


---

## 🎯 Project Goal

The primary goal of this project was to:
* Consolidate disparate CSV datasets related to the Tokyo 2020 Olympics.
* Develop a single, interactive Power BI dashboard for quick, high-level insights.
* Enable users to explore medal standings, participant demographics, and discipline-specific performance.
* Demonstrate strong data analysis, modeling, and visualization skills in Power BI.

---

## 📊 Dashboard Overview

The dashboard is designed as a single-page interactive report, structured for easy navigation and comprehensive insights:

1.  **Global KPIs:** Quick overview of total medals (Gold, Silver, Bronze), participating countries, and disciplines.
2.  **Medal Standings:** Dynamic table showing country ranks based on total medals, with conditional formatting for top performers.
3.  **Medal Distribution:** Donut chart visualizing the global proportion of Gold, Silver, and Bronze medals.
4.  **Top Countries by Medals:** Bar chart highlighting countries with the highest total medal counts.
5.  **Participant Gender Split:** Donut chart illustrating the male-to-female ratio among all participants.
6.  **Top Disciplines by Participants:** Bar chart showcasing the sports with the highest number of athletes.
7.  **Medals Awarded per Discipline:** Column chart comparing Gold, Silver, and Bronze medals won across various disciplines.

The entire dashboard is cross-filterable by `Country` and `Discipline`, allowing users to drill down into specific areas of interest.

---

## 🛠️ Technical Stack & Features

* **Platform:** Microsoft Power BI Desktop
* **Data Source:** Multiple CSV files (Participants, Team Details, Discipline Gender Counts, Medal Standings, Team Event Breakdown)
* **Data Transformation:** Power Query M-language for data cleaning, shaping, and merging.
* **Data Modeling:** Established robust relationships between tables to ensure accurate data aggregation and filtering.
* **DAX Measures:** Developed advanced Data Analysis Expressions for:
    * Dynamic ranking (`Rank by Total Medals` using `RANKX` and `ALLSELECTED`).
    * Calculating `Overall Total Medals`, `Total Participating Countries`, `Total Disciplines`, `Overall Participants`, `Male Count`, `Female Count`, etc.
* **Data Visualization:** Implemented a dark-themed, modern design with custom colors, conditional formatting, and interactive slicers.
* **Deployment:** Published to Power BI Service with "Publish to web" for public access.

---

## 🚀 Getting Started

To explore or modify this project:

1.  **Clone the Repository:**
    ```bash
    git clone [https://github.com/YOUR_GITHUB_USERNAME/tokyo-olympics-dashboard.git](https://github.com/YOUR_GITHUB_USERNAME/tokyo-olympics-dashboard.git)
    ```
2.  **Download Power BI Desktop:** Ensure you have [Power BI Desktop](https://powerbi.microsoft.com/desktop/) installed (Windows OS required).
3.  **Open the Project:** Open the `Tokyo Olympics 2020 Analytics.pbix` file in Power BI Desktop.
4.  **Data Refresh:** The dashboard is configured to connect to CSV files. Ensure the CSV files are located in the same directory as the `.pbix` file, or update the data source paths in Power Query Editor if moved.

---

## 📁 Project Structure
├── Tokyo Olympics 2020 Analytics.pbix
├── data/
│   ├── Participants.csv
│   ├── Team_Details.csv
│   ├── Discipline_Gender_Counts.csv
│   ├── Medal_Standings.csv
│   └── Team_Event_Breakdown.csv
└── README.md

---

## 🤝 Contributing

Feel free to fork this repository, suggest improvements, or submit pull requests. Any contributions are welcome!

---

## 📜 License

This project is open-source and available under the [MIT License](LICENSE). *(Consider adding a LICENSE file to your repo)*

---

## 🙏 Acknowledgements

* Data sourced from various public datasets related to the Tokyo 2020 Olympic Games.
* Power BI community and documentation for continuous learning.

---
