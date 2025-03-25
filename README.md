# Tableau-PowerPlant-Analysis-Dashboard


# 🌍 Global Power Plant Dashboard - Tableau Visualization  

## 📝 Project Overview  
This Tableau visualisations provide insights into global energy production trends with a special focus on **renewable energy sources**. The dataset, sourced from the [Global Power Plant Database](https://datasets.wri.org/datasets/global-power-plant-database?map=eyJ2aWV3U3RhdGUiOnsibG9uZ2l0dWRlIjoyNi40NTY5NTIzMjgyNzQ0NywibGF0aXR1ZGUiOi0yMS4xMDc1OTk0NDc5MzUxMywiem9vbSI6Mi42MTEwNDcyNDg0ODIyNDgsInBpdGNoIjowLCJiZWFyaW5nIjowLCJwYWRkaW5nIjp7InRvcCI6MCwiYm90dG9tIjowLCJsZWZ0IjowLCJyaWdodCI6MH19LCJiYXNlbWFwIjoibGlnaHQiLCJib3VuZGFyaWVzIjpmYWxzZSwibGFiZWxzIjoiZGFyayIsImFjdGl2ZUxheWVyR3JvdXBzIjpbeyJkYXRhc2V0SWQiOiI1MzYyM2RmZC0zZGY2LTRmMTUtYTA5MS02NzQ1N2NkYjU3MWYiLCJsYXllcnMiOlsiMmE2OTQyODktZmVjOS00YmZlLWE2ZDItNTZjMzg2NGVjMzQ5Il19XSwiYm91bmRzIjp7ImJib3giOm51bGwsIm9wdGlvbnMiOnt9fSwibGF5ZXJzUGFyc2VkIjpbWyIyYTY5NDI4OS1mZWM5LTRiZmUtYTZkMi01NmMzODY0ZWMzNDkiLHsidmlzaWJpbGl0eSI6dHJ1ZSwiYWN0aXZlIjp0cnVlLCJvcGFjaXR5IjoxLCJ6SW5kZXgiOjExfV1dfQ%3D%3D), contains detailed information on energy generation worldwide, including power plant capacities, fuel types, and trends over time.  

## 📂 Dataset Overview  
The dataset provides valuable insights into global energy production, with key variables including:  

| Variable | Description |
|----------|------------|
| `country` | Short country code (ISO 3-letter code). |
| `country_long` | Full name of the country. |
| `name` | Name of the power plant. |
| `capacity_mw` | Power plant capacity in megawatts (MW). |
| `primary_fuel` | Main fuel type used (e.g., Hydro, Solar, Gas). |
| `year_of_capacity_data` | Year when the power plant’s capacity (MW) was updated. |

### 📌 **Created Fields in Tableau**  
- **Renewable Primary Fuel**: Filters renewable energy fuels from `primary_fuel`.  
- **Renewable Capacity**: Calculates the total MW capacity from renewable sources.  
- **Non-Renewable Capacity**: Calculates the MW capacity from non-renewable sources.  

## 🔎 Five Key Questions for Visual Exploration  
The Tableau dashboard answers the following key analytical questions:  

1. **Which countries have the highest and lowest renewable energy production, and how is renewable energy distributed globally?**  
2. **How is renewable energy capacity distributed across different renewable sources?**  
3. **How has the energy output from renewable vs. non-renewable sources changed over the years?**  
4. **Which 10 countries have the highest renewable and non-renewable energy capacities, and how do they compare?**  
5. **How has renewable energy capacity changed year by year, and which years saw the most growth or decline?**  

## 📊 Dashboard Preview  
! Refer the pptx file uploaded in CA01-Data_Visualisation-Tableau 2.

## 🌍 Live Tableau Dashboard  
🔗 (https://public.tableau.com/app/profile/jayavardhan.premnath/vizzes)  ]

## 📥 How to Use  
1. **Download the Files**: Clone or download the repository to access the dataset and Tableau workbook (`.twbx`).  
2. **Open in Tableau**: Load the `.twbx` file in [Tableau Public](https://public.tableau.com/) or Tableau Desktop.  
3. **Explore Interactive Visualizations**: Use filters and dashboards to gain insights into global power generation.  

## ⚙️ Tools & Technologies Used  
- **Tableau** – for data visualization  
- **Excel/PDF/CSV** – for data storage *(Required fields were only considered)*  
- **SQL/Python**  

## 📌 Future Improvements  
- Enhance interactivity with **dynamic filters** and **parameter-based analysis**.  
- Integrate **real-time data updates** for live energy monitoring.  
- Expand dataset to include **carbon emissions** and **energy efficiency trends**.
- The developed KPI's can be put to a **dashboard**.

## 👨‍💻 Author & Contact  
📧 **Email**: jayavardhanp2204@gmail.com
