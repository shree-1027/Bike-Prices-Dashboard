🏍️ Bike Prices Dashboard 

📊 Overview
This project analyzes a dataset of used motorcycles using Python, uncovering trends in pricing based on ownership, brand, model year, and location. It features a visually engaging dashboard with custom 3D cylinder-style bar charts to present insights more effectively.

🔍 Objectives
•	Analyze key factors affecting bike prices
•	Explore price variation by:
•	Ownership type
•	Model year
•	Brand
•	Location
•	Use custom 3D-style bar plots to enhance visual storytelling

🧰 Tools & Technologies
•	Python (Pandas, Seaborn, Matplotlib)
•	Data Visualization with custom 3D cylinder effects using matplotlib.patches.Ellipse
•	Clean white-themed dashboard for professional presentation

📁 Dataset
The dataset (bikes.csv) includes:
•	model_name
•	price
•	owner
•	model_year
•	location
•	mileage, power, etc.

Basic preprocessing includes:
•	Extracting brand names from model strings
•	Converting mileage/power columns to numeric
•	Grouping and aggregating price data

📈 Dashboard Features
1. Price Distribution
A histogram showing the overall price distribution with KDE overlay.
2. Average Price by Owner Type
Cylinder-style bar chart illustrating how price varies across first, second, and other owner types.
3. Average Price Over Model Years
Line plot highlighting trends in average pricing over time.
4. Top 10 Brands by Average Price
Comparison of the highest-priced brands using 3D-style bars.
5. Top 15 Locations by Average Price
Visualizing geographic pricing trends using location-based averages.
6. Median Price by Ownership
Helps identify typical prices by owner category, less affected by outliers.

🎨 Visual Style
•	Clean white background
•	Customized 3D cylinder bar effects
•	Rotated axis labels for readability
•	Annotated bars for direct value display

🚀 Getting Started
Prerequisites
pip install pandas seaborn matplotlib
Run the Dashboard
python bikes_dashboard.py

🧠 Learnings
•	Practice in data cleaning and aggregation
•	Created custom visual effects in matplotlib
•	Explored how ownership history, brand, and location affect resale pricing


