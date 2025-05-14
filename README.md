### Cognifyz Data Analytics Internship: Cuisines & Restaurant Dataset Analysis (Python)
Welcome to my internship project completed as a Data Analytics Intern at Cognifyz Technologies. Over the course of this internship, I explored a restaurant dataset to uncover insights related to cuisines, city-wise restaurant trends, ratings, cuisine combinations, and geographic distribution using Python and key data analysis libraries such as Pandas, Matplotlib, and Seaborn.

📁 Dataset Overview
The dataset contains 9,551 entries with 21 columns, including:
• Restaurant Name, City, Country
• Cuisines, Address, Latitude, Longitude
• Ratings, Votes, Average Cost for Two
• Online Delivery & Table Booking Availability

🔹 Internship Task Overview

🔹 Task 1: Data Exploration & Cleaning:
• Imported essential Python libraries.
• Loaded the dataset using pandas.
• Performed data exploration using .head(), .info(), and .describe().
• Cleaned missing values and standardized the Cuisines and City columns for consistency.

🔹 Notebook: 01_data_cleaning.ipynb

🔹 Task 2: Top Cuisines Analysis:
• Split multi-cuisine entries into individual cuisine types.
• Counted and visualized the most common cuisines.
• Identified Top 3 Cuisines:
• North Indian (41.46%)
• Chinese (28.63%)
• Fast Food (20.79%)

🔹 Visualization: Bar Chart

📂 Notebook: 02_cuisine_analysis.ipynb

🔹 Task 3: City-Wise Analysis:
• Identified cities with the highest number of restaurants.
• Calculated average ratings per city.
• Found New Delhi as the city with the highest number of restaurants (5,473).

📂 Notebook: 03_city_analysis.ipynb

🔹 Task 4: Ratings & Votes Distribution:
• Analyzed the distribution of aggregate ratings.
• Found that the majority of ratings were between 3.0 and 4.0.
• Calculated the average number of votes per restaurant (~157 votes).

📂 Notebook: 04_rating_analysis.ipynb

🔹 Task 5: Cuisine Combination Patterns:
• Extracted common cuisine pairings.
• Analyzed and visualized frequently occurring combinations.
• Highlighted high-rated unique combinations like:
    • (breakfast, southern, bbq)
    • (burger, grill, american)

📂 Notebook: 05_cuisine_combination_analysis.ipynb

🔹 Task 6: Geographic Insights:
• Prepared for future integration with Folium for interactive maps (Note: Pure Python tasks, maps not included).
• Identified restaurant distributions across metro regions.

📂 Notebook: 06_geographic_overview.ipynb

🔹 Key Takeaways
• North Indian, Chinese, and Fast Food dominate the restaurant scene.
• New Delhi tops in restaurant density and variety.
• Ratings are clustered around the 3–4 range, with a few high-rated cuisine combos.
• Effective data cleaning plays a crucial role in meaningful analysis.

🔹 Tools & Libraries Used
• Python
• Pandas
• Matplotlib
• Seaborn
• NumPy

🗂️ Repository Structure

• cognifyz-restaurant-analysis/
│
├── Dataset.csv
├── 01_data_cleaning.ipynb
├── 02_cuisine_analysis.ipynb
├── 03_city_analysis.ipynb
├── 04_rating_analysis.ipynb
├── 05_cuisine_combination_analysis.ipynb
├── 06_geographic_overview.ipynb
└── README.md

🔹 Future Enhancements
• Add Folium for interactive maps and density heatmaps.
• Develop a dashboard using Streamlit for user exploration.
• Include a predictive model to forecast restaurant ratings or success based on cuisine and location.

🔹 Internship Summary
• Role: Data Analytics Intern
• Company: Cognifyz Technologies
• Focus Areas: Data Cleaning, EDA, Visualization
• Duration: 1 Month
• Tools Used: Python, Pandas, Matplotlib, Seaborn

🔹 Let's Connect
If you’re interested in data analytics, visualization, or project collaboration, feel free to connect with me on Linkedin(www.linkedin.com/in/garimasingh7g) or explore more of my work on GitHub.
