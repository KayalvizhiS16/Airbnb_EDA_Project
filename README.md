# 🏡 Airbnb Data Analysis — Exploratory Data Analysis (EDA)

This project focuses on analyzing Airbnb listing data to understand pricing patterns, host behavior, room availability, neighbourhood demand, and customer engagement based on reviews.
The dataset contains **20,770 entries** with **22 features** including host details, location coordinates, property characteristics, and pricing.

---

## 🔧 Data Preprocessing Steps

* Handled missing values
* Converted data types where required
* Removed duplicate entries
* Performed outlier treatment for pricing and reviews
* Standardized column names and formats


---

## 📊 Exploratory Data Analysis (EDA)

The EDA focuses on answering:

* Which neighbourhoods have the highest Airbnb listings?
* How does **room type** influence **pricing**?
* Does **location (latitude/longitude)** affect **price**?
* What is the relationship between **reviews** and **occupancy/availability**?
* Which hosts manage the highest number of listings?
* Which areas offer *budget stays* vs *premium stays*?

Visualizations include:

* 🔹 Price distribution
* 🔹 Identifying outliers in price
* 🔹 Average price per bed
* 🔹 Price dependency on neighbourhood
* 🔹 Availability 365 distribution
* 🔹 Number of reviews and price relation
* 🔹 Heat map - correlation of one variable with others for numerical column
* 🔹 Geographical Distribution of AirBnb Listing

---

## ☑ Key Insights

* Most popular neighbourhoods and central locations attract higher booking demand and charge premium prices.
* Room type and host reputation strongly influence pricing, ratings, and overall guest satisfaction.


---


## 🔍 Visualization Preview
<img width="541" height="413" alt="Price_outlier" src="https://github.com/user-attachments/assets/0e4ae7e0-0665-45b2-9522-517d2caf5b39" />
<img width="720" height="462" alt="Price distribution" src="https://github.com/user-attachments/assets/7dacea51-4eb0-4a27-97e2-357ddc9e8361" />
<img width="555" height="323" alt="Availability_distribution" src="https://github.com/user-attachments/assets/8c22d6cc-8ac1-4a9d-b01f-333b236eeec0" />
<img width="575" height="442" alt="price dependency" src="https://github.com/user-attachments/assets/87dfe958-7b7d-4a6d-83fb-4ee2fe888394" />
<img width="710" height="449" alt="reviews vs price" src="https://github.com/user-attachments/assets/db86f7b4-5335-4caf-985f-d1861173ef21" />
<img width="863" height="477" alt="geographical distribution" src="https://github.com/user-attachments/assets/44fa201f-71db-44d6-9d49-593258f9a1bd" />
<img width="752" height="475" alt="Heatmap_corr" src="https://github.com/user-attachments/assets/08f3e8d9-e08a-4427-a147-37962653fb8d" />



## 🛠 Tools & Technologies

| Tool                   | Purpose                 |
| ---------------------- | ----------------------- |
| Python                 | Data analysis           |
| Pandas                 | Data preprocessing      |
| NumPy                  | Numerical operations    |
| Matplotlib / Seaborn   | Visualizations          |
| Jupyter / Google Colab | Development environment |

---

## 🚀 Future Improvements

* Price prediction using Machine Learning
* Geospatial mapping using Folium / Kepler.gl
* Interactive dashboards using PowerBI / Tableau
