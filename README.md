# 🗽 Airbnb NEW YORK EDA Project 
 
![airbnb](https://github.com/user-attachments/assets/1b88aaf5-b108-4c28-bb98-0c662c49a2ae)

## 📌 Project Overview
This project explores Airbnb listings in New York City using **Exploratory Data Analysis (EDA)** techniques. It helps uncover patterns related to **pricing, availability, neighborhoods**, and **room types**. The analysis was done using Python libraries like **Pandas, NumPy, Matplotlib,** and **Seaborn**.

---

## 🎯 Objectives
- Analyze **price distribution** and detect outliers.
- Compare **room types** across NYC boroughs.
- Study **availability patterns** and **host behavior**.
- Perform **correlation analysis** on key features.
- Provide **data-driven recommendations** for hosts and guests.

---

## 📂 Dataset
The dataset contains 20,765 entries and 22 features, including:
- `id`, `host_id`: Unique identifiers  
- `neighbourhood_group`, `neighbourhood`: Location details  
- `latitude`, `longitude`: Coordinates  
- `room_type`: Entire home, private room, etc.  
- `price`: Nightly cost  
- `minimum_nights`, `availability_365`: Booking metrics  
- `number_of_reviews`, `reviews_per_month`: Guest engagement  
- `beds`: Number of beds available  

---

## 🔄 Data Preprocessing
- Removed rows with missing or duplicate values.
- Converted data types for `id`, `host_id`.
- Fix data types: Converted last_review to a datetime object.
- Filtered out listings with **price > $1500** to avoid skew.
- Created a new column: `Price per Bed`.

---

## 📊 Key Analysis & Visuals

### 🏠 Room Types and Prices
- **Entire home/apt** listings are most expensive.
- **Private rooms** are common and more budget-friendly.

### 🗺 Neighborhood Insights
- **Manhattan** has the highest average prices.
![PYTHON QUERY](https://github.com/user-attachments/assets/5d5f4667-0994-4d8c-8e03-9850bf8f0040)


- Bar plots show how **room type affects pricing across boroughs**.
![BARPLOT](https://github.com/user-attachments/assets/f4fb3789-4a5a-4ca2-bac7-3da5b04b6476)


### 🔥 Price Distribution
- Majority of listings fall between **$50 - $300**.
- Outliers were visualized using boxen plots and histograms.
![{9F5AD31D-DEDA-40DB-B4A2-22686F287D0F}](https://github.com/user-attachments/assets/e8f36a7d-d0ca-4c97-aeea-c7d903ce0955)
![histplot](https://github.com/user-attachments/assets/8c63949a-d0e3-48d7-b2fa-811bb8f66437)
---

## 💡 Key Insights
- Listings with more availability tend to have **lower prices** and **more reviews**.
- A few hosts have **multiple listings**, indicating a shift toward professional hosting.
- Price per bed varies significantly by **neighbourhood group**.

## Recommendations
* #### For Guests
  * Look for listings with high availability and good reviews for a better experience.
  * Private rooms in Brooklyn offer affordable stays compared to Manhattan.
* #### For Hosts:
  * Improve availability and review response rates to attract more bookings.
  * Manage pricing effectively to compete within the borough's market.

## Conclusion
This project offers valuable insights into the New York Airbnb market, helping both guests and hosts make informed decisions. By using EDA techniques, we identified key trends and developed actionable recommendations. Future improvements can involve advanced analytics and predictive modeling to further enhance the findings.
