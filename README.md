# ✈ Aircraft Occupancy Optimization 
*Data-Driven Approaches to Strengthen Airline Profitability*

![Occupancy Impact](images/occupancy_impact.png)

---

## 📌 Introduction

Company operates a diverse fleet of small business jets and medium-sized aircraft, delivering safe, comfortable, and reliable air transportation. In recent times, profitability has come under pressure due to:
- **Stricter environmental regulations** → Higher compliance and operational costs
- **Rising fuel prices** → Significant cost increases
- **Higher flight taxes** → Added financial burdens
- **Tight labor market** → Increased wages, high turnover
- **Elevated interest rates** → Costlier financing and capital investment

➡ **Objective:** Leverage data analysis to identify strategies that:
- Increase occupancy rate
- Improve pricing strategy
- Boost profit per seat without compromising service quality

---

## ⚙️ Tools & Technology

- **Python**: Data analysis (Pandas, NumPy), visualizations (Matplotlib, Seaborn)
- **Jupyter Notebook**: Interactive analysis and reporting
- **SQL** (if applicable): Data querying from internal databases
- **Excel**: Supporting analysis and validation

---

## 🛠️ Data Cleaning & Preprocessing

- Removed duplicate and irrelevant entries (e.g., cancelled flights)
- Handled missing values in booking and pricing data
- Standardized data types (dates, prices, seat counts)
- Engineered features:
  - `occupancy_rate` = booked seats / total seats
  - `avg_revenue_per_seat` = total revenue / total seats

---

## ✈️ Fleet Overview

| Aircraft | Number of Seats |
|-----------|----------------|
| 319 | 116 |
| 320 | 140 |
| 321 | 170 |
| 733 | 130 |
| 763 | 222 |
| 773 | 402 |

*Focus: Increase seat utilization across the fleet.*

---

## 📈 Key Insights

- Ticket bookings increased from **June 22 to July 7**, then stabilized.
- **SU9** generated the highest revenue due to high ticket volumes despite low pricing.
- **CN1** had the lowest revenue — low demand and economy-only class.
- Business class pricing consistently higher, but underutilized on certain aircraft.

![Average Fare by Class](images/avg_fare_class.png)

---

## ⚠️ Key Challenges

- Low occupancy on specific aircraft → inefficient revenue generation
- Inconsistent pricing → misaligned with aircraft condition/demand
- Limited premium offerings → missed opportunities for high-margin sales
- Demand fluctuation → hard to predict peak and low-demand periods

---

## 🔑 Key Outcomes

- Identified underperforming aircraft and routes
- Pinpointed pricing mismatches limiting revenue
- Modeled 10% occupancy improvement → gradual revenue increase
- Provided recommendations for pricing and service adjustment

![Occupancy Impact](images/occupancy_impact.png)

---

## ✅ Conclusion

Data analysis shows that raising occupancy rates is critical to improving profitability amid rising costs. A balanced strategy — combining smart pricing, targeted scheduling, and improved service — can help the airline maintain competitiveness and financial health.

> Airlines should aim for a **data-driven, customer-focused approach** while keeping safety and service quality at the forefront.

---

## 📂 Project Files

- `Airlines_Analysis.ipynb`: Full analysis notebook  
- `Report_Airlines.pdf`: Summary report  
- `images/`: Folder with generated charts and visuals

---

## Contact 
bhaskarpal.official@gmail.com
