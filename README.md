# 🚲 Cyclistic Bike-Share Analysis  
**Case Study:** How Does a Bike-Share Navigate Speedy Success?  
**Tool Used:** Tableau  
**Author:** Peris Ndanu  
**Date:**  30th January 2025

---

## 📌 Objective

The purpose of this case study is to analyze usage data from a fictional bike-share company, Cyclistic, to uncover user behavior patterns and provide actionable insights on converting **casual riders** into **annual members**.

---

## 📁 Dataset

**Source:** Divvy Trip Data (publicly available from the City of Chicago)  
**Time Frame:** 12 months of ride data  
**File Format:** `.csv`  
**Key Columns:**
- `ride_id`, `rideable_type`
- `started_at`, `ended_at`
- `start_station_name`, `end_station_name`
- `member_casual` (user type: member or casual)

---

## 🧹 Data Cleaning & Preparation

Performed in **Excel Power Query** before importing into Tableau:

- Combined 12 monthly `.csv` files into a single dataset
- Removed null values and system-generated test data
- Created calculated fields:
  - `ride_length` (in minutes)
  - `day_of_week` from `started_at`
  - `hour_of_day` from `started_at`

---

## 📊 Tableau Visualizations

### 1. 🚴‍♂️ Total Rides by User Type
**Chart:** Bar Chart  
**Insight:** Members account for 60.31% of total rides; casual users 39.69%.
![total rides by member type](./images/image.png)

---

### 2. ⏱️ Ride Duration by User Type
**Chart:** Box Plot  
**Insight:** Casual users take significantly longer rides than members.

---

### 3. 📆 Rides by Day of the Week
**Chart:** Stacked Bar Chart  
**Insight:** Members ride more on weekdays; casual users peak on weekends.

---

### 4. 🕒 Hourly Usage Trends
**Chart:** Line Chart  
**Insight:** Members peak during commute hours; casual riders peak mid-day.

---

### 5. 📍 Top Start Stations
**Chart:** Horizontal Bar Chart  
**Insight:** Casual users tend to begin rides near tourist and leisure spots.

---

## 📌 Dashboard

Created an interactive **Tableau Dashboard** featuring:
- Filters for user type
- KPI Cards (Total Rides, Avg Ride Duration)
- Interactive usage map
- Daily and hourly patterns
- Top 10 stations

📷 **[Insert Screenshot or Tableau Public link]**

---

## 🧠 Key Insights Summary

| Metric | Members | Casual Users |
|--------|---------|--------------|
| Avg Ride Duration | ~13 mins | ~24 mins |
| Peak Days | Weekdays | Weekends |
| Peak Hours | 8 AM & 5 PM | 11 AM – 3 PM |
| Ride Purpose | Commuting | Leisure/Tourism |

---

## 🎯 Business Recommendations

1. **Promote Weekend Membership Deals** for casual riders
2. **Introduce Referral Program** to encourage member sign-ups
3. **Send Personalized Emails** with discounts after casual rides
4. **Create Flexible Membership Plans** like weekly or day passes

---

## 📎 File Structure

