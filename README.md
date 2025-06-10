# 📊 Adidas USA Sales
An interactive Tableau dashboard that visualizes Adidas sales data in the U.S. from 2020 to 2021, helping users quickly explore where and how sales are performing across different segments — all built entirely in Tableau.


## 📂 Contents
Click the image below to see for yourself:

<a href="https://public.tableau.com/app/profile/nadir.zamouche/viz/AdidasUSASalesDashboard_17490873580120/Dashboard" target="_blank">
    <img width="1280" alt="Screenshot 2024-06-11 230236" src="https://github.com/user-attachments/assets/33bdb87f-0616-4eb3-bc30-3efb6bfd53b8"/>
</a>

## 📈 Features
💵 Total Sales ($115.5M) and Profit ($32.1M). <br>
📅 Monthly sales trend analysis. <br>
🛍️ Sales breakdown by Retailer. <br>
🗺️ Geographic visualization of sales by state. <br>
🌐 Comparison of Online vs Outlet vs In-store sales. <br>
🎛️ Dynamic filters for Year, Region, and Product. <br>

## 📌 Notes
- Assigned a *Geographic Role* to the *Region* field as *Country/Region*.  
- Renamed columns:  
  - `Total Sales` → `Sales`  
  - `Operational Profit` → `Profit`
- I have gotten rid of *Retailer Id* column since I didn't need it.
- Applied a *Data Source Filter* to exclude *Alaska* & *Hawaii* from the *State* field only for dashboard layout purposes.  
- Added filters for every single chart to enhance interactivity.  
  - Selecting a specific thing dynamically updates the values of the other sheets in the dashboard.
