# 🚕 GoodCabs Business Performance Analysis (Jan–Jun 2024)

## 🔍 Case Overview

**GoodCabs**, a ride-hailing platform for tier-2 Indian cities, saw red flags in **June 2024**—a sudden **₹26L revenue drop**.

This case study analyzes:
- Revenue trends
- Repeat passenger patterns
- Trip frequency distribution
- Passenger satisfaction
- City-level anomalies and targets

The goal: Identify what's going wrong, where, and how to fix it before losses scale to ₹1 Cr+ in the next 3 months.

---

## 🏭 Domain  
**Industry**: Transportation / Mobility  
**Business Model**: Two-sided marketplace (Passengers ↔ Drivers)

---

## 🧾 Data Overview

**Time Frame**: Jan–Jun 2024  
**Volume**: 425K rows  
**Data Cleanup**: Null handling, duplicates removed, outliers treated

### 📦 Data Tables

| Table Name                        | Description |
|----------------------------------|-------------|
| `dim_city`                       | City metadata (`city_id`, `city_name`) |
| `dim_date`                       | Calendar reference (`date`, `month`, `day_type`) |
| `fact_passenger_summary`        | Monthly passenger data (total, new, repeat) |
| `dim_repeat_trip_distribution`  | Monthly repeat passenger trip counts (1–10+) |
| `fact_trips`                    | Trip-level facts (distance, fare, ratings) |
| `city_target_passenger_rating` | Target avg. ratings per city |
| `monthly_target_new_passengers`| Monthly city-level new passenger goals |
| `monthly_target_trips`         | Monthly city-level trip goals |

---

## 📊 Metrics Tracked

- Total Trips
- Total Revenue
- Repeat Passenger Rate (RPR)
- New vs. Repeat Ratio
- Passenger Ratings (Avg)
- Trip Frequency Buckets (1–10+ trips/month)
- Target vs Actual (Trips, New Users, Ratings)

---

## 🔥 June 2024 Red Flags

- **Revenue down ₹26L**
- **RPR fell across cities**
- If left unchecked → projected **₹1 Cr loss** by Sep

---

## 🏙️ City-wise Highlights & Issues

### 🧂 Kochi (Monsoon May 30 Onward)
- 13% RPR drop, 4.2L fewer weekday repeat rides
- 31% drop in new passengers → ₹3.2L impact
- **Total Est. Loss: ₹12L**

### 🏜️ Jaipur
- 34% RPR crash
- AFT increased without demand pickup → ₹4.5L loss
- Failed conversion from new to repeat users
- **Total Est. Loss: ₹7L**

### 🔥 Lucknow (Heatwave, 44.7°C)
- Weekend rides up by 13%
- 14% rise in new passengers
- Poor repeat experience (Avg. rating: 5.9)
- Risk of churn despite acquisition success

---

## 🧠 Strategic Recommendations

### ✅ Kochi  
- **Now**: Monsoon coupons, 1st-ride free, corporate tie-ups  
- **Next**: Loyalty programs, route optimization  
- **Later**: Dynamic pricing, 2W fleet for hyperlocal services

### ✅ Jaipur  
- **Now**: Weekday passes, re-engagement campaigns  
- **Next**: Referral bonuses, tiered loyalty system  
- **Later**: AI-based trip pricing, seasonal ride bundles

### ✅ Lucknow  
- **Now**: Focus on service quality + weekend offers  
- **Next**: Heat-adaptive fare strategy  
- **Later**: Retention programs for converted new users

---

## 📈 Power BI Dashboard

👉 [Click to View Report](https://app.powerbi.com/view?r=eyJrIjoiMDc0MjU2N2MtMjIzZS00ZmMxLWE3NDYtYTg0YjkxZmFlMTI3IiwidCI6ImM2ZTU0OWIzLTVmNDUtNDAzMi1hYWU5LWQ0MjQ0ZGM1YjJjNCJ9)

---

## 🗂️ Entity Relationship Diagram (ERD)

![ERD](A_digital_Entity-Relationship_Diagram_(ERD)_illust.png)

---

## 💡 Final Takeaways

- Business in Tier-2 cities is **event-sensitive**: weather, day type, local trends matter
- Blanket strategies = burn. Custom local tactics = retention + revenue
- Acquisition is easy. Retention is the battlefield. 

---

## 👨‍💻 About Me

**Viknesh Vengatesh (Vicky)**  
Aspiring Data Analyst  
🔧 Power BI | SQL | Excel | Python  
📫 [LinkedIn](https://www.linkedin.com/in/your-link)

---

## 🛠 Tools Used

- Power BI for Dashboard  
- Excel for Data Cleaning  
- SQL for Data Preparation  
- Canva for ERD Design

---

